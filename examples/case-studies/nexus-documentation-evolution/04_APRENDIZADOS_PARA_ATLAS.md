# 4. Aprendizados e questões para evolução do ATLAS

**Estado:** observações para pesquisa metodológica; não são mudanças normativas aprovadas.

## Aprendizados observados

### 1. A arquitetura documental deve responder a perguntas de recuperação

Não basta guardar tudo sobre um projeto. A organização precisa permitir recuperar rapidamente problemas, decisões, propostas, resultados e ideias sem misturar categorias.

### 2. Um experimento precisa de um espaço próprio, mas não de um catálogo paralelo

O experimento mantém perfis, prompt, acompanhamento e resultados. Ideias continuam no catálogo estratégico central do projeto. A pasta do experimento referencia o catálogo quando necessário.

### 3. Problemas, ideias e visão futura não são a mesma coisa

Um defeito funcional exige investigação e validação. Uma ideia de produto exige análise e decisão. Uma visão futura pode ser preservada sem entrar no próximo planejamento. Misturá-los prejudica priorização e continuidade.

### 4. Estado e evidência precisam acompanhar cada item

O uso de IDs e estados reduz a chance de uma conversa futura esquecer uma solicitação ou declará-la resolvida sem evidência. Entretanto, estados demais podem criar custo operacional. O conjunto deve ser proporcional ao projeto.

### 5. O histórico não deve ser reescrito para parecer linear

O usuário pode mudar de preferência. Uma ideia pode evoluir. O registro anterior precisa continuar compreensível como contexto histórico, com a direção atual claramente identificada.

### 6. Relatórios de ferramentas precisam manter sua origem

O relatório do Google AI Studio foi registrado como relato recebido. A exploração de Gabriel foi registrada como experiência relatada pelo responsável. A inspeção dos caminhos GitHub foi registrada separadamente. Esses níveis de evidência não devem ser confundidos.

### 7. A estrutura deve separar conteúdo do projeto e materiais de avaliação do ATLAS

O caso detalhado pertence ao NEXUS. O ATLAS recebe uma síntese metodológica. Critérios internos de avaliação de uma futura prova do ATLAS não devem ser expostos automaticamente às IAs que utilizam a metodologia.

## Questões para pesquisa no ATLAS

1. O modelo de memória deve sugerir classes de registro como observação, defeito, ideia, decisão, execução e validação, sem impor arquivos fixos?
2. Como uma IA decide quando criar uma nova pasta ou documento, reutilizar um existente ou apenas adicionar uma seção?
3. Como evitar duplicação entre um catálogo central e registros locais de experimentos?
4. Qual é o conjunto mínimo de estados que permite continuidade sem burocracia?
5. Como manter ligações entre observação, item de trabalho, decisão, commit e teste?
6. Como uma IA deve reconciliar mudanças de direção sem apagar o histórico?
7. Como distinguir relato humano, resultado de ferramenta, inspeção direta e validação independente?
8. Como manter exemplos públicos sem vazar dados privados de projetos?
9. Como avaliar a utilidade dessa estrutura em projetos não relacionados a software?

## Limite metodológico

Este caso demonstra uma necessidade prática e uma solução documental contextual. Não comprova que a estrutura escolhida seja ótima, nem que o ATLAS já tenha mecanismos suficientes para recomendar ou manter essa organização automaticamente.

Qualquer incorporação ao núcleo do ATLAS deve depender de análise, comparação com documentos existentes e testes em projetos diferentes.
