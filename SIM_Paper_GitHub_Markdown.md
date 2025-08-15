
# SIM: Statically Implied Models for Transparent and Interoperable Embedding of Spatiotemporal Knowledge
### A Foundation for Prompt-Readable, Vector-Native Reasoning

**Author**: Sean Tucker

---

## Abstract
We introduce **SIM (Statically Implied Models)**, a new class of deterministic, interpretable vector embedding systems designed for spatial-temporal knowledge representation and reasoning. Unlike learned embeddings, SIMs are algebraically structured, reproducible, and prompt-compatible. They support native vector math, symbolic decomposition, and transparent inference across infrastructure and planning domains. We formally define the properties of SIMs, motivate their need in geospatial and infrastructu...

---

## 1. Introduction

Most spatial embeddings today—whether derived from transformers (e.g., GeoBERT) or graph models—are opaque, non-reproducible, and difficult to interpret [Bommasani et al., 2021; Mai et al., 2022]. This limits their use in high-stakes reasoning domains such as infrastructure, transit, disaster planning, or regulatory systems, where traceability and symbolic compatibility are essential [Cai & Wang, 2020].

We propose a new embedding model class: **Statically Implied Models (SIMs)**.

SIMs encode structured domain knowledge—such as geospatial, ontological, or temporal information—into deterministic, algebra-compatible vectors. These vectors can be:
- Directly compared
- Algebraically manipulated
- Referenced in prompts
- Used across systems without retraining

SIMs restore interpretability, interoperability, and control to AI-based spatial reasoning, creating a new interface between vector logic and symbolic inference [Bengio et al., 2021; Garnelo & Shanahan, 2019].

No prior work has proposed a generalized, deterministic, and interpretable vector embedding *model class*—one that supports algebraic manipulation, cross-domain integration, and symbolic reasoning. While individual components of SIMs resemble ideas from positional encodings [Vaswani et al., 2017], geospatial reference systems [Kuhn, 2003], and symbolic AI frameworks [Bengio et al., 2021], SIMs unify these strands into a coherent and reusable framework. By introducing a model-theoretic foundation for sta...

SIMs are not proposed as a replacement for learned semantic embeddings or statistical models in domains where abstraction, generalization, or high-dimensional concept learning is critical. Rather, SIMs are designed to complement such systems—especially in settings where static knowledge, structured environments, or infrastructure constraints demand referential clarity and logical accountability.

---

## 2. Defining SIMs

We define a **Statically Implied Model (SIM)** as an embedding model that satisfies the following properties:

| Property            | Description |
|---------------------|-------------|
| Determinism         | Same input always yields the same output vector |
| Decomposability     | Components have known, interpretable meanings |
| Algebra-Compatibility | Supports vector math (e.g., differences, scaling) |
| Cross-Domain Reasoning | Operable across ontological/geospatial boundaries |
| Prompt-Readable     | Vector operations can be referenced in LLM prompts or symbolic logic |

This sets SIMs apart from learned vector models that are dense, opaque, and domain-fixed [Marcus, 2020].

---

## 3. SIMs and Prompt-Readable Vector Logic

SIMs support a new interaction mode for LLMs and AI systems:  
**Prompt-Readable Vector Logic** — vectors whose meaning and operations can be directly referenced in natural language reasoning [Kojima et al., 2022; Liu et al., 2021].

**Examples:**
- “What’s the elevation difference between location A and B?”
- “Which areas are within 500m and 15 minutes of a flood zone?”
- “Return all coffee shops uphill from the station and open now.”

SIMs enable symbolic + vector fusion—a language model can reason about vectors arithmetically, spatially, or relationally, using interpretable components. This makes SIMs usable in:
- Prompt injection pipelines
- Function-calling logic chains
- RAG frameworks over spatial vector databases [Tucker, 2024].

---

## 4. Case Study: STEM as SIM-0

We introduce **STEM (Spatiotemporal Embedding Model)** as the first SIM implementation [Tucker, 2025b].

Given:
- Latitude
- Longitude
- Altitude
- Time of day

STEM produces:
```
STEM(lat, lon, alt, t) = [sin(lat), cos(lat), sin(lon), cos(lon), alt/h, sin(2πt/T), cos(2πt/T)]
```

This vector is:
- Reproducible and interpretable
- Sensitive to time and elevation
- Usable in both vector databases (e.g., Weaviate [Yan et al., 2021]) and AI prompts

Use Case:  
A transit planner queries “stations within 15 minutes and uphill of any Zone 1 flood zone.”  
Using STEM vectors, the system computes this without GIS layers—via vector proximity and delta-altitude math.

---

## 5. Comparison: SIMs vs Learned Embeddings

| Capability              | SIM (e.g., STEM) | Learned Embeddings (e.g., GeoBERT) |
|-------------------------|------------------|------------------------------------|
| Deterministic           | ✅                | ❌                                 |
| Interpretable           | ✅                | ❌                                 |
| Algebraic               | ✅                | ⚠️ Partial                         |
| Prompt-Readable         | ✅                | ❌                                 |
| Cross-domain            | ✅                | ⚠️ Limited                         |
| Reusable across systems | ✅                | ❌                                 |

SIMs are ideal where transparency, control, and reproducibility are more important than statistical abstraction—such as public infrastructure, environmental systems, or AI explainability [Goodchild, 2009; Janowicz et al., 2020].

---

## 6. Toward MOSES: Modular Reasoning with SIMs

In upcoming work, we present **MOSES: the Modular Onto-logic Spatial Embedding System** [Tucker, 2025c].

MOSES composes multiple SIMs into a live AI reasoning engine:
- Uses STEM for space-time anchoring
- Adds GPLE and GOE for place logic and type embeddings [Smith & Mark, 2001; Kuhn, 2003]
- Integrates with vector search (e.g., Weaviate [Yan et al., 2021]) and LLMs
- Enables symbolic RAG with vector-native logic [Modi & Titov, 2021]

---

## 7. Conclusion

SIMs represent a shift in AI vector modeling—from black-box embeddings to deterministic, algebra-compatible, and interpretable representations. They provide a foundation for modular, reusable reasoning systems, and enable **Prompt-Readable Vector Logic** for transparent and traceable AI.

We position SIMs as the beginning of a new class of AI infrastructure—designed not just to encode meaning, but to make that meaning accessible, composable, and accountable.

---

## References

[Full reference list is identical to the original supplied. Available in the full Markdown file.]

