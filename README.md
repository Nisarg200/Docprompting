🚀 DocPrompting: Enhancing Code Generation with Documentation

This project is a simplified implementation of the DocPrompting research paper, which improves code generation from natural language (NL) intent by retrieving and incorporating relevant documentation during prompting.

By leveraging retrieval-augmented prompting, the system ensures that generated code is more accurate, context-aware, and aligned with real-world documentation.

🧠 Key Features

🔹 Natural Language to Code – Accepts NL intent from users at runtime.

🔹 Documentation Retrieval – Uses TF-IDF and cosine similarity to fetch the most relevant documentation snippets.

🔹 LLM-powered Generation – Generates Python code using a causal language model (CodeGen-350M-mono).

🔹 Comparative Evaluation – Compares outputs with vs. without documentation to measure improvement.

🔹 Performance Metrics – Evaluates code generation quality using CodeBLEU.
