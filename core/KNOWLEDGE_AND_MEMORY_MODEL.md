# Modelo de conhecimento e memória de projetos

**Estado:** modelo conceitual inicial.

## 1. Objetivo

Definir como o ATLAS distingue tipos de informação e mantém contexto útil ao longo do tempo. Memória não deve ser tratada como um depósito indiferenciado de texto.

## 2. Classes de informação

Uma arquitetura pode precisar de algumas ou de todas estas classes:

- **Identidade:** nome, propósito, contexto e limites do projeto.
- **Objetivos e requisitos:** resultados pretendidos e condições de aceitação.
- **Conhecimento de referência:** fatos, pesquisas, manuais, normas e materiais externos.
- **Ideias e hipóteses:** possibilidades ainda não aprovadas ou validadas.
- **Decisões:** escolhas tomadas, justificativas e estado de vigência.
- **Estado operacional:** situação atual, progresso, bloqueios e indicadores.
- **Execução:** tarefas, atividades, entregáveis e resultados.
- **Histórico:** eventos, versões, mudanças e estados anteriores.
- **Riscos e restrições:** ameaças, dependências, limites e obrigações.
- **Continuidade:** instruções para retomar o trabalho e contexto necessário.
- **Procedência:** origem, autoridade, relações e evidências associadas à informação.

Essas classes são categorias semânticas, não exigem um arquivo por classe.

## 3. Metadados recomendados

Quando o risco e a complexidade justificarem, informações importantes devem registrar:
- identificador estável;
- tipo ou classe;
- conteúdo ou resumo;
- fonte/origem;
- responsável ou autor conhecido;
- data de criação e atualização;
- estado (proposto, aprovado, vigente, substituído, arquivado, contestado etc.);
- domínio de autoridade;
- relações com outros registros;
- evidências e método de verificação;
- restrições de acesso e uso.

Não invente metadados ausentes. Use “desconhecido” ou deixe explícita a lacuna.

## 4. Estados não equivalentes

- **Declarado:** informado por pessoa ou fonte identificada.
- **Proposto:** sugestão ainda não aprovada.
- **Aprovado:** aceito por autoridade competente.
- **Verificado:** submetido a um método de verificação descrito.
- **Inferido:** conclusão derivada de evidências, não declaração direta.
- **Contestado:** existem objeções ou evidências divergentes.
- **Substituído:** deixou de ser vigente, mas permanece no histórico.
- **Arquivado:** preservado sem expectativa de uso operacional corrente.

Um item pode ser aprovado sem ter sido tecnicamente verificado. Um item verificado pode deixar de ser vigente posteriormente.

## 5. Relações entre informações

Registre relações relevantes, por exemplo:
- deriva de;
- copia/espelha;
- substitui;
- depende de;
- contradiz;
- implementa;
- valida;
- referencia;
- foi decidido por;
- foi verificado em.

Relações devem refletir evidências ou declarações do projeto. Não criar uma cadeia de procedência imaginada.

## 6. Memória operacional versus histórico

A memória operacional deve facilitar a ação presente: estado, decisões vigentes, restrições, pendências e próximos passos.

O histórico preserva como o projeto chegou ao estado atual. Não é necessário reler todo o histórico em cada sessão; a recuperação deve consultar o histórico conforme a pergunta ou risco.

## 7. Retenção e privacidade

O projeto deve definir o que precisa ser preservado, por quanto tempo, onde e com quais permissões. Dados pessoais, segredos, credenciais e informações sensíveis exigem tratamento específico. O repositório oficial ATLAS não deve receber dados privados de projetos individuais.

## 8. Qualidade da memória

Uma memória é útil quando pode ser:
- localizada;
- interpretada;
- atribuída a uma origem;
- relacionada a outras informações;
- avaliada quanto à validade;
- atualizada sem apagar indevidamente o passado;
- transferida para outra pessoa ou IA.

## 9. Limite

Nenhum formato de registro garante por si só que uma IA compreenda corretamente o conteúdo. O modelo precisa ser combinado com recuperação contextual, validação e testes.
