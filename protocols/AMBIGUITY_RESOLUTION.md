# Protocolo de resolução de ambiguidades e divergências

**Estado:** protocolo inicial para validação.

## 1. Objetivo

Orientar a IA quando encontrar fontes que parecem contraditórias, duplicadas, desatualizadas, sem autoridade definida ou inacessíveis. O objetivo é impedir decisões silenciosas que possam causar perda de contexto, alteração indevida ou continuidade baseada em informação errada.

## 2. Gatilhos

Inicie este protocolo quando:
- duas ou mais fontes parecem oficiais para o mesmo domínio;
- um documento contradiz outro;
- uma cópia ou espelho diverge da origem;
- há arquivos com nomes ou conteúdos semelhantes, mas finalidades diferentes;
- a fonte de autoridade não está declarada;
- um registro histórico parece contradizer uma instrução atual;
- uma fonte necessária está inacessível;
- permissões de leitura, edição ou aprovação não estão claras.

## 3. Procedimento

### Etapa 1 — Interromper a decisão dependente

Não escolha uma interpretação apenas para avançar. Continue apenas tarefas independentes da ambiguidade, se isso não criar risco.

### Etapa 2 — Descrever o conflito observado

Registre:
- fontes e localizações;
- domínio afetado;
- trechos, versões ou estados envolvidos;
- diferença concreta;
- data e método de observação;
- impacto potencial da escolha.

Separe o que foi observado do que foi inferido.

### Etapa 3 — Classificar provisoriamente

Use uma destas categorias:
- **Temporal:** fontes representam momentos diferentes.
- **Complementar:** fontes tratam de aspectos diferentes e podem coexistir.
- **Derivação:** uma fonte resume, transforma ou deriva de outra.
- **Espelho divergente:** cópia não corresponde à origem no escopo esperado.
- **Autoridade concorrente:** mais de uma fonte reivindica autoridade no mesmo domínio.
- **Histórico versus vigente:** registro antigo está sendo comparado com instrução atual.
- **Acesso insuficiente:** não há dados para concluir.
- **Desconhecida:** evidência insuficiente para classificar.

A classificação é provisória até que exista evidência suficiente.

### Etapa 4 — Consultar autoridade e procedência

Consulte o manifesto, o mapa de fontes, as declarações do projeto, os responsáveis e o modelo de autoridade por domínio. Verifique origem, cadeia de derivação, estado, versão, sincronização e permissões.

Não use apenas nomes de arquivos, datas ou semelhança de conteúdo como critério de autoridade.

### Etapa 5 — Avaliar risco e reversibilidade

Considere se a ação pode:
- apagar ou sobrescrever conteúdo;
- alterar a fonte autoritativa;
- propagar informação incorreta para espelhos;
- mudar decisões ou requisitos;
- expor dados privados;
- tornar a recuperação futura mais difícil.

Quanto maior o impacto ou menor a reversibilidade, maior a exigência de confirmação humana.

### Etapa 6 — Resolver ou escalar

Se uma regra explícita e evidências suficientes resolverem a divergência, registre a justificativa e as fontes usadas. Caso contrário, formule uma pergunta específica ao responsável humano e aguarde resposta antes da ação dependente.

Não transforme a interpretação provisória em regra permanente sem autorização apropriada.

### Etapa 7 — Registrar a decisão

Documente:
- ambiguidade original;
- fontes analisadas;
- classificação final ou estado ainda aberto;
- decisão e justificativa;
- responsável e aprovação;
- documentos afetados;
- ações executadas;
- itens não verificados.

Atualize o mapa de fontes e os registros relacionados quando autorizado.

## 4. Regras de preservação

- Não excluir fontes por parecerem duplicadas.
- Não sobrescrever a origem com conteúdo de um espelho sem autorização.
- Não fundir documentos históricos e vigentes.
- Não corrigir divergências por edição unilateral quando a autoridade for incerta.
- Preservar evidências necessárias para auditoria e reversão.
- Não declarar resolução se apenas uma hipótese plausível foi escolhida.

## 5. Modelo curto de comunicação

**Ambiguidade:** [descrição objetiva]  
**Fontes:** [identificadores e versões]  
**Domínio:** [domínio afetado]  
**O que foi verificado:** [método e escopo]  
**O que permanece incerto:** [lacunas]  
**Risco de agir agora:** [impacto]  
**Decisão necessária:** [pergunta específica]  
**Ação suspensa:** [operação dependente]

## 6. Critérios de sucesso

O caso está adequadamente tratado quando a IA:
- identifica e descreve a divergência sem exagerá-la;
- distingue observação, inferência e desconhecido;
- consulta a autoridade do domínio e a procedência;
- preserva as fontes enquanto a decisão não está clara;
- solicita aprovação quando necessário;
- registra decisão, evidências e limitações.

## 7. Limites

Este protocolo não garante que a IA detecte toda contradição nem substitui responsáveis pelo projeto. Sua eficácia deve ser testada com cenários reais e casos adversariais.
