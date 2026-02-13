# Exercícios - Módulo 2: Requisitos Modernos

## Exercício Prático: Especificando o "To-Do List Enterprise"

**Objetivo:** Praticar a escrita de User Stories e Critérios de Aceitação.

**Contexto:** Continuando o projeto do Módulo 1.

**Tarefas:**

1. **User Story Refining:**
   Pegue uma das User Stories que você criou no Módulo 1 (ex: "Adicionar tarefa") e refine-a aplicando o INVEST. Se necessário, quebre-a em duas.

2. **Escrevendo Gherkin:**
   Para a história refinada acima, escreva pelo menos 2 cenários de aceitação usando Gherkin (Given-When-Then).
   
   *Exemplo de estrutura:*
   ```herkin
   Funcionalidade: Adicionar Tarefa
   
   Cenário: Adicionar tarefa com sucesso
     Dado que estou na tela inicial
     E preencho o campo "Nova Tarefa" com "Comprar leite"
     Quando clico em "Adicionar"
     Então a tarefa "Comprar leite" deve aparecer na lista
   ```

3. **Cenário de Erro:**
   Escreva um cenário cobrindo um caso de erro ou exceção (ex: tentar adicionar tarefa vazia).

**Entregável:** Um arquivo markdown `especificacao_todo_list.md` no seu repositório contendo as histórias e os cenários.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
