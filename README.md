# Pipeliner — Token Atlas

An interactive visualizer for how LLMs and classic NLP models turn text into tokens, token IDs and embeddings.

- **Live tokenizer playground** — GPT-4o (o200k_base) and GPT-4 (cl100k_base) running their real vocabularies in the browser via js-tiktoken, plus simulated BERT WordPiece (30,522) and legacy word-level (10,000) tokenizers.
- **3D embedding space** — drag, zoom and inspect 40 words; switch between meaning-based and spelling-based space and try king − man + woman.
- **Vocabulary size trade-off** — sequence length versus embedding-table memory across models and embedding sizes.
- **Concept guide** — 8 core NLP and LLM concepts, each linked to a live demo.

Static site, no build step. Open `index.html` through any static server, or deploy the folder as-is to Vercel.
