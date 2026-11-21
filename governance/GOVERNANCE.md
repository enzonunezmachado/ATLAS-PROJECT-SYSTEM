# Governança inicial do ATLAS

## 1. Escopo

Estas regras se aplicam ao repositório oficial ATLAS. Projetos individuais devem definir sua própria governança, podendo adotar e adaptar estes princípios.

## 2. Princípios de contribuição

- Mudanças devem ter objetivo e justificativa claros.
- Documentos precisam manter responsabilidades distintas e referências coerentes.
- Mudanças estruturais devem atualizar o MANIFEST.
- Não apresentar hipóteses como capacidades comprovadas.
- Preservar histórico e rastreabilidade.
- Não introduzir dados privados de projetos ou usuários no repositório público.
- Preferir lotes pequenos, revisáveis e reversíveis.

## 3. Branches e integração

A branch `main` representa a versão integrada do ATLAS. Mudanças devem ser desenvolvidas em branches separadas e propostas por pull request sempre que possível.

A aprovação humana é necessária antes de integrar mudanças relevantes. A existência de uma branch ou pull request não garante que as configurações de proteção do GitHub estejam habilitadas; isso deve ser verificado nas configurações do repositório.

## 4. Níveis de mudança

### Editorial
Correções de linguagem, formatação e links sem alteração de significado.

### Evolutiva
Novos procedimentos, templates, exemplos ou esclarecimentos compatíveis com os princípios vigentes.

### Estrutural
Mudança na arquitetura, hierarquia, autoridade, fluxo de recuperação ou governança. Exige justificativa, análise de impacto e revisão explícita.

### Sensível
Mudança que possa afetar segurança, privacidade, permissões, integridade, histórico ou autoridade de fontes. Exige autorização humana explícita e plano de reversão quando possível.

## 5. Integridade documental

Antes de concluir um lote:
- verificar links internos;
- atualizar o MANIFEST;
- revisar consistência terminológica;
- conferir se as instruções não se contradizem;
- registrar limitações;
- preservar documentos históricos;
- confirmar quais arquivos foram realmente alterados.

## 6. Segurança e acesso

O repositório oficial pode ser público para leitura, mas a escrita deve permanecer restrita a colaboradores autorizados. Não incluir segredos, tokens, credenciais, dados pessoais sensíveis ou conteúdo privado de projetos.

Branch protection, revisão obrigatória, regras de aprovação, backups e releases devem ser configurados e verificados nas opções do GitHub. A documentação desta intenção não comprova que a configuração técnica já foi aplicada.

## 7. Versionamento

Mudanças relevantes devem ser registradas no CHANGELOG. Releases devem representar conjuntos revisados e coerentes de alterações. Não declarar uma versão estável antes de critérios de validação definidos.

## 8. Resolução de conflitos

Quando documentos divergirem:
1. identifique o domínio;
2. consulte a autoridade definida no MANIFEST e nos documentos especializados;
3. determine se a diferença é temporal, complementar ou conflitante;
4. não escolha silenciosamente uma interpretação;
5. registre a decisão e atualize referências relacionadas.

## 9. Transparência operacional

Toda entrega deve distinguir:
- o que foi proposto;
- o que foi alterado;
- o que foi revisado;
- o que foi testado;
- o que não foi possível verificar;
- o que depende de aprovação humana.
