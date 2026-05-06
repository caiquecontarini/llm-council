# 📖 Como Usar

Guia prático para começar com LLM Council.

## Instalação

```bash
pip install llm-council
```

## Setup Básico

```python
from llm_council import Council, Persona

council = Council(
    personas=[
        Persona("Analyst", "Avalia dados e fatos"),
        Persona("Creative", "Pensa fora da caixa"),
        Persona("Critic", "Identifica riscos")
    ]
)
```

## Fazer um Debate

```python
result = council.debate(
    question="Como crescer meu negócio?",
    context="Startup em fase inicial"
)

print(result.decision)
print(result.perspectives)
```

## Customizar Personas

```python
custom_persona = Persona(
    name="MyExpert",
    expertise="Meu domínio específico",
    style="Formal e assertivo"
)
```

## Casos de Uso

- Decisões estratégicas
- Análise de riscos
- Brainstorms
- Avaliação de ideias

---

[🏠 Voltar para Home](index.md)
