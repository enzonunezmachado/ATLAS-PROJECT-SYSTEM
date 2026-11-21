# Especificação inicial do ATLAS_INDEX

**Estado:** especificação conceitual acompanhada por templates iniciais sujeitos a validação.

## 1. Finalidade

O ATLAS_INDEX é a função de indexação pessoal: um catálogo e ponto de descoberta dos projetos de uma pessoa ou organização. A expressão identifica o papel lógico do índice, não um nome obrigatório para o repositório GitHub.

A pessoa ou organização escolhe livremente o nome do repositório que hospeda esse índice — por exemplo, `MEUS-PROJETOS`, `FOLLOW-INDEX` ou outro nome disponível. O repositório continua sendo um recurso individual, com URL própria. Não é necessário nem recomendado exigir que todos criem um repositório chamado `ATLAS_INDEX`.

O índice conecta o usuário ao ATLAS oficial e aos repositórios individuais dos projetos. Não substitui a documentação de cada projeto nem armazena automaticamente todo o seu conteúdo.

## 2. Separação de propriedade

- O ATLAS oficial define a metodologia.
- O ATLAS_INDEX pertence ao usuário ou organização.
- Cada repositório de projeto pertence ao respectivo projeto e segue suas regras.

O ATLAS oficial não deve exigir que os índices pessoais sejam públicos. O índice pode ser privado, especialmente quando revela projetos confidenciais.

## 3. Nome e identidade do repositório

- `ATLAS_INDEX` é o nome conceitual da função/estrutura de indexação, não um identificador global nem um nome obrigatório de repositório.
- O nome do repositório é escolhido pelo proprietário e deve ser único dentro de sua conta ou organização GitHub.
- O índice deve manter um identificador estável próprio, quando necessário, independente do nome e da URL do repositório.
- Renomear o repositório não deve alterar a identidade lógica do índice nem os IDs dos projetos catalogados.
- Os arquivos e campos internos podem continuar usando os termos `ATLAS_INDEX` para indicar compatibilidade com a metodologia.

## 4. Responsabilidades do índice

- catalogar projetos;
- manter identificadores estáveis;
- registrar nome, descrição, categoria e estado;
- apontar para repositórios e espaços relevantes;
- registrar a versão da metodologia ATLAS adotada;
- indicar a data da última revisão conhecida;
- facilitar descoberta e seleção do projeto a recuperar;
- registrar projetos arquivados sem confundi-los com projetos ativos.

## 5. Registro de projeto

Um registro pode conter, conforme necessidade:
- Project ID;
- nome;
- descrição curta;
- categoria/natureza;
- estado;
- localização principal;
- outras fontes relacionadas;
- versão ATLAS;
- responsável;
- sensibilidade/classificação de acesso;
- última revisão;
- observações de descoberta.

Não guardar tokens, senhas, chaves privadas ou credenciais no índice.

## 6. Descoberta e acesso

O índice só permite descobrir recursos que estejam listados e acessíveis. A IA não deve presumir que consegue abrir repositórios privados apenas porque o URL está registrado.

Se o usuário não fornecer o índice ou a conexão não permitir acesso, a IA deve explicar a limitação e solicitar o caminho ou autorização apropriada.

## 7. Identidade e duplicidade

Cada projeto deve ter um identificador estável, independente de renomeações. Antes de registrar um novo projeto, comparar nome, objetivo, links e contexto com registros existentes. Semelhança não prova identidade; em caso de dúvida, perguntar antes de criar duplicata ou fundir registros.

## 8. Atualização

Alterações no projeto principal podem exigir atualização do índice, mas não se deve declarar que o índice está sincronizado sem verificar as fontes. Registrar data e escopo da última revisão.

## 9. Recuperação

Fluxo esperado:
1. localizar o índice;
2. verificar sua origem e versão;
3. consultar o catálogo;
4. identificar o projeto solicitado;
5. verificar links e acesso;
6. seguir o protocolo de recuperação contextual no repositório do projeto;
7. atualizar o índice apenas com autorização e evidência adequadas.

## 10. Templates iniciais

- [Template do índice pessoal](../templates/ATLAS_INDEX_TEMPLATE.md)
- [Template do catálogo de projetos](../templates/PROJECT_REGISTRY_TEMPLATE.md)
- [Template de registro detalhado de projeto](../templates/PROJECT_RECORD_TEMPLATE.md)

Os modelos são opcionais e devem ser adaptados. O índice mínimo pode começar apenas com a identificação do proprietário e o catálogo, acrescentando registros detalhados quando necessário.

## 11. Privacidade e segurança

O usuário decide a visibilidade do índice. A escolha entre público e privado deve considerar se nomes, descrições e links revelam informações confidenciais. Projetos privados não devem ser expostos por metadados do índice.

## 12. Evolução

O formato inicial deve ser simples e legível por humanos e IAs. Automatizações, bancos de dados ou integrações podem ser acrescentados quando houver necessidade comprovada, sem tornar esses serviços pré-requisitos para o funcionamento básico.
