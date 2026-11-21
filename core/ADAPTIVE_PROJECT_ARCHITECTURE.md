# Arquitetura adaptável de projetos

## 1. Objetivo

Definir como uma IA deve descobrir e propor a estrutura documental e operacional apropriada para um projeto, sem impor uma árvore fixa.

## 2. Diagnóstico antes da estrutura

Antes de criar pastas ou documentos, compreenda:
- natureza do projeto e resultado pretendido;
- escopo, estágio e horizonte;
- participantes, papéis e responsabilidades;
- tipos de conhecimento e artefatos envolvidos;
- ferramentas e plataformas já utilizadas;
- requisitos legais, técnicos, operacionais e de privacidade;
- frequência de mudança e necessidade de histórico;
- riscos de perda, conflito, duplicação e acesso;
- como o projeto será retomado por outra pessoa ou IA.

Pergunte somente o que for necessário para decisões estruturais relevantes. Não transforme toda descoberta em questionário.

## 3. Projetar por responsabilidades

Considere quais responsabilidades precisam ser cobertas, por exemplo:
- identidade, visão e objetivos;
- escopo e requisitos;
- planejamento e execução;
- decisões e justificativas;
- conhecimento de referência;
- estado atual e pendências;
- histórico e mudanças;
- fontes, autoridade e procedência;
- riscos e permissões;
- instruções de continuidade.

Essas responsabilidades podem ficar em documentos separados, combinadas ou ser atendidas por sistemas externos. A escolha deve considerar clareza, tamanho, frequência de atualização, dependências e custo de manutenção.

## 4. Critérios para separar documentos

Separe quando:
- os conteúdos têm ciclos de atualização diferentes;
- há responsáveis ou permissões diferentes;
- um documento ficou difícil de consultar;
- uma área possui regras próprias;
- mudanças frequentes criam conflitos;
- o conteúdo tem valor independente ou precisa de histórico próprio.

Combine quando:
- os conteúdos são pequenos e fortemente relacionados;
- a separação criaria navegação desnecessária;
- a manutenção conjunta é mais simples e segura.

Não crie arquivos apenas para preencher uma estrutura predeterminada.

## 5. Evolução contínua

A estrutura deve ser revisada quando houver sinais como:
- crescimento significativo do volume;
- novos módulos, equipes ou domínios;
- aumento de conflitos ou duplicações;
- dificuldade recorrente para localizar a informação vigente;
- documentos com múltiplas funções incompatíveis;
- mudanças de ferramentas ou fontes;
- falhas de continuidade ou interpretação.

Ao propor evolução:
1. descreva o sinal observado;
2. apresente evidências;
3. identifique responsabilidades afetadas;
4. proponha a estrutura-alvo;
5. mapeie documentos, links e dependências;
6. defina migração e compatibilidade;
7. preserve o histórico;
8. solicite aprovação quando houver risco ou mudança de autoridade;
9. valide a estrutura após a mudança.

## 6. Não confundir estrutura com autoridade

Uma pasta chamada `official`, `docs` ou `archive` não estabelece por si só a autoridade de seu conteúdo. A arquitetura precisa declarar relações e regras explicitamente.

## 7. Resultado mínimo do diagnóstico

Antes da inicialização, produza:
- resumo do projeto;
- necessidades documentais identificadas;
- fontes existentes e sua autoridade conhecida;
- estrutura proposta com justificativa;
- artefatos essenciais e opcionais;
- regras de atualização e preservação;
- questões em aberto;
- plano de inicialização por etapas.

## 8. Regra de proporcionalidade

A arquitetura deve ser tão simples quanto possível e tão completa quanto necessário. O ATLAS não deve criar burocracia superior ao risco e à complexidade que pretende controlar.
