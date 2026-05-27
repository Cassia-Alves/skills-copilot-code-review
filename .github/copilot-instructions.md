# Copilot Instructions

## Contexto do projeto
- Este repositório contém uma aplicação web com backend em Python (FastAPI) e frontend estático em `src/static`.
- Priorize mudanças pequenas, seguras e fáceis de revisar.

## Regras de implementação
- Preserve a estrutura atual de pastas e padrões de nomenclatura.
- Evite refatorações amplas quando a tarefa for pontual.
- Não altere comportamento existente sem necessidade explícita.
- Mantenha compatibilidade com o código já presente no projeto.

## Backend (Python/FastAPI)
- Siga boas práticas de clareza e legibilidade.
- Prefira funções curtas e com responsabilidade única.
- Trate erros com mensagens objetivas.

## Frontend (HTML/CSS/JS)
- Use HTML semântico e CSS organizado.
- Evite dependências externas desnecessárias.
- Garanta que mudanças visuais não quebrem o layout existente.

## Qualidade e validação
- Quando possível, valide as mudanças localmente antes de concluir.
- Não inclua segredos, tokens, chaves ou credenciais no código.
- Não modifique arquivos não relacionados ao pedido.

## Segurança

- Valide práticas de sanitização de entrada de dados.
- Procure riscos que possam expor dados de usuários.
- Prefira carregar configurações e conteúdos do banco de dados ao invés de valores fixos no código. Se for absolutamente necessário, use variáveis de ambiente ou arquivos de configuração não versionados.

## Qualidade do Código

- Use convenções de nomenclatura consistentes.
- Tente reduzir duplicação de código.
- Prefira manutenibilidade e legibilidade à otimização prematura.
- Se um método for muito utilizado, tente otimizá-lo para performance.
- Prefira tratamento explícito de erros a falhas silenciosas.