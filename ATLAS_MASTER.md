# ATLAS_MASTER — Documento mestre

**Nome:** ATLAS — Universal Project Memory & Engineering System  
**Estado:** em construção  
**Natureza:** metodologia universal adaptável para engenharia de projetos, memória externa e continuidade assistida por IA.

## 1. Propósito

O ATLAS busca tornar projetos compreensíveis, preserváveis e continuáveis por diferentes IAs, conversas e ferramentas, sem depender exclusivamente da memória interna de uma plataforma.

Seu problema central não é apenas armazenar informações. É permitir que uma IA interprete corretamente o significado, a procedência, a autoridade, a validade e as permissões associadas a essas informações.

## 2. O que o ATLAS é

Uma metodologia que orienta a IA a:
- compreender a natureza, o objetivo, o escopo e a complexidade de um projeto;
- identificar necessidades de organização e engenharia;
- propor uma arquitetura documental e operacional proporcional;
- estruturar conhecimento, decisões, estado, histórico e pendências;
- mapear fontes, autoridade, relações, versões e sincronização;
- recuperar contexto com evidências e incertezas explícitas;
- manter continuidade entre sessões, plataformas e modelos;
- detectar quando a estrutura existente precisa evoluir;
- preservar integridade, histórico e controle humano.

## 3. O que o ATLAS não é

- Não é um template rígido que todos os projetos devem copiar.
- Não é uma promessa literal de memória infinita.
- Não é um substituto universal para Git, bancos de dados, sistemas de gestão, armazenamento ou ferramentas especializadas.
- Não é uma IA autônoma autorizada a modificar qualquer fonte.
- Não é uma garantia de que todo conteúdo recuperado seja verdadeiro ou atual.
- Não é um repositório central de dados privados dos usuários.

## 4. Arquitetura em três camadas

### 4.1 ATLAS oficial
Mantém metodologia, protocolos, templates, exemplos, governança e testes. É público para leitura e tem contribuição controlada.

### 4.2 ATLAS_INDEX individual
Repositório pessoal que cataloga os projetos de um usuário. Registra identificadores, links, finalidade, estado, versão ATLAS e metadados úteis. Pode ser público ou privado.

### 4.3 Repositórios individuais de projetos
Cada projeto mantém seus próprios documentos, artefatos, dados, código e regras. A estrutura é definida conforme suas necessidades e pode incluir múltiplas fontes com autoridades distintas.

## 5. Princípios estruturais

1. Adaptação.
2. Separação de responsabilidades.
3. Autoridade explícita por domínio.
4. Procedência.
5. Temporalidade.
6. Rastreabilidade.
7. Continuidade.
8. Evolução controlada.
9. Segurança.
10. Honestidade operacional.
11. Proporcionalidade.
12. Controle humano.

## 6. Ciclo universal de engenharia

O ATLAS orienta descoberta, caracterização, análise de complexidade, modelagem, arquitetura, planejamento, execução, revisão e encerramento ou transição. A aplicação deve ser proporcional à natureza do projeto.

Detalhamento: [UNIVERSAL_PROJECT_ENGINEERING.md](core/UNIVERSAL_PROJECT_ENGINEERING.md).

## 7. Conhecimento e memória

A memória do projeto pode abranger identidade, objetivos, requisitos, referências, ideias, hipóteses, decisões, estado operacional, execução, histórico, riscos, continuidade e procedência. Essas categorias não exigem arquivos separados.

Detalhamento: [KNOWLEDGE_AND_MEMORY_MODEL.md](core/KNOWLEDGE_AND_MEMORY_MODEL.md).

## 8. Recuperação contextual e continuidade

A recuperação deve reconstruir não apenas conteúdo, mas origem, finalidade, autoridade, validade, relações e permissões. A continuidade entre sessões deve transferir estado operacional e referências verificáveis, não apenas um resumo narrativo.

Protocolos:
- [Recuperação contextual](protocols/CONTEXT_RECOVERY.md).
- [Continuidade entre sessões e IAs](protocols/SESSION_CONTINUITY.md).
- [Descoberta e registro de projetos](protocols/PROJECT_DISCOVERY_AND_REGISTRATION.md).

## 9. ATLAS_INDEX e templates operacionais

O índice individual cataloga projetos e aponta para seus espaços de trabalho. Não armazena automaticamente todo o conteúdo e não concede acesso a repositórios privados.

Especificação: [ATLAS_INDEX_SPECIFICATION.md](core/ATLAS_INDEX_SPECIFICATION.md).  
Modelos iniciais: [guia de templates](templates/README.md).

Os templates fornecem estruturas de partida para o índice, catálogo, registro de projeto, mapa de fontes e handoff. Seu uso deve ser seletivo e proporcional; copiar um template não substitui a definição de autoridade, permissões ou validação do projeto.

## 10. Evolução da arquitetura

Quando um projeto cresce, a IA deve avaliar se a estrutura continua adequada. Pode propor novos documentos, separação de responsabilidades, índices, registros ou reorganizações. Deve explicar o motivo, mapear referências e dependências, preservar histórico e obter autorização para mudanças sensíveis.

## 11. Validação

Uma capacidade só deve ser descrita como validada quando houver teste adequado e evidência registrada. Um documento que descreve um protocolo não prova que o protocolo funciona. Um repositório sincronizado não prova que a aplicação executa corretamente.

O caso NEXUS é evidência de um problema real observado, não prova antecipada de que o ATLAS já o resolve.

## 12. Próximos módulos

- Governança detalhada de fontes, permissões, privacidade e segurança.
- Exemplos de aplicação em projetos de diferentes naturezas.
- Reconstrução, auditoria e testes de aceitação.
- Avaliação de ferramentas e integrações opcionais.

Mudanças nesta visão devem ser registradas e refletidas nos documentos dependentes.
