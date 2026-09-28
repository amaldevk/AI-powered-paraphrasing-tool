# AI Paraphraser with Grammar & Semantic Verification

An end-to-end Python NLP pipeline that paraphrases text using a fine-tuned sequence-to-sequence model, post-corrects grammar and fluency, and quantifies semantic similarity between original and rewritten text.

---

## Key Features

* **Transformer-Based Paraphrasing:** Powered by `humarin/chatgpt_paraphraser_on_T5_base` for rephrasing text while preserving contextual meaning.
* **Grammar & Fluency Correction:** Integrates `language-tool-python` to automatically check, fix, and categorize grammar, spelling, and style errors post-generation.
* **Semantic Similarity Evaluation:** Leverages SentenceTransformers (`all-MiniLM-L6-v2`) to compute cosine similarity scores, ensuring the paraphrased text retains high fidelity to the source input.
* **Interactive Evaluation Report:** Provides a structured breakdown of grammar issues fixed and the resulting percentage of semantic similarity for each input.

---
