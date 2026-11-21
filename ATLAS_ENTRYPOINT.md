# ATLAS_ENTRYPOINT — Entrada obrigatória para IAs

**Público:** qualquer IA, agente ou pessoa técnica que vá interpretar, manter ou evoluir o ATLAS.

**Regra:** este arquivo é a porta de entrada. Não presuma que o README, a memória da conversa ou uma instrução isolada contenha todo o contexto necessário.

## 1. Identifique o contexto da tarefa

Determine se você está estudando a metodologia, contribuindo para o ATLAS oficial, inicializando um índice individual, recuperando um projeto, avaliando sua estrutura ou executando auditoria/reconstrução. Não misture essas operações.

## 2. Leia a documentação na ordem indicada

1. [README.md](README.md) — visão geral.
2. [MANIFEST.md](MANIFEST.md) — inventário, autoridade e sequência.
3. [ATLAS_MASTER.md](ATLAS_MASTER.md) — visão integrada.
4. [core/FOUNDATION.md](core/FOUNDATION.md) — princípios.
5. [core/ADAPTIVE_PROJECT_ARCHITECTURE.md](core/ADAPTIVE_PROJECT_ARCHITECTURE.md) — arquitetura adaptável.
6. [core/UNIVERSAL_PROJECT_ENGINEERING.md](core/UNIVERSAL_PROJECT_ENGINEERING.md) — engenharia universal.
7. [core/KNOWLEDGE_AND_MEMORY_MODEL.md](core/KNOWLEDGE_AND_MEMORY_MODEL.md) — memória e conhecimento.
8. [core/ATLAS_INDEX_SPECIFICATION.md](core/ATLAS_INDEX_SPECIFICATION.md) — índice pessoal.
9. [core/SOURCE_AUTHORITY_AND_PROVENANCE.md](core/SOURCE_AUTHORITY_AND_PROVENANCE.md) — autoridade e procedência das fontes.
10. [protocols/CONTEXT_RECOVERY.md](protocols/CONTEXT_RECOVERY.md) — recuperação contextual.
11. [protocols/AMBIGUITY_RESOLUTION.md](protocols/AMBIGUITY_RESOLUTION.md) — resolução de ambiguidades e divergências.
12. [protocols/SESSION_CONTINUITY.md](protocols/SESSION_CONTINUITY.md) — continuidade e handoff.
13. [protocols/PROJECT_DISCOVERY_AND_REGISTRATION.md](protocols/PROJECT_DISCOVERY_AND_REGISTRATION.md) — descoberta de projetos.
14. [governance/GOVERNANCE.md](governance/GOVERNANCE.md) — governança.
15. [templates/README.md](templates/README.md) — selecione apenas os templates necessários à tarefa.

Não é necessário ler todos os templates em toda sessão. Se um arquivo indicado não existir, registre-o como pendência; não invente seu conteúdo.

## 3. Reconstrua a autoridade antes de interpretar

Inventarie as fontes acessíveis; identifique finalidade, origem, domínio, estado, relações, autoridade, versão, sincronização e permissões. Determine autoridade por domínio, não por nome de arquivo ou data isolada. Diferencie originais, fontes oficiais, espelhos, cópias, derivações, arquivos históricos e memórias operacionais. Registre a cadeia de procedência e separe fatos observados, declarações, hipóteses, inferências e desconhecidos. Use o [modelo de autoridade e procedência](core/SOURCE_AUTHORITY_AND_PROVENANCE.md) e o [mapa de fontes](templates/SOURCE_MAP_TEMPLATE.md). Se houver divergência ou autoridade incerta, siga o [protocolo de resolução de ambiguidades](protocols/AMBIGUITY_RESOLUTION.md) antes de agir.

## 4. Preserve antes de modificar

Não reorganize, substitua, mova ou exclua documentos apenas porque parecem redundantes ou desatualizados. Primeiro compreenda sua função e relações. Mudanças que alterem autoridade, integridade ou histórico exigem justificativa e autorização adequada.

## 5. Não finja acesso ou validação

Não declare acesso a fontes privadas sem acesso efetivo. Não declare sincronização sem comparação adequada. Não confunda leitura de documentação ou inspeção de código com teste funcional. Registre escopo, método, resultado e limitações.

## 6. Trabalhe em lotes controlados

Explique objetivo e escopo, identifique dependências, preserve o estado, proponha a mudança, trabalhe em branch quando possível, revise coerência e referências, apresente evidências e respeite aprovação humana antes de integrar mudanças relevantes.

## 7. Resultado esperado ao assumir um projeto

Apresente identidade, objetivo, arquitetura, mapa de fontes, hierarquia de autoridade, estado atual, decisões vigentes, concluídos, pendentes, bloqueios, riscos, ambiguidades, verificações realizadas e próximo passo.

Não comece implementação enquanto houver ambiguidade crítica sobre a fonte de verdade ou sobre permissões.

## 8. Regra de evolução

Se encontrar lacuna, contradição ou oportunidade, descreva o problema com evidência, identifique documentos afetados e diferencie requisito, hipótese e proposta. Não altere silenciosamente a metodologia.

A metodologia deve evoluir por evidências e testes, não por improvisação.
