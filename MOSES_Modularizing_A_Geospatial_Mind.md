# MOSES – Modularizing a Geospatial Mind: Modular Onto-Logic Embeddings for Spatial AI Reasoning

**Sean Tucker**

---

## Abstract

We introduce MOSES (Modular Onto-Logic Spatial Embedding System), a framework for transparent, interoperable, and modular reasoning in geospatial AI. MOSES composes three baseline Statically Implied Models (SIMs): the Spatiotemporal Embedding Model (STEM-GLE), the Geospatial Ontological Embedding (GOE), and the Geospatial Poly-Linear Embedding (GPLE). These SIMs are deterministic, interpretable, and algebra-compatible vector representations of real-world entities. Each includes a shared `stem_vector` derived from STEM-GLE, enabling cross-embedding spatial anchoring, model-integration, and vector-native reasoning in systems like Weaviate. We propose this as the foundation for Prompt-Readable Vector Logic—where both humans and language models can directly reason over embedded vectors. MOSES draws inspiration from modular theories of cognition, offering a novel model for AI systems that are spatially grounded, symbolically interoperable, and cognitively inspired.

## 1. Introduction

Modern AI systems struggle to reason over real-world geospatial structures with transparency and accountability. Most spatial embeddings are opaque, learned representations that cannot be directly interpreted or decomposed [Mai et al., 2022; Bommasani et al., 2021]. This poses serious limitations in safety-critical fields like transportation, environmental planning, and disaster response—where human-AI collaboration requires semantic grounding, spatial traceability, and symbolic compatibility [Cai & Wang, 2020; Janowicz et al., 2020].

To address this, we introduce MOSES, a modular AI system built from Statically Implied Models (SIMs). SIMs are a class of deterministic, algebra-compatible vector embeddings that encode structured knowledge in a reproducible and interpretable form [Tucker, 2024].

In MOSES, we compose three baseline SIMs—STEM-GLE, GOE, and GPLE—into a modular architecture. These are not the only possible SIMs; they are baseline types, extensible by domain, geometry, or logic layer.

Crucially, each geo-based SIM in MOSES includes a shared `stem_vector`, derived from STEM-GLE. This spatial anchor enables model-integration in vector databases, allowing cross-SIM joins, spatial proximity logic, and vector-native referencing of real-world features.

Inspired by theories of modular intelligence and distributed cognition [Fodor, 1983; Gardner, 1983; Rumelhart & McClelland, 1986; Clark & Chalmers, 1998], MOSES offers a new model of AI reasoning that mimics the brain’s integration of specialized representations through common spatial and temporal grounding.

...

## References

- Bommasani, R., et al. (2021). *On the Opportunities and Risks of Foundation Models*. arXiv:2108.07258.  
- Cai, L., & Wang, J. (2020). *A survey of explainable AI: Interpretability, fairness, and robustness*. arXiv:2006.11371.  
- Clark, A., & Chalmers, D. (1998). *The extended mind*. Analysis, 58(1), 7–19.  
- Fodor, J. A. (1983). *The Modularity of Mind*. MIT Press.  
- Fotheringham, A. S., Oshan, T. M., & Wolf, L. J. (2023). *Multiscale geographically weighted regression: A framework for multiscale spatial process modeling*. Geographical Analysis.  
- Gardner, H. (1983). *Frames of Mind: The Theory of Multiple Intelligences*. Basic Books.  
- Janowicz, K., et al. (2020). *GeoAI: Spatially Explicit Artificial Intelligence Techniques*. IJGIS.  
- Kuhn, W. (2003). *Semantic reference systems*. IJGIS, 17(5), 405–409.  
- Mai, G., et al. (2022). *Toward a theory of spatial information observability*. Transactions in GIS, 26(2), 867–884.  
- Oshan, T. M. (2020). *Spatial interaction modeling with vector-based data*. Spatial Analysis Journal.  
- Rumelhart, D. E., & McClelland, J. L. (1986). *Parallel Distributed Processing*. MIT Press.  
- Smith, B., & Mark, D. M. (2001). *Geographic categories: An ontological investigation*. IJGIS, 15(7), 591–612.  
- Tucker, S. (2024). *A systematic review of geospatial location embedding approaches*. arXiv:2401.10279.  
- Tucker, S. (2025a). *SIM: Statically Implied Models for Embedding Spatiotemporal Knowledge*. arXiv Preprint.  
- Tucker, S. (2025b). *STEM: Stabilizing the Stochastic with the Static: A Deterministic Spatiotemporal Embedding Model*. arXiv Preprint.