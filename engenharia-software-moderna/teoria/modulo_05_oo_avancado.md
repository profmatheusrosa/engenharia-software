# Módulo 5: Projeto Orientado a Objetos Avançado

## Sumário
- [5.1 Princípios SOLID](#51-princípios-solid)
- [5.2 GRASP](#52-grasp)
- [5.3 Padrões de Projeto Modernos](#53-padrões-de-projeto-modernos)
- [5.4 Repository Pattern](#54-repository-pattern)
- [5.5 Anti-patterns](#55-anti-patterns)
- [Referências](#referências)

## Introdução
Saber Orientação a Objetos (Herança, Polimorfismo) é o básico. Para criar sistemas robustos, precisamos de diretrizes. SOLID e Design Patterns são o vocabulário comum dos engenheiros seniores.

## 5.1 Princípios SOLID

Cinco princípios que facilitam a manutenção e extensão do sofware.

1.  **S - The Single Responsibility Principle (SRP):** Uma classe deve ter apenas um motivo para mudar. (Ex: A classe `Pedido` não deve saber enviar email; isso é responsabilidade de `EmailService`).
2.  **O - The Open/Closed Principle (OCP):** Aberto para extensão, fechado para modificação. (Ex: Use herança ou interfaces para adicionar comportamentos sem mudar o código existente).
3.  **L - The Liskov Substitution Principle (LSP):** Subclasses devem ser substituíveis por suas superclasses sem quebrar o sistema. "Se parece um pato e grasna como um pato, mas precisa de baterias, você tem a abstração errada".
4.  **I - The Interface Segregation Principle (ISP):** Muitas interfaces específicas são melhores que uma interface única geral.
5.  **D - The Dependency Inversion Principle (DIP):** Dependa de abstrações, não de implementações concretas (visto no Módulo 4).

[IMAGEM_11_PRINCIPIOS_SOLID]

## 5.2 GRASP

General Responsibility Assignment Software Patterns. Princípios que ajudam a atribuir responsabilidades às classes e objetos.
- **Controller:** Quem deve tratar um evento de sistema? (Um Controlador, não a View).
- **Creator:** Quem deve criar uma instância de A? (Quem contém A, ou usa A).
- **High Cohesion:** Mantenha classes focadas.
- **Low Coupling:** Mantenha classes independentes.

## 5.3 Padrões de Projeto Modernos (GoF)

Não decore todos os 23. Foque nos essenciais:

- **Factory:** Criação de objetos sem expor a lógica de criação.
- **Builder:** Construção de objetos complexos passo a passo.
- **Adapter:** Faz classes incompatíveis trabalharem juntas (Ex: Adaptador de voltagem).
- **Facade:** Interface simplificada para um subsistema complexo.
- **Observer:** Assinatura de eventos (Ex: Quando o estado muda, notifica todos os ouvintes - base do React/Vue).

[IMAGEM_12_DESIGN_PATTERNS_ICONS]

**Exercício 5.3:** Qual padrão é ideal para converter a interface de uma classe em outra interface que o cliente espera?

- a) Factory
- b) Adapter
- c) Singleton
- d) Observer

<details>
<summary>Ver Resposta</summary>

**Resposta:** b) Adapter

**Explicação:** Como o nome diz, ele adapta interfaces incompatíveis.
</details>

## 5.4 Repository Pattern

Isola a lógica de acesso a dados da lógica de domínio. O Repositório simula uma coleção de objetos em memória.
- Métodos comuns: `add()`, `remove()`, `getById()`, `findByCriteria()`.
- **Não** deve conter regras de negócio (ex: "se saldo < 0"). Isso fica na Entidade ou Service.

## 5.5 Anti-patterns

O que NÃO fazer:
- **God Object (Classe Deus):** Uma classe que sabe tudo e faz tudo (ex: tem 2000 linhas).
- **Spaghetti Code:** Fluxo de controle confuso, muitos GOTOs ou exceptions usadas como controle de fluxo.
- **Golden Hammer:** "Para quem tem martelo, tudo é prego". Usar a mesma tecnologia/padrão para tudo.

## Referências

[1] GAMMA, Erich et al. Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley, 1994.

[2] LARMAN, Craig. Applying UML and Patterns. Prentice Hall, 2004.

---
[Próximo módulo →](../teoria/modulo_06_implementacao_e_qualidade.md)

[Voltar aos Links Rápidos](../README.md#links-rapidos)
