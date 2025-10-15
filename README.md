# Multi-Artifact-Analysis-of-Self-Admitted-Technical-Debt-in-Scientific-Software
Replication package of the research paper "Multi-Artifact Analysis of Self-Admitted Technical Debt in Scientific Software".

Context: Large Language Models (LLMs) like GPT-5 and LLaMA-
405b exhibit advanced code generation abilities, but their deploy-
ment demands substantial computation resources and energy. Quan-
tization can reduce memory footprint and hardware requirements,
yet may degrade code quality. Objective: This study investigates
code generation performance of smaller LLMs, examines the ef-
fect of quantization, and identifies common code quality issues as
a proof of concepts (PoC). Method: Four open-source LLMs are
evaluated on Python benchmarks using code similarity metrics,
with an analysis on 8-bit and 4-bit quantization, alongside static
code quality assessment. Results: While smaller LLMs can generate
functional code, benchmark performance is limited. Quantization
impacts are variable, and generated code exhibits quality and main-
tainability concerns. Conclusions: LLM-generated code should be
carefully validated before integration into software projects.
