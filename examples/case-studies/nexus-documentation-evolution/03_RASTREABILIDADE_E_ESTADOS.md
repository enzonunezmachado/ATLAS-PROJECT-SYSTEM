# 3. Rastreabilidade e estados no caso NEXUS

## Identificadores usados

O registro pós-teste utiliza prefixos para distinguir a natureza dos itens:

| Prefixo | Uso | Exemplo |
|---|---|---|
| BUG | Defeito funcional observado | Perda de estado ao girar o dispositivo |
| COR | Correção solicitada, inclusive visual | Remover símbolo N verde redundante |
| OBS | Comportamento positivo ou fato de uso | Alertas vermelho/amarelo elogiados |
| IDEA | Oportunidade de evolução do produto | Visão inicial da Agenda configurável |
| FUT | Possibilidade de longo prazo | Assistente opcional de IA e WhatsApp |

Os identificadores devem ser estáveis. O estado muda ao longo do ciclo, mas a origem e o histórico não devem ser apagados.

## Estados adotados no registro

- Observado: há relato ou evidência de comportamento.
- Solicitado: o usuário pediu uma correção ou mudança.
- Em análise: investigação técnica ou de produto pendente.
- Proposto: existe uma solução descrita, ainda sem aprovação.
- Aprovado: decisão explícita para seguir.
- Em implementação: execução autorizada.
- Implementado: alteração confirmada no artefato correto.
- Validado: teste adequado confirmou o resultado.
- Pausado / descartado: direção interrompida, mantendo histórico.

Este conjunto é um vocabulário contextual do caso NEXUS, não um padrão obrigatório do ATLAS.

## Cadeia de rastreabilidade desejada

Uma correção deve permitir percorrer:

**observação → item identificado → investigação → proposta → aprovação → implementação → teste → validação**

A cadeia não precisa ser linear. Uma hipótese pode ser rejeitada, uma proposta pode ser substituída e uma correção pode exigir reabertura. Cada transição deve ter evidência apropriada.

## Exemplo: defeito de rotação

- BUG-001 foi criado a partir do relato de que girar o dispositivo retorna à Home e perde conteúdo de formulários/edição.
- A causa técnica ainda não foi identificada.
- O próximo passo é analisar o estado de navegação e de edição em diferentes telas.
- Não pode ser marcado como implementado ou validado antes de mudança confirmada e teste de rotação.

## Exemplo: identidade visual

- COR-001 registra o pedido de remover o N verde redundante antes do nome NEXUS.
- O ícone atual com N branco sobre fundo preto deve permanecer.
- A análise deve localizar todas as ocorrências e respeitar o escopo.
- O pedido não autoriza criar outra marca nem alterar o ícone do aplicativo.

## Lições de proveniência

O registro precisa distinguir:
- relato do usuário;
- inspeção direta de repositório;
- relatório fornecido por outra ferramenta;
- inferência;
- proposta do assistente;
- mudança realmente executada;
- teste efetivamente realizado.

Um relatório de validação estática recebido não é equivalente a um teste de restauração no aparelho. Um arquivo presente no GitHub não prova que o aplicativo o restaura corretamente.
