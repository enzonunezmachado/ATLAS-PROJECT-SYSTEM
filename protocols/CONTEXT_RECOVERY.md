# Protocolo de recuperação e verificação contextual

**Estado:** proposta inicial para validação.  
**Objetivo:** impedir que uma IA confunda conteúdo localizado com conhecimento corretamente compreendido.

## 1. Princípio

A recuperação de um projeto não termina quando os arquivos são encontrados ou lidos. A IA precisa compreender origem, finalidade, autoridade, validade, relações e permissões das fontes.

## 2. Etapas obrigatórias

### Etapa 1 — Inventariar
Liste repositórios, diretórios, documentos, sistemas e outras fontes efetivamente acessíveis. Registre também fontes mencionadas, mas não acessíveis.

### Etapa 2 — Identificar finalidade
Para cada fonte relevante, determine:
- responsável ou origem conhecida;
- finalidade;
- domínio de informação;
- público ou consumidor;
- estado declarado;
- restrições de acesso e alteração.

### Etapa 3 — Mapear relações
Identifique se a fonte é:
- original;
- fonte oficial;
- espelho;
- cópia de trabalho;
- exportação;
- arquivo histórico;
- memória operacional;
- referência externa.

Registre origem, destino, dependências, sincronização esperada e transformações conhecidas. Não infira equivalência apenas pela semelhança de conteúdo.

### Etapa 4 — Determinar autoridade por domínio
Para cada domínio (por exemplo, requisitos, código, decisões, operação, pesquisa ou histórico), identifique a fonte que o projeto reconhece como autoritativa e a regra que sustenta essa escolha.

Se a autoridade não estiver declarada ou houver evidência conflitante, marque como desconhecida e solicite esclarecimento quando isso afetar a tarefa.

### Etapa 5 — Determinar temporalidade
Registre datas, versões, commits, status e eventos relevantes. Diferencie:
- vigente;
- histórico;
- substituído;
- espelhado;
- desatualizado;
- desconhecido.

Não trate o conteúdo histórico como instrução vigente sem evidência.

### Etapa 6 — Verificar integridade e sincronização
Escolha uma verificação proporcional ao risco: comparação de hashes, commits, versões, metadados, conteúdo ou validação do sistema de origem.

Registre exatamente o que foi comparado. Uma amostra não comprova sincronização integral. Hashes iguais comprovam igualdade dos objetos comparados, não validade semântica nem funcionamento do sistema.

### Etapa 7 — Tratar divergências
Não classifique automaticamente toda diferença como conflito. Ela pode representar histórico, especialização, atraso de sincronização, conteúdo complementar ou divergência real.

Descreva a diferença, o domínio afetado, as fontes envolvidas e o impacto potencial.

### Etapa 8 — Registrar evidências e limites
Para cada conclusão importante, identifique:
- afirmação;
- fonte ou evidência;
- método de verificação;
- data ou versão observada;
- nível de confiança;
- limitações e itens não verificados.

### Etapa 9 — Construir a síntese operacional
Somente depois das etapas anteriores, apresente a compreensão do projeto, suas fontes de verdade, estado, decisões, pendências, restrições e próximo passo.

### Etapa 10 — Obter autorização antes de mudanças sensíveis
Não mova, substitua, renomeie, sobrescreva ou exclua fontes por parecerem redundantes. Mudanças que alterem autoridade, sincronização, histórico ou integridade precisam de justificativa e autorização adequada.

## 3. Modelo mínimo de registro de fonte

| Campo | Descrição |
|---|---|
| Identificador | Nome estável da fonte |
| Localização | URL, repositório, caminho ou sistema |
| Origem/responsável | Quem mantém ou produziu |
| Finalidade | Para que existe |
| Domínio | Que tipo de informação contém |
| Autoridade | Oficial, derivada, auxiliar ou desconhecida |
| Relação | Original, espelho, cópia, histórico etc. |
| Estado | Vigente, histórico, desatualizado etc. |
| Versão/data | Referência temporal observada |
| Permissões | Leitura, proposta, edição, aprovação |
| Verificação | Método e resultado |
| Limitações | O que não foi possível confirmar |

Para projetos com múltiplas fontes, use o [template SOURCE_MAP](../templates/SOURCE_MAP_TEMPLATE.md) como instrumento de registro. O template não substitui as declarações de autoridade do próprio projeto nem a verificação das fontes.

## 4. Modelo de declaração de verificação

Use linguagem explícita, por exemplo:

- **Verificado:** os arquivos X e Y foram comparados pelo método Z na versão/commit identificado.
- **Não verificado:** não houve execução, teste funcional ou inspeção de todos os arquivos.
- **Inferido:** a relação parece ser X devido às evidências A e B, mas não há declaração explícita.
- **Desconhecido:** não há informação suficiente para concluir.

## 5. Critérios de bloqueio

Não iniciar mudanças que dependam da autoridade de uma fonte quando:
- duas fontes reivindicam autoridade sobre o mesmo domínio sem regra de precedência;
- a fonte oficial não pode ser identificada;
- a tarefa exige acesso não disponível;
- não está claro se o material é histórico ou vigente;
- a alteração pode causar perda irreversível;
- as permissões não estão claras.

Nesses casos, documente a ambiguidade e faça a pergunta mais específica possível.

## 6. Limites do protocolo

Este protocolo é uma proposta inicial. Sua eficácia precisa ser testada com projetos reais, diferentes estruturas e diferentes IAs. Cumprir a sequência documental não garante compreensão correta; os resultados devem ser avaliados por critérios observáveis.
