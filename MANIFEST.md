# MANIFEST — Inventário e autoridade documental

Este manifesto registra a função dos documentos oficiais do ATLAS, sua autoridade e a sequência de leitura. Deve ser atualizado sempre que a estrutura mudar.

## Regras de autoridade

- Este repositório é a fonte oficial da metodologia ATLAS.
- O `README.md` apresenta o projeto, mas não substitui os protocolos.
- O `ATLAS_ENTRYPOINT.md` define a entrada e a sequência inicial para IAs.
- O `ATLAS_MASTER.md` consolida a visão integrada, mas não anula regras específicas dos documentos especializados.
- Documentos especializados governam seus respectivos domínios.
- A autoridade de fontes de um projeto deve ser identificada por domínio; origem, localização, integridade e recência não substituem uma declaração de autoridade.
- Ambiguidades sobre autoridade, procedência ou divergências devem seguir o protocolo próprio; a IA não pode escolher silenciosamente nem alterar fontes sensíveis para resolver incertezas.
- Exemplos demonstram aplicações; não criam regras universais por si só.
- Templates são pontos de partida, não estruturas obrigatórias.
- Histórico e changelog registram evolução; não devem ser tratados automaticamente como instruções vigentes.

## Inventário atual

| Caminho | Função | Estado |
|---|---|---|
| `README.md` | Apresentação humana e orientação inicial | Inicial |
| `ATLAS_ENTRYPOINT.md` | Entrada obrigatória e sequência de leitura para IAs | Inicial |
| `MANIFEST.md` | Inventário, autoridade e ordem de leitura | Inicial |
| `ATLAS_MASTER.md` | Visão integrada da metodologia e seus limites | Inicial |
| `CHANGELOG.md` | Histórico de mudanças relevantes | Inicial |
| `core/FOUNDATION.md` | Princípios, conceitos e limites | Inicial |
| `core/ADAPTIVE_PROJECT_ARCHITECTURE.md` | Análise e evolução de estruturas por projeto | Inicial |
| `core/UNIVERSAL_PROJECT_ENGINEERING.md` | Método de engenharia aplicável a diferentes tipos de projeto | Inicial |
| `core/KNOWLEDGE_AND_MEMORY_MODEL.md` | Classes de informação, estados, relações e metadados | Inicial |
| `core/ATLAS_INDEX_SPECIFICATION.md` | Arquitetura conceitual do índice pessoal | Inicial |
| `core/SOURCE_AUTHORITY_AND_PROVENANCE.md` | Modelo de autoridade por domínio, procedência e relações entre fontes | Inicial — não validado |
| `protocols/CONTEXT_RECOVERY.md` | Recuperação, procedência e verificação contextual | Inicial |
| `protocols/AMBIGUITY_RESOLUTION.md` | Tratamento de ambiguidades, divergências e bloqueios de decisão | Inicial — não validado |
| `protocols/SESSION_CONTINUITY.md` | Encerramento, retomada e transferência entre IAs | Inicial |
| `protocols/PROJECT_DISCOVERY_AND_REGISTRATION.md` | Descoberta, identificação e registro de projetos | Inicial |
| `governance/GOVERNANCE.md` | Regras de mudança, preservação e controle | Inicial |
| `templates/README.md` | Guia de seleção e uso dos templates | Inicial |
| `templates/ATLAS_INDEX_TEMPLATE.md` | Estrutura inicial do repositório índice individual | Inicial |
| `templates/PROJECT_REGISTRY_TEMPLATE.md` | Catálogo resumido de projetos | Inicial |
| `templates/PROJECT_RECORD_TEMPLATE.md` | Registro detalhado de um projeto | Inicial |
| `templates/SOURCE_MAP_TEMPLATE.md` | Mapa de fontes, autoridade, relações e verificação | Inicial |
| `templates/SESSION_HANDOFF_TEMPLATE.md` | Registro de continuidade e transferência de sessão | Inicial |
| `examples/README.md` | Índice de estudos de caso e exemplos contextuais | Inicial |
| `examples/case-studies/nexus-documentation-evolution/README.md` | Índice do estudo de caso NEXUS | Inicial — caso documentado |
| `examples/case-studies/nexus-documentation-evolution/01_CONTEXTO_E_PROBLEMA.md` | Contexto e necessidade de organização identificada no NEXUS | Inicial — caso documentado |
| `examples/case-studies/nexus-documentation-evolution/02_ESTRUTURA_DOCUMENTAL.md` | Estrutura documental aplicada e responsabilidades das pastas | Inicial — caso documentado |
| `examples/case-studies/nexus-documentation-evolution/03_RASTREABILIDADE_E_ESTADOS.md` | Identificadores, estados e cadeia de evidências | Inicial — caso documentado |
| `examples/case-studies/nexus-documentation-evolution/04_APRENDIZADOS_PARA_ATLAS.md` | Lições e questões para pesquisa metodológica | Inicial — não normativo |

## Áreas planejadas

- `core/`: fundamentos, modelos conceituais e engenharia universal.
- `protocols/`: procedimentos reproduzíveis para IAs.
- `templates/`: modelos reutilizáveis.
- `governance/`: autoridade, segurança, permissões, versionamento e manutenção.
- `examples/`: casos variados, incluindo projetos de software e não software.
- `reconstruction/`: recuperação, auditoria e testes de reconstrução.

Pastas planejadas podem ainda não conter arquivos. Não as considere implementadas até que seus documentos existam e estejam registrados aqui.

## Ordem recomendada de leitura

1. README
2. ATLAS_ENTRYPOINT
3. MANIFEST
4. ATLAS_MASTER
5. Fundação e arquitetura adaptável
6. Engenharia universal e modelo de memória
7. Especificação do ATLAS_INDEX
8. Protocolos aplicáveis à tarefa
9. Governança
10. Templates pertinentes
11. Exemplos e reconstrução, quando disponíveis e aplicáveis

## Política de manutenção

Toda inclusão, remoção, renomeação ou mudança de autoridade documental deve atualizar este manifesto no mesmo lote de alteração. Verifique links internos e referências cruzadas antes de concluir.
