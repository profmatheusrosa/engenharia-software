# Exercícios - Módulo 6: Testes e TDD

## Exercício Prático: TDD na Prática

**Objetivo:** Implementar uma calculadora de descontos simples usando TDD.

**Ferramenta:** Use Jest (Node.js) ou qualquer framework de testes unitários.

**Ciclo 1:**
1. Escreva um teste: `deve aplicar 10% de desconto para compras acima de 100 reais`.
2. Rode o teste (deve falhar).
3. Implemente a função `calcularDesconto`.
4. Rode o teste (deve passar).

**Ciclo 2:**
1. Escreva um teste: `não deve aplicar desconto para compras abaixo de 100 reais`.
2. Rode o teste.
3. Ajuste a função.
4. Rode o teste.

**Ciclo 3:**
1. Escreva um teste: `deve aplicar 20% para compras acima de 500 reais`.
2. Rode o teste.
3. Ajuste a função.
4. Refatore o código (elimine `if/else` aninhados se possível).

**Entregável:** Arquivo de teste (`desconto.test.js`) e arquivo de implementação (`desconto.js`).

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
