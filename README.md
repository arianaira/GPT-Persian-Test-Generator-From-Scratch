## Persian Wikipedia Text Generator (LLM from Scratch)

### 1. Introduction and Goal
The objective of this exercise was to implement a Large Language Model (LLM) for text generation using the **Persian Wikipedia dataset**. A fundamental requirement was to implement the model **from scratch**, designing and coding the neural network architecture without using pre-trained or fine-tuned models.

### 2. Methodology Summary
1.  **Dataset Creation:** The full Persian Wikipedia dataset, consisting of **7,547,845 lines** and over **478 million characters**, was utilized.
2.  **Normalization:** Rigorous text preprocessing was performed using the **`hazm` library**. This involved applying the `hazm` normalizer, standardizing special characters (e.g., replacing hamzas like 'أ' and 'ئ'), and deleting all non-Persian alphabet characters using specific regex patterns.
3.  **Model Implementation:** A **GPT-style decoder-only Transformer model** was designed and implemented *from scratch* using PyTorch.
4.  **Training:** The network was successfully trained on the massive, normalized dataset.

### 3. Evaluation and Key Result
Model evaluation used Perplexity (PPL), a standard metric for language models.

| Metric | Final Result |
| :--- | :--- |
| **Perplexity (PPL)** | **3.99** |

