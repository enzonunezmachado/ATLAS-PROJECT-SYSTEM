# Templates operacionais ATLAS

**Estado:** conjunto inicial de modelos reutilizáveis, sujeito a testes e evolução.

## Princípios de uso

Os templates reduzem o trabalho de inicialização, mas não definem uma estrutura obrigatória para todos os projetos. Selecione apenas os modelos que resolvem uma necessidade real e adapte os campos ao contexto, risco e complexidade.

- Não preencha campos com suposições. Use `Desconhecido`, `Não aplicável` ou deixe uma pendência explícita.
- Não transforme toda categoria em um arquivo separado sem necessidade.
- Preserve os identificadores e referências já existentes ao atualizar registros.
- Não inclua senhas, tokens, chaves privadas ou dados sensíveis desnecessários.
- Registre o que foi verificado e o que apenas foi declarado.
- A cópia de um template para um projeto não transfere automaticamente a autoridade do ATLAS oficial para aquele arquivo.

## Modelos disponíveis

| Modelo | Finalidade | Uso típico |
|---|---|---|
| [ATLAS_INDEX_TEMPLATE.md](ATLAS_INDEX_TEMPLATE.md) | Inicializar o repositório índice pessoal | Usuário ou organização com múltiplos projetos |
| [PROJECT_REGISTRY_TEMPLATE.md](PROJECT_REGISTRY_TEMPLATE.md) | Catálogo de projetos | Parte central do ATLAS_INDEX |
| [PROJECT_RECORD_TEMPLATE.md](PROJECT_RECORD_TEMPLATE.md) | Registro detalhado de um projeto | Quando o catálogo resumido não basta |
| [SOURCE_MAP_TEMPLATE.md](SOURCE_MAP_TEMPLATE.md) | Mapa de fontes, autoridade e relações | Projetos com múltiplos repositórios, documentos ou sistemas |
| [SESSION_HANDOFF_TEMPLATE.md](SESSION_HANDOFF_TEMPLATE.md) | Transferência de contexto entre sessões/IAs | Encerramento e retomada de trabalho |

## Fluxo recomendado de adoção

1. Crie um repositório para o índice pessoal apenas quando houver necessidade e autorização; escolha livremente seu nome no GitHub.
2. Use o template ATLAS_INDEX como estrutura interna, sem precisar nomear o repositório `ATLAS_INDEX`.
3. Comece pelo template do índice e pelo catálogo.
4. Registre cada projeto com identificador estável.
5. Para projetos com múltiplas fontes, construa um mapa de fontes antes de fazer mudanças relevantes.
6. Ao encerrar uma sessão importante, gere um handoff e mantenha-o coerente com o estado real do projeto.
7. Revise os registros quando houver mudanças relevantes.

## Compatibilidade e limites

Os modelos são Markdown simples para facilitar leitura, versionamento e uso por diferentes ferramentas. Eles não criam acesso a repositórios privados, não sincronizam arquivos automaticamente e não substituem políticas de segurança, backups ou testes.

Consulte também:
- [Especificação do ATLAS_INDEX](../core/ATLAS_INDEX_SPECIFICATION.md)
- [Modelo de conhecimento e memória](../core/KNOWLEDGE_AND_MEMORY_MODEL.md)
- [Recuperação e verificação contextual](../protocols/CONTEXT_RECOVERY.md)
- [Continuidade entre sessões e IAs](../protocols/SESSION_CONTINUITY.md)
