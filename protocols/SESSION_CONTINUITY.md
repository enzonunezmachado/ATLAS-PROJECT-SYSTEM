# Protocolo de continuidade entre sessões e IAs

**Estado:** protocolo inicial para validação.

## 1. Objetivo

Permitir que o trabalho seja interrompido e retomado em outra conversa, plataforma, modelo ou pessoa sem depender exclusivamente do histórico integral da sessão anterior.

## 2. Princípio

A continuidade deve transferir estado operacional e referências verificáveis, não apenas um resumo narrativo. A IA que recebe o contexto deve consultar as fontes relevantes antes de agir.

## 3. Encerramento de sessão

Quando a sessão produzir mudanças ou conhecimento relevante, preparar um registro de continuidade com:
- identidade e objetivo do projeto;
- tarefa trabalhada;
- estado anterior e estado resultante;
- decisões tomadas e seu estado de aprovação;
- arquivos, fontes e versões alterados;
- evidências de execução e verificação;
- pendências, bloqueios e riscos;
- perguntas em aberto;
- próximo passo recomendado;
- limites do que não foi verificado.

Não registrar como concluído algo que apenas foi planejado ou tentado.

## 4. Abertura de sessão

A IA que assume deve:
1. identificar o projeto e a tarefa;
2. ler as instruções de entrada;
3. consultar o índice, se disponível;
4. executar a recuperação contextual das fontes pertinentes;
5. comparar o registro de continuidade com o estado atual;
6. identificar mudanças ocorridas desde a última sessão;
7. apresentar uma síntese operacional;
8. confirmar ambiguidades críticas antes de modificar fontes.

O registro de continuidade é um ponto de partida, não uma autoridade superior às fontes oficiais atuais.

## 5. Transferência entre IAs

O pacote de handoff deve usar linguagem direta, nomes de arquivos e links explícitos. Deve indicar:
- o que a próxima IA precisa ler;
- o que não deve modificar;
- quais decisões estão aprovadas;
- quais propostas aguardam aprovação;
- quais ferramentas ou acessos são necessários;
- quais ações já foram executadas;
- quais afirmações ainda precisam de confirmação.

## 6. Sincronização após retomada

Se houver diferença entre o handoff e o repositório atual, não sobrescreva automaticamente o estado mais recente. Determine a origem e a autoridade de cada informação e registre a divergência.

## 7. Modelo de registro

Um modelo reutilizável será disponibilizado em `templates/` após a definição do conjunto inicial de templates. Até lá, use os campos descritos neste protocolo sem inventar um arquivo oficial inexistente.

## 8. Critérios de sucesso

Uma transferência é bem-sucedida quando a IA receptora consegue identificar o projeto, localizar as fontes autoritativas, explicar o estado atual, distinguir decisões de propostas, reconhecer limites e continuar a tarefa sem duplicar ou destruir trabalho anterior.

## 9. Limites

Um handoff não garante continuidade se as fontes estiverem inacessíveis, desatualizadas, incompletas ou contraditórias. Essas condições devem ser explicitadas.
