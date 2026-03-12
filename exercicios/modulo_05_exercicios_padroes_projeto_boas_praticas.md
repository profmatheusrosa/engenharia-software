# Exercícios - Módulo 5: Padrões de Projeto e Boas Práticas

## Exercício Prático: Refatorando com SOLID

**Objetivo:** Identificar violações de SOLID e corrigir.

**Código Legado (Java/C#/TS):**
```typescript
class Usuario {
  constructor(public nome: string) {}

  salvarNoBanco() {
    // logica de sql...
    console.log("Salvando no banco...");
  }

  enviarEmailBoasVindas() {
    // logica de smtp...
    console.log("Enviando email...");
  }
  
  gerarRelatorioPDF() {
     // logica de pdf...
  }
}
```

**Tarefas:**

1.  **Identifique a Violação:** Qual princípio do SOLID está sendo violado drasticamente aqui? (Dica: O "S").
2.  **Refatore:** Separe as responsabilidades em classes diferentes: `Usuario`, `UsuarioRepository`, `EmailService`, `RelatorioService`.
3.  **Use Injeção:** Crie uma classe `UsuarioService` que orquestre tudo, recebendo as dependências no construtor.

**Entregável:** Código refatorado.

## Exercício Teórico: Identificando Padrões

Dê um exemplo real (do dia a dia ou de uma biblioteca que você usa) para cada um dos seguintes padrões:
1. Singleton
2. Observer (Dica: addEventListener do JS)
3. Builder

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
