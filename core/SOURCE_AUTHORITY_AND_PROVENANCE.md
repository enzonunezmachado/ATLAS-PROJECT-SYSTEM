# Modelo de autoridade e procedência das fontes

**Estado:** modelo inicial para validação.

## 1. Objetivo

Definir como um projeto declara e como uma IA identifica a autoridade, a origem e as relações entre suas fontes. O modelo evita que a IA trate todos os arquivos encontrados como equivalentes ou suponha que uma fonte governe todos os domínios.

## 2. Conceitos que não devem ser confundidos

- **Origem:** quem produziu a informação ou de qual fonte ela deriva.
- **Responsável pela manutenção:** pessoa, equipe ou sistema que responde por atualizar a fonte.
- **Autoridade:** fonte ou regra reconhecida pelo projeto para governar determinado domínio.
- **Localização:** onde o conteúdo está armazenado ou pode ser acessado.
- **Estado temporal:** condição da informação em determinado momento, como vigente, histórica, substituída ou desconhecida.
- **Integridade:** evidência de que o conteúdo não foi alterado em relação a uma referência definida.
- **Sincronização:** relação de atualização entre fontes, limitada ao escopo e ao método efetivamente verificados.
- **Procedência:** cadeia documentada de origem, transformações, cópias, revisões e derivações de uma informação.

Uma fonte pode ser autoritativa em um domínio e apenas auxiliar em outro. A localização mais recente, o nome do arquivo, a data de modificação ou a semelhança textual não estabelecem autoridade isoladamente.

## 3. Autoridade por domínio

A autoridade deve ser declarada por domínio, não atribuída genericamente a um repositório inteiro quando ele contém materiais com funções diferentes.

Exemplos de domínios:
- requisitos e escopo;
- arquitetura e decisões técnicas;
- código-fonte;
- operação e procedimentos;
- pesquisa e referências externas;
- decisões estratégicas;
- histórico e registros de sessão;
- dados e resultados de execução.

Para cada domínio, registre:
1. fonte autoritativa ou regra de autoridade;
2. responsável pela manutenção;
3. justificativa ou declaração que sustenta a autoridade;
4. fontes complementares;
5. limites e exceções;
6. estado e data da última confirmação.

Se a autoridade não estiver declarada ou não puder ser sustentada por evidência, marque-a como **desconhecida** ou **ambígua**. Não transforme inferência em regra oficial.

## 4. Tipos de relação entre fontes

Use relações explícitas sempre que possível:

| Relação | Significado |
|---|---|
| Original | Fonte primária em que o conteúdo foi produzido ou mantido |
| Espelho | Reprodução destinada a acompanhar uma fonte de origem, dentro de um escopo definido |
| Cópia de trabalho | Cópia usada para edição ou consulta, sem autoridade automática |
| Derivação | Conteúdo produzido a partir de uma ou mais fontes, com transformação |
| Exportação | Representação gerada por outro sistema ou formato |
| Histórico | Registro preservado de um estado ou período anterior |
| Memória estratégica | Registro de decisões, contexto e intenção estratégica |
| Memória operacional | Artefato usado por uma ferramenta ou IA para orientar sua operação |
| Referência externa | Fonte fora do controle direto do projeto |

Não presuma que espelhos sejam completos, atuais ou bidirecionais. Registre direção, escopo, frequência ou evento de sincronização e método de comparação, quando conhecidos.

## 5. Cadeia de procedência

Quando uma informação for copiada, resumida, transformada ou incorporada em outro documento, registre, conforme o risco:
- identificador e localização da fonte de origem;
- autor ou responsável conhecido;
- data, versão, commit ou estado observado;
- transformação aplicada;
- destino ou documento derivado;
- responsável pela transformação;
- evidência disponível;
- limitações ou lacunas.

Uma citação ou link identifica uma referência, mas não comprova que o conteúdo derivado permaneça fiel ou atualizado. Resumos de IA devem ser tratados como derivados, não como substitutos automáticos da fonte original.

## 6. Resolução de precedência

Quando fontes divergem, a ordem de análise é:
1. domínio afetado;
2. autoridade explicitamente declarada para esse domínio;
3. procedência e relação entre as fontes;
4. temporalidade e estado;
5. integridade e escopo de sincronização;
6. evidência e limitações;
7. regra de decisão do próprio projeto.

Recência pode ser relevante, mas não substitui autoridade. Um arquivo mais novo pode ser rascunho; um arquivo antigo pode continuar sendo o registro histórico correto.

Se a precedência continuar incerta, suspenda a ação dependente e consulte o responsável humano.

## 7. Limites e segurança

- Acesso de leitura não implica permissão de edição.
- A existência de uma cópia não autoriza sobrescrever a origem.
- Um hash igual demonstra igualdade dos objetos comparados, não validade semântica.
- Um espelho parcialmente comparado não pode ser declarado integralmente sincronizado.
- Uma fonte inacessível não deve ser descrita como verificada.
- Não exponha credenciais, segredos ou dados privados ao construir mapas de fontes.
- Preserve registros históricos conforme as regras do projeto.

## 8. Instrumentos relacionados

- [Protocolo de recuperação e verificação contextual](../protocols/CONTEXT_RECOVERY.md)
- [Protocolo de resolução de ambiguidades](../protocols/AMBIGUITY_RESOLUTION.md)
- [Template de mapa de fontes](../templates/SOURCE_MAP_TEMPLATE.md)
- [Governança](../governance/GOVERNANCE.md)

## 9. Critério de validação

O modelo deve ser testado em projetos com múltiplos repositórios, fontes oficiais por domínio, espelhos, acervos históricos e memórias operacionais. A validação deve observar se a IA identifica corretamente autoridade, procedência, estado, permissões e limites sem inventar relações nem alterar fontes indevidamente.
