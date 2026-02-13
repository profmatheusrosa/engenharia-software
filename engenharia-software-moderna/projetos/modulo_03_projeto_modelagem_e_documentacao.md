# Projeto - Módulo 3: Documentação Viva

## Título do Projeto: Architecture Decision Records (ADR)

## Descrição
Documentação arquitetural não é só diagrama. É também sobre registrar **decisões importantes**. Por que escolhemos Node.js e não Java? Por que Postgres e não MongoDB? O ADR (Architecture Decision Record) é o padrão para isso.

## Requisitos e Etapas

1.  **Pesquisa sobre ADR:**
    - Leia sobre o formato de ADR (template básico: Título, Status, Contexto, Decisão, Consequências).

2.  **Crie seu primeiro ADR:**
    - No seu repositório, crie uma pasta `docs/adr`.
    - Crie o arquivo `001-escolha-da-linguagem-backend.md`.
    - Simule a decisão da tecnologia do backend do "To-Do List Enterprise".

    *Exemplo de conteúdo:*
    - **Contexto:** Precisamos de uma tecnologia que permita desenvolvimento rápido e o time já conhece JavaScript.
    - **Decisão:** Usaremos Node.js com Express.
    - **Consequências:** Reaproveitamento de código JS no Front e Back; facilidade de contratação; risco de performance em tarefas pesadas de CPU (mitigável).

3.  **Diagrama C4 no README:**
    - Integre a imagem do diagrama C4 (Nível 2) que você fez nos exercícios diretamente no `README.md` principal do seu repositório, na seção de "Arquitetura".

## Entrega
Link do repositório contendo a pasta `docs/adr` e o README atualizado com o diagrama.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
