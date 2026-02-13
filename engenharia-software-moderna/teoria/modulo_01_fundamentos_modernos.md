# Módulo 1: Fundamentos Modernos de Engenharia de Software

## Sumário
- [1.1 O que é Engenharia de Software](#11-o-que-é-engenharia-de-software)
- [1.2 Qualidade de Software](#12-qualidade-de-software)
- [1.3 Processos de Desenvolvimento](#13-processos-de-desenvolvimento)
- [1.4 Métodos Ágeis](#14-métodos-ágeis)
- [1.5 Cultura Ágil e Produto](#15-cultura-ágil-e-produto)
- [1.6 Ferramentas de Mercado](#16-ferramentas-de-mercado)
- [Referências](#referências)

## Introdução
Este módulo estabelece as bases da Engenharia de Software moderna, diferenciando a prática de "apenas programar" de "projetar software". Exploraremos como a indústria evoluiu de processos rígidos para abordagens ágeis focadas em entrega de valor e qualidade.

## 1.1 O que é Engenharia de Software

A Engenharia de Software é a aplicação de uma abordagem sistemática, disciplinada e quantificável ao desenvolvimento, operação e manutenção de software[1]. Diferente da programação pura, que foca na escrita de código, a engenharia de software preocupa-se com todo o ciclo de vida do produto, desde a concepção até a descontinuação.

![Ciclo de Vida do Software](../imagens/ciclo_vida_software.png)

### Programar vs. Projetar Software
- **Programar:** Foco na resolução imediata de um problema lógico específico. Muitas vezes individual.
- **Projetar Software:** Foco na estrutura, manutenibilidade, escalabilidade e colaboração em equipe. Envolve arquitetura, testes e documentação.

**Exercício 1.1:** Qual a principal diferença entre programar e projetar software?

- a) Programar é mais difícil que projetar.
- b) Projetar foca apenas em documentação.
- c) Programar foca na escrita de código, enquanto projetar engloba todo o ciclo de vida e qualidades sistêmicas.
- d) Não há diferença.

<details>
<summary>Ver Resposta</summary>

**Resposta:** c) Programar foca na escrita de código, enquanto projetar engloba todo o ciclo de vida e qualidades sistêmicas.

**Explicação:** A engenharia de software (projetar) é uma disciplina mais ampla que usa a programação como uma de suas ferramentas, mas adiciona rigor, processos e foco em qualidade a longo prazo.
</details>

## 1.2 Qualidade de Software

Qualidade de software não é apenas "não ter bugs". Segundo a ISO/IEC 25010, qualidade é dividida em várias características[2]:

1. **Manutenibilidade:** Facilidade com que o software pode ser modificado.
2. **Escalabilidade:** Capacidade de lidar com aumento de carga.
3. **Testabilidade:** Facilidade de verificar se o software funciona corretamente.
4. **Segurança:** Proteção de dados e informações.

[IMAGEM_02_CARACTERISTICAS_QUALIDADE_ISO25010]

## 1.3 Processos de Desenvolvimento

Historicamente, o desenvolvimento de software passou por diversas fases.

### Modelo Cascata (Waterfall)
Um processo linear e sequencial. Cada fase (Requisitos, Design, Implementação, Testes, Manutenção) deve ser completada antes da próxima começar.
- **Vantagem:** Disciplina e documentação clara.
- **Desvantagem:** Rigidez e dificuldade de acomodar mudanças.

### Modelo Espiral
Combina a natureza iterativa da prototipagem com os aspectos controlados e sistemáticos do modelo cascata. Foca muito em análise de riscos.

## 1.4 Métodos Ágeis

O Manifesto Ágil (2001) mudou a indústria ao valorizar:
- **Indivíduos e interações** mais que processos e ferramentas.
- **Software em funcionamento** mais que documentação abrangente.
- **Colaboração com o cliente** mais que negociação de contratos.
- **Responder a mudanças** mais que seguir um plano.

### Scrum
Framework para gerenciar trabalho complexo.
- **Papéis:** Product Owner (PO), Scrum Master, Dev Team.
- **Cerimônias:** Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective.
- **Artefatos:** Product Backlog, Sprint Backlog, Incremento.

### Kanban
Método visual para gerenciar trabalho à medida que ele avança em um processo. Foca em **fluxo contínuo** e limitar o trabalho em progresso (WIP).

[IMAGEM_03_QUADRO_KANBAN]

**Exercício 1.4:** Qual cerimônia do Scrum é focada na melhoria do processo da equipe?

- a) Sprint Review
- b) Daily Scrum
- c) Sprint Retrospective
- d) Sprint Planning

<details>
<summary>Ver Resposta</summary>

**Resposta:** c) Sprint Retrospective

**Explicação:** A Retrospectiva ocorre ao final da Sprint e é dedicada a inspecionar como a última Sprint foi em termos de pessoas, relações, processos e ferramentas, para criar um plano de melhorias.
</details>

## 1.5 Cultura Ágil e Produto

A cultura ágil vai além dos frameworks. Trata-se de uma mentalidade de **Produto** vs **Projeto**.
- **Mentalidade de Projeto:** Foco em escopo, prazo e custo (Triângulo de Ferro). Sucesso = entregar no prazo.
- **Mentalidade de Produto:** Foco no valor entregue ao usuário, outcome (resultado) vs output (entrega). MVP (Minimum Viable Product) é essencial para validar hipóteses rapidamente.

**Backlog:** Lista priorizada de tudo que pode ser necessário no produto.

## 1.6 Ferramentas de Mercado

A engenharia de software moderna depende de ferramentas robustas para gestão e colaboração.

- **Jira:** Padrão da indústria para gestão de projetos ágeis (Scrum/Kanban).
- **Trello:** Ferramenta visual baseada em colunas (Kanban), mais simples que o Jira.
- **GitHub Projects:** Gestão de tarefas integrada ao repositório de código, ganhando muita força.

## Referências

[1] IEEE. Standard Glossary of Software Engineering Terminology. IEEE Std 610.12-1990.

[2] ISO/IEC. Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models. ISO/IEC 25010:2011.

---
[Próximo módulo →](../teoria/modulo_02_requisitos_modernos.md)

[Voltar aos Links Rápidos](../README.md#links-rapidos)
