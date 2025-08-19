# NCERTwise
This repository contains a Falcon-7B-Instruct model fine-tuned specifically on NCERT-based social studies material for grades 5–10 using LoRA and 4-bit quantization. The model has been trained to provide strictly NCERT-aligned answers in a simplified and student-friendly style, ensuring clarity and alignment with the curriculum. Retrieval-augmented generation (RAG) ensures the model remains anchored to source material for maximal factual fidelity.

Key features:
- Trained on curated, self-made NCERT textual content from class 5–10 social studies.
- Parameter-efficient tuning via LoRA and quantization for efficient inference.
- Accurate, context-backed answers following NCERT language and style.
- Retrieval mechanism to ensure responses are sourced directly from extracted NCERT content.

This tool is ideal for students seeking clear, curriculum-aligned explanations directly rooted in NCERT texts, without any extraneous content.

