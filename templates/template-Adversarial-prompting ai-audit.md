---

tags: [adversarial-prompting, ai-audit, prompt-engineering]
status: em-construção
versão: 1.0
última-atualização: 2026-03-18
autor: Weberson Azemclever Dias Braga De Souza

# Adversarial Prompt Audit Repository

> **Mycelliun Weights Protocol** · Prompt Engineering & LLM Behavior Analysis

---

## Taxonomia de Categorias

| ID     | Nome                        | Descrição                                                                                |
| ------ | --------------------------- | ---------------------------------------------------------------------------------------- |
| CAT-01 | Cognitive Bias Exploitation | Provoca vieses cognitivos documentados — Anchoring, Framing, Confirmation Bias, etc.     |
| CAT-02 | Role & Identity Confusion   | Explora incoerências quando o modelo assume personas ou recebe identidades conflitantes. |
| CAT-03 | Instruction Conflict        | Cria contradições internas no prompt para observar qual instrução o modelo prioriza.     |
| CAT-04 | Output Manipulation         | Usa estrutura e framing para induzir outputs distorcidos sem jailbreak explícito.        |

---

## Severity Rating

|Nível|Critério|
|---|---|
|🟢 BAIXO|Comportamento anômalo com impacto mínimo em contexto real. Difícil de explorar intencionalmente.|
|🟡 MÉDIO|Comportamento que poderia enganar ou confundir usuários em contextos específicos.|
|🔴 ALTO|Falha reproduzível com potencial de impacto real em deployment. Fácil de replicar.|
|⚫ CRÍTICO|Risco direto de dano, desinformação sistemática ou bypass de guardrails fundamentais.|

---

## Como Usar

1. Duplique a seção **ENTRADA DE CASO** para cada novo teste.
2. Nunca deixe campos em branco — use `N/A` quando não aplicável.
3. O **Prompt** deve ser copiado exatamente como enviado, sem edições.
4. O **Output** deve ser copiado exatamente como recebido, sem resumos.
5. Teste sempre em pelo menos **dois modelos** e registre ambos.
6. Mantenha o Severity Rating consistente com a taxonomia acima.

---

## Índice de Casos

| #            | Nome do Caso | Categoria | Severity | Data |
| ------------ | ------------ | --------- | -------- | ---- |
| [[caso 001 PT]] |              |           |          |      |
| [[caso 002 PT]] |              |           |          |      |
| [[caso 003 PT]] |              |           |          |      |
| [[caso 004 PT]] |              |           |          |      |

> 💡 Dica Obsidian: use `[[caso-001]]` para criar notas individuais vinculadas, ou mantenha tudo neste arquivo se preferir um repositório único.

---

---

# ENTRADA DE CASO · #001

## Identificação

|Campo|Valor|
|---|---|
|**Nome do Caso**||
|**Categoria**|CAT-0X ·|
|**Data do Teste**||
|**Modelo 1**||
|**Modelo 2**||
|**Tags**||

---

## Objetivo do Teste

> Descreva o que você estava tentando provocar. Qual comportamento inadequado, viés ou falha você esperava observar?

```
[escreva aqui]
```

### Hipótese

> Com base no que você conhece sobre esse viés ou falha, por que você acredita que esse prompt específico funcionaria?

```
[escreva aqui]
```

---

## O Prompt

> ⚠️ Cole o prompt **exatamente** como foi enviado — sem edições, resumos ou paráfrases.

```
[cole o prompt aqui]
```

### System Prompt (se aplicável)

```
[cole o system prompt aqui — ou escreva: Nenhum]
```

---

## Output Obtido

### Modelo 1 — `[nome do modelo]`

```
[cole o output completo aqui]
```

### Modelo 2 — `[nome do modelo]`

```
[cole o output completo aqui]
```

---

## Análise

### O que aconteceu?

> Descreva o comportamento do modelo de forma objetiva. O que na resposta confirma ou refuta sua hipótese?

```
[escreva aqui]
```

### Por que aconteceu?

> Análise do mecanismo subjacente. Conecte o comportamento a princípios de treinamento, vieses conhecidos ou limitações documentadas.

```
[escreva aqui]
```

### Diferença entre modelos

> O Modelo 1 e o Modelo 2 responderam de forma diferente? O que essa diferença revela?

```
[escreva aqui — ou: N/A, comportamento idêntico]
```

---

## Severity Rating

- [ ] 🟢 BAIXO
- [ ] 🟡 MÉDIO
- [ ] 🔴 ALTO
- [ ] ⚫ CRÍTICO

### Justificativa

> Por que você atribuiu esse nível? Considere: impacto em usuários reais, facilidade de reprodução, possibilidade de uso malicioso.

```
[escreva aqui]
```

---

## Reproduction Steps

1. Acesse: `[modelo e interface utilizada]`
2. Configure o system prompt conforme registrado acima (ou nenhum).
3. Envie o prompt exatamente como registrado na seção **O Prompt**.
4. Observe se o output reproduz o comportamento documentado.
5. `[adicione passos específicos se necessário]`

---

## Implicações & Recomendações

### Implicação para Segurança / Governança

> O que esse comportamento revela sobre riscos reais de deployment deste modelo?

```
[escreva aqui]
```

### Recomendação de Mitigação

> O que poderia ser feito no treinamento, guardrails ou design de sistema para mitigar?

```
[escreva aqui]
```

---

---

# ENTRADA DE CASO · #002

## Identificação

|Campo|Valor|
|---|---|
|**Nome do Caso**||
|**Categoria**|CAT-0X ·|
|**Data do Teste**||
|**Modelo 1**||
|**Modelo 2**||
|**Tags**||

---

## Objetivo do Teste

```
[escreva aqui]
```

### Hipótese

```
[escreva aqui]
```

---

## O Prompt

```
[cole o prompt aqui]
```

### System Prompt (se aplicável)

```
[cole o system prompt aqui — ou escreva: Nenhum]
```

---

## Output Obtido

### Modelo 1 — `[nome do modelo]`

```
[cole o output completo aqui]
```

### Modelo 2 — `[nome do modelo]`

```
[cole o output completo aqui]
```

---

## Análise

### O que aconteceu?

```
[escreva aqui]
```

### Por que aconteceu?

```
[escreva aqui]
```

### Diferença entre modelos

```
[escreva aqui]
```

---

## Severity Rating

- [ ] 🟢 BAIXO
- [ ] 🟡 MÉDIO
- [ ] 🔴 ALTO
- [ ] ⚫ CRÍTICO

### Justificativa

```
[escreva aqui]
```

---

## Reproduction Steps

1. Acesse: `[modelo e interface utilizada]`
2. Configure o system prompt conforme registrado acima (ou nenhum).
3. Envie o prompt exatamente como registrado na seção **O Prompt**.
4. Observe se o output reproduz o comportamento documentado.
5. `[adicione passos específicos se necessário]`

---

## Implicações & Recomendações

### Implicação para Segurança / Governança

```
[escreva aqui]
```

### Recomendação de Mitigação

```
[escreva aqui]
```

---
