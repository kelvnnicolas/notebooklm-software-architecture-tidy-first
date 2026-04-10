# 📘 NotebookLM Study Guide — Software Architecture com Tidy First

## 📌 Contexto

Este projeto foi desenvolvido como parte de um desafio prático da DIO com o objetivo de explorar o uso da Inteligência Artificial — especificamente o NotebookLM — como ferramenta de aprendizagem ativa.

O tema escolhido foi Arquitetura de Software, com base no livro Tidy First?, que aborda práticas essenciais de organização de código, refatoração incremental e tomada de decisão consciente no desenvolvimento de software.

A proposta foi não apenas consumir conteúdo, mas estruturar conhecimento, testar hipóteses com IA e documentar o processo de aprendizado de forma transparente.

---

## 🎯 Objetivos

* Consolidar fundamentos de arquitetura de software
* Utilizar IA como copiloto de aprendizado técnico
* Desenvolver pensamento crítico sobre design de código
* Criar um material reutilizável (miniguia + prompts)
* Demonstrar processo de aprendizado (incluindo erros e ajustes)

---

## 📚 Curadoria de Fontes

As seguintes fontes foram utilizadas como base para o estudo e carregadas no NotebookLM:

1. Tidy First? — Kent Beck
2. Refactoring — Martin Fowler (artigos e resumos)
3. Clean Code — Robert C. Martin (conceitos e práticas)
4. Refactoring Guru — Code Smells (https://refactoring.guru)

📌 Observação: A qualidade das respostas da IA foi diretamente impactada pela qualidade e foco das fontes utilizadas.

---

## 🤖 Engenharia de Prompts e Aprendizados

### 🔹 Prompt 1 — Exploração Inicial

**Prompt:**

> Explique os principais conceitos do livro Tidy First de forma simples

**Problema:**

* Resposta genérica
* Pouco aplicável ao contexto real de desenvolvimento

**Ajuste:**

> Explique os conceitos do Tidy First com foco em aplicação prática para desenvolvedores backend

**Resultado:**

* Respostas mais direcionadas
* Inclusão de exemplos reais

---

### 🔹 Prompt 2 — Falta de Contexto

**Prompt:**

> Liste boas práticas de arquitetura

**Problema:**

* Resposta ampla demais
* Não utilizou as fontes carregadas

**Correção:**

> Baseado exclusivamente nas fontes fornecidas, liste práticas de arquitetura segundo o Tidy First

**Insight:**
📌 A IA performa melhor quando restrita ao contexto (source grounding)

---

### 🔹 Prompt 3 — Extração de Valor

**Prompt:**

> Transforme os conceitos do Tidy First em um checklist prático para revisão de código

**Resultado:**

* Output altamente aplicável
* Pode ser reutilizado em projetos reais

---

### 🔹 Prompt 4 — Simulação

**Prompt:**

> Simule uma revisão de código aplicando os princípios do Tidy First

**Resultado:**

* Excelente para aprendizado ativo
* Aproxima teoria da prática

---

## 📘 Miniguia de Estudo

### 🔹 1. Separação de Mudanças

* Mudanças estruturais ≠ mudanças comportamentais
* Nunca misturar refatoração com alteração de lógica

📌 Impacto:

* Redução de bugs
* Facilita code review
* Melhora rastreabilidade

---

### 🔹 2. Pequenas Melhorias Contínuas

* Sempre melhorar o código antes de adicionar novas features
* Evita acúmulo de débito técnico

📌 Mentalidade:

> “Deixe o código melhor do que você encontrou”

---

### 🔹 3. Código como Comunicação

* Código deve ser legível antes de ser otimizado
* Clareza > complexidade

📌 Prática:

* Nomeação clara
* Funções pequenas
* Intenção explícita

---

### 🔹 4. Refatoração Segura

* Alterar estrutura sem mudar comportamento
* Testes são essenciais

📌 Estratégia:

* Refatorar em pequenos passos
* Validar constantemente

---

### 🔹 5. Redução de Complexidade

* Evitar abstrações prematuras
* Preferir soluções simples

📌 Regra prática:

> Se está difícil de entender, está errado

---

## 📖 Glossário

* **Refatoração:** melhoria da estrutura do código sem alterar comportamento
* **Code Smell:** indício de problema no design do código
* **Débito Técnico:** custo acumulado de decisões ruins
* **Acoplamento:** dependência entre componentes
* **Coesão:** foco de um módulo em uma única responsabilidade
* **Legibilidade:** facilidade de entender o código
* **Abstração:** simplificação de complexidade

---

## 🔁 Prompts Reutilizáveis

* Explique [conceito] com exemplos práticos em backend
* Baseado nas fontes, quais são os principais erros ao aplicar [conceito]?
* Transforme esse conceito em checklist de código
* Simule uma revisão de código aplicando [conceito]
* Compare [conceito A] vs [conceito B] com exemplos reais
* Gere um exemplo de código ruim e refatore aplicando Tidy First

---

## 🚀 Aplicação Prática

### Antes (problema comum)

* Função longa
* Responsabilidades misturadas
* Difícil de testar e manter

### Depois (aplicando Tidy First)

* Separação de responsabilidades
* Melhor nomeação
* Refatoração incremental

📌 Resultado:

* Código mais legível
* Mais fácil de testar
* Mais escalável

---

## 🧠 Principais Insights

* IA não substitui pensamento crítico — ela amplifica
* Prompt mal feito = resposta inútil
* Contexto é mais importante que volume de informação
* Aprendizado real vem da iteração (tentativa e erro)

---

## 📂 Estrutura do Repositório

```
/README.md
/assets (opcional)
/prompts.md (opcional)
/notes.md (opcional)
```

---

## 🏁 Conclusão

Este projeto demonstrou como a combinação de:

* Curadoria de conteúdo
* Engenharia de prompts
* Pensamento crítico
* Documentação estruturada

pode transformar o uso de IA em uma ferramenta real de aprendizado e não apenas geração de respostas.

Mais do que entender arquitetura de software, este projeto evidencia a capacidade de aprender de forma autônoma, estruturada e orientada a resultados — habilidade essencial no cenário atual de tecnologia.

---

## 🔗 Entrega

Repositório desenvolvido para o desafio da DIO utilizando NotebookLM como ferramenta central de estudo.

---
