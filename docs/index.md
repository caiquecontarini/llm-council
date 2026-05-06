# 🏛️ LLM Council

Sistema inteligente de tomada de decisão com múltiplas IAs.

## O que é LLM Council?

Um framework que orquestra múltiplas IAs (personas) para debater, avaliar e chegar a decisões mais inteligentes.

## 🎯 Características

- **Multi-IA** — Múltiplos modelos de IA
- **Debate** — Cada IA apresenta sua perspectiva
- **Consenso** — Convergência para melhor solução
- **Rastreável** — Veja o raciocínio de cada um

## 🚀 Quick Start

```python
from llm_council import Council

council = Council([
    Persona("Analyst", "Perspectiva analítica"),
    Persona("Creative", "Perspectiva criativa"),
    Persona("Strategist", "Perspectiva estratégica")
])

decision = council.debate("Qual é a melhor estratégia de marketing?")
```

## 📚 Navegação

- [Arquitetura](arquitetura.md) — Como funciona
- [Como Usar](como-usar.md) — Guia prático
- [Casos de Uso](casos-uso.md) — Exemplos reais
- [API](api.md) — Referência técnica

---

**Decisões melhores, IAs colaborando!** 🤖
