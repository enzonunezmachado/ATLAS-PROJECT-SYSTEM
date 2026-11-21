# 2. Estrutura documental aplicada no NEXUS

A organização foi adaptada ao projeto e ao tipo de informação. Não se propôs uma estrutura universal para todos os repositórios.

## Separação em duas áreas

### A. Repositório do projeto — memória estratégica e experimentos

No repositório NEXUS-DOCUMENTACAO, a área CHATGPT mantém contexto, intenção, evolução e decisões estratégicas.

O catálogo central de ideias continua único em CHATGPT/03_IDEIAS_E_BRAINSTORMS.md. As pastas de experimentos preservam evidências e observações específicas sem replicar o catálogo.

### B. Pasta de experimento

O experimento de três vidas simuladas foi organizado em:

| Pasta | Responsabilidade | Por que existe |
|---|---|---|
| 01_PROMPT | Instrução enviada ao ambiente de desenvolvimento | Preservar escopo, autonomia, limites e origem da execução |
| 02_PERFIS | Contexto humano dos cenários | Evitar misturar contexto de vida com especificação técnica |
| 03_ACOMPANHAMENTO | Etapas, observações, estados e próximos passos | Manter uma linha de continuidade do experimento |
| 04_RESULTADOS | Relatórios de geração e testes no aplicativo | Separar validação estática de comportamento observado |
| 05_OBSERVACOES_POS_TESTE | Problemas, correções, ideias, futuro e observações positivas | Facilitar recuperação por tipo de necessidade sem duplicar o catálogo central |

O README da pasta do experimento funciona como índice e explica limites, arquivos e execução.

## Responsabilidades dos documentos pós-teste

- Problemas e correções: defeitos observados e ajustes explicitamente solicitados, com critérios de validação.
- Ideias de evolução: oportunidades de produto que ainda precisam de análise.
- Visão de longo prazo: possibilidades sem prioridade ou aprovação para o próximo ciclo.
- Resultado da exploração: comportamentos positivos, experiência relatada e aspectos que devem ser preservados.

## O que ficou fora da pasta do experimento

- Ideias continuam indexadas no catálogo central, sem duplicar os detalhes.
- Decisões estratégicas continuam em seu documento próprio.
- Propostas ao Google AI Studio só são registradas quando efetivamente encaminhadas.
- Documentação técnica vigente permanece no repositório técnico do NEXUS.
- JSONs de teste permanecem no repositório ativo do aplicativo; a documentação estratégica mantém links, não cópias.

## Princípio de organização

A estrutura deve responder a uma necessidade de recuperação real. Criar uma pasta só se justifica quando ela separa uma responsabilidade que seria difícil localizar ou manter junto das demais. Não é necessário criar um arquivo por categoria em todo projeto.
