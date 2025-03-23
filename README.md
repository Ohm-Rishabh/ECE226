## ECE226 – Speculative Decoding

This repository contains implementations for auto-regressive text generation, including a baseline and speculative decoding variant. Developed as part of the ECE226 course project.

---

## 📁 Repository Structure

```text
sampling/
├── base_decoding.py          # Naive auto-regressive generation (baseline)
├── speculative_decoding.py   # Speculative decoding implementation

utils/
├── ...                       # Logits processing, formatted printing, etc.
```

## 📌 Highlights

- **Base Decoding**: Implements the standard greedy auto-regressive text generation using a language model.
- **Speculative Decoding**: Optimized generation technique using a draft and target model to accelerate inference.
- **Utility Functions**: Helpful tools for processing logits, formatting outputs, and other common tasks.

---
