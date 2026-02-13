# Exercícios - Módulo 4: Arquitetura Moderna

## Exercício Prático: Refatorando para Clean Architecture

**Objetivo:** Entender a inversão de dependência na prática.

**Cenário:** Você tem um código legado (fictício) onde a Regra de Negócio chama diretamente o Banco de Dados.

*Código "Sujo" (Conceitual):*
```javascript
class PedidoService {
  criarPedido(dados) {
    if (dados.total > 0) {
      const db = new PostgresDatabase(); // Acoplamento direto!
      db.salvar(dados);
    }
  }
}
```

**Tarefas:**

1.  **Crie as Interfaces (Portas):**
    - Defina uma interface (ou classe abstrata) `PedidoRepository` que tenha o método `salvar`.

2.  **Implemente a Regra de Negócio (Use Case):**
    - Reescreva o `PedidoService` para receber `PedidoRepository` no construtor (Injeção de Dependência).
    - O Service não deve saber se é Postgres ou MySQL.

3.  **Implemente o Adaptador:**
    - Crie a classe `PostgresPedidoRepository` que implementa `PedidoRepository`.

**Entregável:** Um arquivo `refatoracao_clean_arch.js` (ou .ts/.java) com as 3 partes acima implementadas.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
