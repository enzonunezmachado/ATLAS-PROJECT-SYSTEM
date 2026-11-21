# SOURCE_MAP — Mapa de fontes e autoridade

**Projeto:** [nome e Project ID]  
**Última revisão:** [AAAA-MM-DD]  
**Responsável pela revisão:** [responsável]  
**Estado:** [rascunho/verificado/parcial/desatualizado]

## 1. Objetivo

Este mapa explica onde está a informação, para que cada fonte existe, qual domínio ela governa e como se relaciona com outras fontes. Não presuma que uma única fonte seja autoridade para todos os domínios.

## 2. Inventário de fontes

| ID | Fonte/localização | Origem | Responsável pela manutenção | Finalidade | Domínio | Estado |
|---|---|---|---|---|---|---|
| SRC-001 | [URL/caminho] | [origem primária/derivada/desconhecida] | [responsável] | [finalidade] | [código/requisitos/decisões/operação/histórico etc.] | [vigente/histórico/desconhecido] |

## 3. Autoridade por domínio

| Domínio | Fonte autoritativa | Regra/evidência da autoridade | Responsável | Fontes complementares | Limites/exceções | Situação |
|---|---|---|---|---|---|---|
| [Ex.: documentação técnica vigente] | [SRC-001] | [declaração, política ou evidência] | [responsável] | [SRC-002] | [limites] | [confirmada/ambígua] |

A autoridade pode variar por domínio. Se não houver regra clara, registre como desconhecida ou ambígua; não escolha silenciosamente.

## 4. Relações entre fontes

| Origem | Relação | Destino | Escopo da relação | Evidência |
|---|---|---|---|---|
| [SRC-001] | [espelha/copia/deriva de/substitui/referencia] | [SRC-002] | [arquivos ou conteúdo abrangido] | [commit, declaração, hash etc.] |

Relações possíveis incluem original, espelho sincronizado, cópia de trabalho, exportação, arquivo histórico, memória estratégica, memória operacional e referência externa. Use apenas relações sustentadas por evidência ou declaração identificada.

## 5. Sincronização e integridade

| Par de fontes | Método | Escopo comparado | Data/versões | Resultado | Limitações |
|---|---|---|---|---|---|
| [SRC-001 → SRC-002] | [hash/commit/diff/manual] | [arquivos abrangidos] | [referências] | [resultado] | [o que não comprova] |

Não use “sincronizado” sem registrar o escopo da comparação. Hashes iguais demonstram igualdade dos objetos comparados, não validade semântica nem funcionamento do sistema.

## 6. Divergências e ambiguidades

| ID | Fontes envolvidas | Diferença observada | Domínio afetado | Classificação | Ação |
|---|---|---|---|---|---|
| DIV-001 | [SRC-001/SRC-002] | [descrição] | [domínio] | [histórica/complementar/atraso/conflito/desconhecida] | [investigar/perguntar/nenhuma] |

Não classifique toda diferença como conflito. Preserve conteúdo histórico até que sua função e as permissões estejam claras.

## 7. Permissões e preservação

- **Fontes somente leitura:** [lista]
- **Fontes editáveis:** [lista e por quem]
- **Aprovação obrigatória:** [ações e responsável]
- **Fontes históricas a preservar:** [lista]
- **Operações proibidas sem autorização:** [exclusão, sobrescrita, migração etc.]

## 8. Declaração de verificação

- **Verificado:** [afirmações, método, escopo, data e versão]
- **Não verificado:** [testes ou fontes não cobertos]
- **Inferido:** [interpretações e evidências]
- **Desconhecido:** [lacunas]

## 9. Critério de atualização

Atualize este mapa quando uma fonte mudar de localização, finalidade, autoridade, relação, versão, sincronização ou permissão. Registre a revisão e preserve o histórico relevante.


## 10. Cadeia de procedência e transformação

| Informação/documento | Fonte de origem | Transformação | Destino/derivado | Responsável | Evidência/versão |
|---|---|---|---|---|---|
| [item] | [SRC-001] | [cópia/resumo/exportação/transformação] | [SRC-002] | [responsável] | [commit/data/registro] |

## 11. Responsabilidade e aprovação

- **Responsável pela autoridade do projeto:** [pessoa/equipe]
- **Responsáveis por domínio:** [domínio → responsável]
- **Quem pode propor alterações:** [papéis]
- **Quem pode executar alterações:** [papéis e escopo]
- **Quem aprova alterações sensíveis:** [responsável]
- **Restrições adicionais:** [regras]

## 12. Histórico de revisões do mapa

| Data | Responsável | Escopo revisado | Alterações | Evidências |
|---|---|---|---|---|
| [AAAA-MM-DD] | [responsável] | [escopo] | [resumo] | [links/commits/registros] |

A atualização deste mapa não altera, por si só, a autoridade das fontes. Mudanças de autoridade devem ser aprovadas pelo responsável competente e registradas na fonte ou política que governa o projeto.
