# 1. Contexto e problema observado

## Contexto do projeto

O NEXUS é um aplicativo Android pessoal, offline-first, com módulos integrados para agenda, tarefas, eventos, compromissos, projetos e finanças. Seu desenvolvimento utiliza um repositório ativo de código e uma estrutura documental separada.

A documentação do projeto distingue:
- repositório ativo do aplicativo, com código e documentação técnica vigente;
- repositório central de documentação, com uma área GOOGLE_IA para espelhar documentação técnica e uma área CHATGPT para memória estratégica e histórica;
- artefatos internos do ambiente Google AI Studio, usados como memória operacional complementar.

## Experimento que originou a necessidade

Foram preparados três backups JSON independentes para representar:
- um universitário que também administra uma pequena assistência técnica;
- uma pessoa aposentada envolvida com família, comunidade, casas alugadas e produção artesanal;
- um empresário que coordena uma distribuidora, lojas, equipe e finanças pessoais.

O Google AI Studio investigou o contrato real de backup e as regras de domínio antes de gerar os arquivos. O relatório recebido declarou validação estática aprovada. Posteriormente, a presença dos três arquivos foi conferida no repositório ativo.

O usuário explorou inicialmente o perfil universitário e relatou uma experiência positiva com a Agenda, a densidade moderada dos registros e a distinção visual de alertas.

## Problema documental

A experiência gerou materiais de natureza diferente:
- contextos humanos dos perfis;
- instrução enviada ao ambiente de desenvolvimento;
- relatório de geração e validação;
- resultados observados no aplicativo;
- defeitos funcionais;
- correções visuais solicitadas;
- ideias de evolução de produto;
- possibilidades de longo prazo.

Armazenar tudo num único documento dificultaria recuperar o tipo de informação necessário. Criar catálogos separados de ideias dentro de cada experimento produziria duplicação e risco de divergência.

A necessidade concreta foi estabelecer uma organização que permita perguntas diferentes:
- Quais erros foram observados?
- Quais correções foram solicitadas?
- Quais ideias surgiram após o teste?
- O que é apenas visão futura?
- O que foi implementado e validado?
- Qual evidência originou cada item?

## Problema de continuidade

Um defeito relatado durante o uso — perda da tela e do conteúdo de edição após rotação do dispositivo — precisa permanecer rastreável até a investigação, proposta de correção, implementação e teste. Sem um identificador estável e um estado explícito, uma conversa futura pode esquecer o problema ou declarar sua resolução sem evidência.

O caso também mostrou que a memória estratégica precisa ser separada do registro técnico de implementação: uma correção solicitada não é ainda uma mudança no código.
