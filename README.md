# ATLAS — Universal Project Memory & Engineering System

**ATLAS** é uma metodologia para estruturar, compreender, documentar, preservar e dar continuidade a projetos com o apoio de diferentes IAs e ferramentas.

Seu propósito é permitir que uma IA compreenda não apenas o conteúdo de um projeto, mas também sua organização, suas fontes de verdade, suas decisões, seu estado atual, suas restrições e as regras para modificá-lo.

> ATLAS é uma metodologia e uma camada de integração. Não é um gerenciador universal que substitui Git, bancos de dados, ferramentas de execução ou os sistemas próprios de cada projeto.

## O que o ATLAS busca permitir

- Analisar projetos de naturezas e complexidades diferentes.
- Projetar uma estrutura documental adequada a cada projeto, sem impor um modelo único.
- Registrar conhecimento, decisões, histórico, estado, responsabilidades e pendências.
- Distinguir fontes oficiais, cópias, espelhos, arquivos históricos e registros operacionais.
- Recuperar contexto com procedência e limites de verificação explícitos.
- Continuar o trabalho entre conversas, plataformas e modelos de IA.
- Evoluir a estrutura documental quando as necessidades do projeto mudarem.
- Preservar integridade, permissões, rastreabilidade e controle humano.

## Arquitetura em três camadas

1. **ATLAS oficial** — metodologia, protocolos, padrões, templates, exemplos e governança.
2. **ATLAS_INDEX individual** — catálogo pessoal dos projetos de um usuário, mantido em seu próprio repositório.
3. **Repositórios de projetos** — espaços independentes que guardam os documentos, dados e artefatos próprios de cada projeto.

O ATLAS oficial não é o local para armazenar os projetos privados de seus usuários.

## Comece por aqui

Se você é uma pessoa, leia este README e depois consulte [ATLAS_ENTRYPOINT.md](ATLAS_ENTRYPOINT.md).

Se você é uma IA assumindo este repositório, **não comece criando arquivos ou alterando a arquitetura**. Leia [ATLAS_ENTRYPOINT.md](ATLAS_ENTRYPOINT.md), siga a sequência do [MANIFEST.md](MANIFEST.md) e respeite os protocolos de governança.

## Estado do projeto

O ATLAS está em construção. Os documentos iniciais estabelecem fundamentos e regras de trabalho; eles não devem ser interpretados como uma metodologia já validada em todos os tipos de projeto.

Decisões, hipóteses, requisitos e capacidades ainda não testadas devem permanecer identificados como tais. A evolução deve ocorrer por lotes revisáveis, com histórico preservado.

## Estrutura inicial

- `core/` — fundamentos e arquitetura conceitual.
- `protocols/` — procedimentos operacionais para IAs.
- `templates/` — modelos reutilizáveis.
- `governance/` — autoridade, permissões, integridade e mudanças.
- `examples/` — casos de referência e testes em projetos reais.
- `reconstruction/` — recuperação, auditoria e validação do próprio ATLAS.

Consulte [MANIFEST.md](MANIFEST.md) para o inventário oficial e a ordem de leitura.

## Princípio essencial

**Encontrar um arquivo não significa compreender sua autoridade, seu significado ou se ele ainda está válido.** O ATLAS deve orientar a IA a reconstruir as relações entre fontes, identificar o que foi efetivamente verificado e só então formar uma compreensão operacional do projeto.
