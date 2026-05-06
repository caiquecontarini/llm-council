# 🔌 API Reference

Documentação completa da API do LLM Council.

## Council

### `__init__(personas, config={})`

Inicializa um novo council com personas.

### `debate(question, context="")`

Executa debate entre personas.

**Retorno:** `Decision` com resultado e perspectivas.

---

## Persona

### `__init__(name, expertise, style="")`

Define uma persona especializada.

**Parâmetros:**
- `name` — Nome da persona
- `expertise` — Área de especialidade
- `style` — Estilo de comunicação

---

## Decision

Resultado de um debate.

**Atributos:**
- `decision` — Decisão final
- `perspectives` — Perspectivas individuais
- `confidence` — Nível de confiança

---

[🏠 Voltar para Home](index.md)
