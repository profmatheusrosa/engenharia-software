# Exercícios - Módulo 3: Modelagem e Documentação

## Exercício Prático: Diagramando o "To-Do List Enterprise"

**Objetivo:** Praticar modelagem arquitetural com C4 Model.

**Contexto:**
Seu sistema vai ter um Frontend (React), um Backend (Node.js) e um Banco de Dados (Postgres). Além disso, ele vai enviar emails usando um serviço externo (SendGrid).

**Tarefas:**

1.  **Desenhe o Nível 1 (Contexto):**
    - Identifique o Usuário.
    - Identifique o Sistema de To-Do List (caixa preta).
    - Identifique o Sistema de Email externo.
    - Desenhe as setas de interação (ex: Usuário "usa" Sistema; Sistema "envia email usando" SendGrid).

2.  **Desenhe o Nível 2 (Containers):**
    - Dê "zoom" na caixa do Sistema de To-Do List.
    - Desenhe os containers: Web App (Single Page Application), API Application, Database.
    - Mostre as tecnologias (React, Node, Postgres).
    - Mostre as interações (Web App "faz chamadas JSON/HTTPS" para API; API "lê e escreve" no Database).

**Ferramenta:** Use o [Draw.io](https://app.diagrams.net/) ou tente usar [Mermaid.js](https://mermaid.js.org/) direto no markdown se seu editor suportar.

**Entregável:** Salve os diagramas como imagens (`c4_context.png` e `c4_container.png`) na pasta do seu projeto e adicione ao seu repositório.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
