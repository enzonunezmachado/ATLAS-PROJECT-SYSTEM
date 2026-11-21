# Protocolo de descoberta e registro de projetos

**Estado:** procedimento inicial.

## 1. Objetivo

Orientar a IA a identificar se um projeto já existe no ecossistema do usuário antes de inicializar outro, evitando duplicações e preservando a continuidade.

## 2. Descoberta

1. Pergunte ou identifique qual projeto o usuário pretende trabalhar.
2. Localize o ATLAS_INDEX, se fornecido ou acessível.
3. Verifique a procedência e a versão do índice.
4. Consulte os registros relevantes.
5. Compare identidade, objetivo, descrição, identificador e links.
6. Verifique acesso real aos repositórios apontados.
7. Consulte as fontes do projeto seguindo o protocolo de recuperação contextual.

Não suponha acesso a recursos privados. Não trate resultados de busca parcial como prova de inexistência.

## 3. Classificação do resultado

- **Correspondência confirmada:** identificador ou evidências suficientes demonstram que é o projeto desejado.
- **Possível correspondência:** há semelhanças, mas identidade não está confirmada.
- **Projeto não localizado no índice consultado:** a busca no índice disponível não encontrou registro.
- **Índice indisponível:** não foi possível consultar o catálogo.
- **Acesso insuficiente:** o registro existe, mas os recursos não puderam ser inspecionados.

A frase “projeto não existe” só pode ser usada quando o escopo da busca e suas limitações sustentarem essa conclusão; normalmente prefira “não localizado nas fontes consultadas”.

## 4. Decisão de inicialização

Se houver correspondência confirmada, continuar o projeto existente. Se houver possível correspondência, perguntar antes de criar outro. Se não houver registro e o usuário desejar iniciar um novo projeto, apresentar a estrutura proposta e obter autorização antes de criar recursos.

## 5. Registro

Ao criar projeto novo:
- definir Project ID estável;
- registrar nome e descrição;
- definir localização e fontes;
- identificar proprietário e permissões;
- estabelecer estado inicial;
- registrar versão ATLAS adotada;
- documentar relações com projetos anteriores, se existirem;
- atualizar o ATLAS_INDEX com autorização.

## 6. Renomeação, arquivamento e fusão

Renomear não significa criar novo projeto. Arquivar não significa apagar. Fundir projetos pode destruir distinções importantes e exige análise, mapeamento de histórico e autorização explícita.

## 7. Limite operacional

A IA só pode executar ações para as quais tenha ferramentas e permissões reais. Quando não puder criar um repositório, acessar um índice ou alterar um arquivo, deve apresentar a limitação sem simular a ação.
