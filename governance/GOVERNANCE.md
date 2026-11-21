# Governança inicial do ATLAS

## 1. Escopo

Estas regras se aplicam ao repositório oficial ATLAS. Projetos individuais devem definir sua própria governança, podendo adotar e adaptar estes princípios.

## 2. Princípios de contribuição

- Mudanças devem ter objetivo e justificativa claros.
- Documentos precisam manter responsabilidades distintas e referências coerentes.
- Mudanças estruturais devem atualizar o MANIFEST.
- Não apresentar hipóteses como capacidades comprovadas.
- Preservar histórico e rastreabilidade.
- Não introduzir dados privados de projetos ou usuários no repositório público.
- Preferir lotes pequenos, revisáveis e reversíveis.

## 3. Branches e integração

A branch `main` representa a versão integrada do ATLAS. Mudanças devem ser desenvolvidas em branches separadas e propostas por pull request sempre que possível.

A aprovação humana é necessária antes de integrar mudanças relevantes. A existência de uma branch ou pull request não garante que as configurações de proteção do GitHub estejam habilitadas; isso deve ser verificado nas configurações do repositório.

## 4. Níveis de mudança

### Editorial
Correções de linguagem, formatação e links sem alteração de significado.

### Evolutiva
Novos procedimentos, templates, exemplos ou esclarecimentos compatíveis com os princípios vigentes.

### Estrutural
Mudança na arquitetura, hierarquia, autoridade, fluxo de recuperação ou governança. Exige justificativa, análise de impacto e revisão explícita.

### Sensível
Mudança que possa afetar segurança, privacidade, permissões, integridade, histórico ou autoridade de fontes. Exige autorização humana explícita e plano de reversão quando possível.

## 5. Integridade documental

Antes de concluir um lote:
- verificar links internos;
- atualizar o MANIFEST;
- revisar consistência terminológica;
- conferir se as instruções não se contradizem;
- registrar limitações;
- preservar documentos históricos;
- confirmar quais arquivos foram realmente alterados.

## 6. Segurança e acesso

O repositório oficial pode ser público para leitura, mas a escrita deve permanecer restrita a colaboradores autorizados. Não incluir segredos, tokens, credenciais, dados pessoais sensíveis ou conteúdo privado de projetos.

Branch protection, revisão obrigatória, regras de aprovação, backups e releases devem ser configurados e verificados nas opções do GitHub. A documentação desta intenção não comprova que a configuração técnica já foi aplicada.

## 7. Versionamento

Mudanças relevantes devem ser registradas no CHANGELOG. Releases devem representar conjuntos revisados e coerentes de alterações. Não declarar uma versão estável antes de critérios de validação definidos.

## 8. Resolução de conflitos

Quando documentos divergirem:
1. identifique o domínio;
2. consulte a autoridade definida no MANIFEST e nos documentos especializados;
3. determine se a diferença é temporal, complementar ou conflitante;
4. não escolha silenciosamente uma interpretação;
5. registre a decisão e atualize referências relacionadas.

## 9. Transparência operacional

Toda entrega deve distinguir:
- o que foi proposto;
- o que foi alterado;
- o que foi revisado;
- o que foi testado;
- o que não foi possível verificar;
- o que depende de aprovação humana.


## 10. Matriz de permissões para IAs

As permissões devem ser definidas pelo projeto e pelo responsável humano. Na ausência de declaração, aplique o nível mais conservador.

| Operação | Condição padrão |
|---|---|
| Consultar fontes acessíveis | Permitido, respeitando privacidade e escopo |
| Comparar, analisar e resumir | Permitido; conclusões devem indicar fontes e limites |
| Propor mudanças | Permitido; separar proposta de execução |
| Criar rascunhos ou alterações reversíveis em branch | Permitido quando a tarefa e o escopo foram autorizados |
| Alterar fonte autoritativa ou propagar mudanças para espelhos | Exige autorização explícita para o escopo |
| Alterar autoridade, hierarquia, permissões ou política de retenção | Exige aprovação humana explícita |
| Excluir, sobrescrever ou migrar fontes históricas | Proibido sem autorização específica e plano de preservação/reversão |
| Publicar dados privados, segredos ou credenciais | Proibido |

A autorização para uma tarefa não deve ser interpretada como autorização irrestrita para ações adjacentes. Se o escopo mudar ou surgir risco não previsto, interrompa a ação afetada e solicite nova aprovação.

## 11. Procedência e evidências

Mudanças e conclusões relevantes devem manter rastreabilidade suficiente para reconstrução:
- fonte e domínio envolvidos;
- origem e responsável conhecido;
- versão, data, commit ou identificador observado;
- método e escopo de comparação ou verificação;
- resultado obtido;
- limitações e itens não verificados;
- autor da alteração e estado de aprovação.

Diferencie explicitamente **observado**, **declarado**, **inferido**, **proposto**, **executado**, **verificado** e **não verificado**. Não use “sincronizado”, “validado” ou “corrigido” além do que as evidências permitem.

## 12. Ambiguidades e preservação

A resolução de divergências deve seguir o [protocolo de resolução de ambiguidades](../protocols/AMBIGUITY_RESOLUTION.md). Enquanto autoridade, procedência ou permissão permanecer incerta, preserve as fontes e suspenda operações dependentes. A IA pode continuar atividades independentes desde que não amplie o risco.

## 13. Revisão humana e reversibilidade

Antes de uma mudança estrutural ou sensível, apresente objetivo, fontes afetadas, impacto, riscos, reversibilidade e plano de verificação. A aprovação deve ser específica o bastante para identificar o que foi autorizado. Uma aprovação de proposta não comprova que a mudança foi executada ou validada.
