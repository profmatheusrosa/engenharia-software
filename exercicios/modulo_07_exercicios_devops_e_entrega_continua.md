# Exercícios - Módulo 7: DevOps na Prática

## Exercício Prático: Simulando Git Flow

**Objetivo:** Praticar o fluxo de branches.

**Tarefas:**

1.  **Crie um repositório de testes** (pode ser local).
2.  **Inicie o Git:** `git init`.
3.  **Crie a branch develop:** `git checkout -b develop`.
4.  **Crie uma feature:** `git checkout -b feature/nova-funcionalidade`.
5.  **Faça commits:** Crie um arquivo, edite, commite.
6.  **Merge na develop:** Volte para develop e faça merge da feature (`git merge --no-ff feature/nova-funcionalidade`).
7.  **Simule release:** Crie uma branch `release/v1.0` a partir da develop.
8.  **Merge na main:** Jogue a release na main e tagguei (`git tag v1.0`).

**Entregável:** Um print do comando `git log --graph --oneline --all` mostrando a árvore de commits colorida.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
