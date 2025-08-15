# SPAIS – Spatial AI Systems via Modular Onto-Logic Embeddings

## Overview

**SPAIS** is a modular architecture and conceptual framework for building **Spatial Artificial Intelligence Systems** 
by anchoring spatial, ontological, and poly-linear features in shared spatiotemporal vector space. 
This repository introduces and interconnects four foundational papers:

- [SIM: Statically Implied Models](./SIM - Statically Implied Models for Transparent and Interoperable Embeddings.pdf)
- [STEM: Spatiotemporal Embedding Model](./STEM - Stabilizing the Stochastic with the Static.pdf)
- [MOSES: Modular Onto-Logic Spatial Embedding System](./MOSES - Modularizing a Geospatial Mind.pdf)
- [SPAIS: A Path to Spatial AI Systems](./SPAIS_ArXIV_2401.10279v1.pdf)

Together, they provide a blueprint for spatially grounded LLM systems, explainable vector reasoning, and scalable 
knowledge integration using deterministic embeddings.

## Key Concepts

### 🧠 SIM – Statically Implied Models
A new class of **transparent, decomposable, and deterministic embeddings** for spatial and ontological domains. 
Each SIM encodes meaningful features with explainable arithmetic and interoperable structure, enabling vector-native joins, 
alignment, and reuse.

### 🌐 STEM – Spatiotemporal Embedding Model
A core SIM that encodes latitude, longitude, altitude, and time into a unified spatial-temporal vector (called `stem_vector`).
stem_vector is of the form:
STEM(lat, lon, alt, t) = [sin(lat), cos(lat), sin(lon), cos(lon), alt/h, sin(2πt/T), cos(2πt/T)]
This shared vector becomes a **spatial anchor** for all geo-based models.

- Deterministic
- Time-aware (sin/cos encoding)
- Supports model integration across systems

### 🧩 MOSES – Modular Onto-Logic Spatial Embedding System
MOSES is a cognitive and architectural model built from **three baseline SIMs**:
- `STEM-GLE`: The universal spatiotemporal anchor
- `GOE`: Geospatial Onto-logic Embeddings (e.g., hospitals, parks, bridges)
- `GPLE`: Geospatial Poly-Linear Embeddings (e.g., zones, paths, boundaries)

All are embedded into vector databases (e.g., Weaviate), enabling **modular intelligence** via Retrieval-Augmented Generation (RAG) 
over interoperable embeddings. MOSES mimics human cognition via distributed modules and a common referential index (`stem_vector`).

### SPAIS – Spatial AI Systems
Published in arXiv [Tucker, 2024](https://arxiv.org/abs/2401.10279), this review paper examines the evolution of 
**Geospatial Location Embeddings (GLE)** and proposes SPAIS as the future of LLM+GeoAI integration.

It calls for:
- **SLMs** (Spatial Language Models) with native spatial vector awareness (As STEM now suggests)
- **Spatial Vector Space (SVS)** as a grounded reference system (As now proposed by SIM and actualized by STEM)
- **LLN** (Large Language Nexus) to coordinate LLMs and SLMs like hemispheres of the brain (As accomplished via 
  vector database model-integration and RAG)

## Why This Matters

Current LLMs lack intrinsic spatial intelligence. 
Attempts to force geospatial meaning into non-spatial models lead to 
- performance bottlenecks, brittle integrations, and black-box reasoning. 
MOSES, SIM, and STEM respond with:
- Deterministic, referenceable embeddings
- Unified spatiotemporal anchoring (`stem_vector`)
- Vector-native, explainable joins
- Modular design for scalable SPAIS development
- Cognitive analogues to distributed mind and modular intelligence

## Academic Context

This work draws deeply from 
- cognitive science of modular reasoning (Fodor, 1983; Gardner, 1983), 
- spatial information theory (Kuhn, 2003, 2012)
- multiscale interaction models (Oshan, 2020)
- recent GeoAI advances (Mai et al., 2022–2023).

> “The architecture borrow from the modular structure of the human mind. 
Each SIM is a specialized reasoning unit, and the `stem_vector` acts as a spatial referential index 
— much like attention in the brain allows distributed yet co-referenced intelligence.”  
> — *Tucker, MOSES 2025*

## Suggested Readings by Section

| Theme | Paper | Suggested Sections |
|-------|-------|---------------------|
| Cognitive Architecture | MOSES | Introduction, Section 4.4 |
| Deterministic Embeddings | SIM | Sections 2 & 3 |
| Spatiotemporal Anchoring | STEM | Sections 2–4 |
| Vector Reasoning & Integration | MOSES | Section 4 |
| Geospatial LLM Interop | SPAIS | Entire paper (esp. Figures 2–4) |

## Citation (TBD)

For full reference list, please see the Bibliography sections of each paper.

## Future Work

Explore:
- New SIM types (mobility, emissions, economy)
- Interoperable GeoMesh base layers (Build and host GeoMesh as basic SIM BaseLayer)
- Standardization of `stem_vector` for open SIMs
- Cross-disciplinary fusion with environmental, health, and transport domains

For collaboration inquiries, open an issue or contact the author directly.
