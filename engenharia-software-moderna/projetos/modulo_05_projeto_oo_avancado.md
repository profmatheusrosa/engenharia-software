# Projeto - Módulo 5: Aplicando Padrões

## Título do Projeto: Implementando Repositórios e Factories

## Descrição
Vamos implementar a camada de persistência do "To-Do List Enterprise" usando padrões corretos.

## Requisitos e Etapas

1.  **Repository Pattern:**
    - Crie uma implementação em memória de `TaskRepository`.
    - Deve ter métodos: `save(task)`, `findById(id)`, `findAll()`, `delete(id)`.
    - Use um Map ou Array para simular o banco.

2.  **Factory Method (Opcional):**
    - Crie uma `TaskFactory` que cria instâncias de Task já validadas. Ex: `TaskFactory.create(title, output_format)`.

3.  **Teste Manual:**
    - Crie um script `main.js` (ou `Program.cs`) que:
      1. Instancia o repositório.
      2. Cria uma task usando a factory.
      3. Salva a task no repositório.
      4. Busca a task e imprime no console.

## Entrega
Link para o código implementação no seu repositório.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
