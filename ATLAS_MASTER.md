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

A expressão “memória infinita” pode descrever conceitualmente uma memória externa expansível, persistente e independente de uma plataforma, mas não significa capacidade literalmente ilimitada.

## 4. Arquitetura em três camadas

### 4.1 ATLAS oficial

Mantém a metodologia, protocolos, templates, exemplos, governança e testes. É público para leitura e tem contribuição controlada.

### 4.2 ATLAS_INDEX individual

Repositório pessoal que cataloga os projetos de um usuário. Registra identificadores, links, finalidade, estado, versão ATLAS e metadados úteis. Pode ser público ou privado conforme decisão do usuário.

### 4.3 Repositórios individuais de projetos

Cada projeto mantém seus próprios documentos, artefatos, dados, código e regras. A estrutura é definida conforme suas necessidades e pode incluir múltiplas fontes com autoridades distintas.

## 5. Princípios estruturais

1. **Adaptação:** a estrutura nasce da natureza e das necessidades do projeto.
2. **Separação de responsabilidades:** cada documento deve ter função clara.
3. **Autoridade explícita:** fontes de verdade devem ser identificáveis por domínio.
4. **Procedência:** informações relevantes devem ter origem e relações compreensíveis.
5. **Temporalidade:** estado vigente, histórico e conteúdo desatualizado não podem ser confundidos.
6. **Rastreabilidade:** decisões e mudanças importantes precisam de registro.
7. **Continuidade:** uma nova IA deve conseguir reconstruir o contexto sem depender da conversa anterior.
8. **Evolução controlada:** a arquitetura documental pode crescer ou mudar sem apagar sua história.
9. **Segurança:** acesso e permissão são parte do modelo, não um adendo.
10. **Honestidade operacional:** a IA deve declarar o que verificou, como verificou e o que permanece desconhecido.
11. **Proporcionalidade:** o custo de manter a estrutura não deve superar seu benefício.
12. **Controle humano:** ações relevantes e mudanças de risco devem respeitar autorização explícita.

## 6. Ciclo de vida proposto

1. Descoberta e entendimento.
2. Análise de natureza, escopo e complexidade.
3. Projeto da arquitetura documental e operacional.
4. Inicialização e registro.
5. Desenvolvimento e captura de conhecimento.
6. Recuperação e continuidade.
7. Revisão de integridade e coerência.
8. Evolução da estrutura.
9. Arquivamento, transferência ou encerramento.

Este ciclo é um modelo de trabalho inicial e deverá ser testado em projetos reais.

## 7. Recuperação contextual

A recuperação deve reconstruir não apenas o conteúdo, mas também:
- quem ou o que produziu a informação;
- onde ela está armazenada;
- qual sua finalidade;
- qual fonte tem autoridade sobre aquele domínio;
- se é vigente, histórica, espelhada ou operacional;
- de quais outras fontes depende;
- quando e como foi verificada;
- quais alterações são permitidas.

A metodologia inicial está em [CONTEXT_RECOVERY.md](protocols/CONTEXT_RECOVERY.md).

## 8. Evolução da arquitetura

Quando um projeto cresce, a IA deve avaliar se a estrutura continua adequada. Pode propor novos documentos, separação de responsabilidades, índices, registros ou reorganizações. Deve explicar o motivo, mapear referências e preservar conteúdo e histórico. Não deve executar mudanças destrutivas por inferência própria.

## 9. Validação

Uma capacidade só deve ser descrita como validada quando houver teste adequado e evidência registrada. Um documento que descreve um protocolo não prova que o protocolo funciona. Um repositório sincronizado não prova que a aplicação executa corretamente.

O ATLAS será avaliado em projetos de naturezas diferentes, incluindo o caso NEXUS, que revelou falhas de interpretação de hierarquia documental. Esse caso é evidência de um problema real observado, não prova antecipada de que o ATLAS já o resolve.

## 10. Estado e próximos módulos

A fundação está sendo estabelecida. Os próximos módulos deverão detalhar:
- engenharia universal e diagnóstico de projetos;
- modelo de memória e conhecimento;
- continuidade e handoff entre IAs;
- ATLAS_INDEX e registro de projetos;
- descoberta, reconhecimento e recuperação;
- governança e segurança;
- templates e exemplos;
- reconstrução, auditoria e testes.

Mudanças nesta visão devem ser registradas e refletidas nos documentos dependentes.
