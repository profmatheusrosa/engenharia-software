# Projeto - Módulo 4: Arquitetura Hexagonal

## Título do Projeto: Estruturando o Monólito Modular

## Descrição
Vamos reestruturar as pastas do nosso projeto "To-Do List Enterprise" para seguir os princípios da Arquitetura Hexagonal/Clean.

## Requisitos e Etapas

1.  **Estrutura de Pastas:**
    - Crie a seguinte estrutura dentro da pasta `src` do seu projeto (simulação):
      ```
      src/
      ├── core/ (ou domain)
      │   ├── entities/ (Task, User)
      │   ├── repositories/ (Interfaces: ITaskRepository)
      │   └── usecases/ (CreateTask, CompleteTask - regras de negócio pura)
      ├── infra/
      │   ├── database/ (Implementação: PostgresTaskRepository)
      │   └── api/ (Controllers: TaskController)
      └── main/ (Configuração e Injeção de Dependência)
      ```

2.  **Identificando Bounded Contexts:**
    - Se seu projeto cresceu, talvez você tenha contextos diferentes. Crie um arquivo `CONTEXTOS.md`.
    - Descreva pelo menos 2 contextos possíveis para um sistema de gestão de tarefas avançado (ex: Contexto de Execução de Tarefas vs Contexto de Gamificação/Recompensas).

3.  **Atualização do Repositório:**
    - Comite as pastas vazias (use um arquivo `.gitkeep`) ou com arquivos de exemplo para demonstrar a estrutura.

## Entrega
Link do repositório com a nova estrutura de pastas organizada.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
