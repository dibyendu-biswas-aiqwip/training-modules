# 📚 OpenAI API Overview

## 🔷 OpenAI Model Types:
I explored the different types of OpenAI models and their purposes:

- **Reasoning Models (`gpt-4o`)** – Designed for complex, multi-step tasks like problem-solving, coding, and logical reasoning.
- **Flagship Chat Models (`gpt-4-turbo`)** – Versatile, general-purpose models great for conversations, writing, tutoring, and more.
- **Cost-Optimized Models (`gpt-3.5-turbo`)** – Faster and cheaper models for simpler, high-volume applications.
- **Realtime Models** – Built for real-time applications like voice assistants and low-latency interactions.
- **Text-to-Speech** – Converts text into natural-sounding spoken audio (`tts-1`, `tts-1-hd`).
- **Transcription (`whisper`)** – Transcribes and translates audio into text with multilingual support.
- **Embeddings** – Converts text into vector representations for tasks like search and similarity (`text-embedding-3-small/large`, `ada-002`).

---

## 🛠️ OpenAI API Parameters Explained:

| **Parameter**       | **Purpose** |
|---------------------|-------------|
| `temperature`       | Controls randomness (0 = deterministic, 1+ = creative). |
| `top_p`             | Limits token selection to top cumulative probability. |
| `max_tokens`        | Sets max length of output. |
| `frequency_penalty` | Discourages repeating tokens. |
| `presence_penalty`  | Encourages introducing new topics. |
| `stop`              | Stops generation at specified sequence(s). |
| `n`                 | Number of responses to generate. |
| `stream`            | Enables real-time streaming of tokens. |
| `logit_bias`        | Modifies likelihood of specific tokens. |
| `user`              | Tracks end-user for safety and analytics. |

---

## 🧠 Embedding Model Dimensions:

| **Model**                  | **Vector Dimension** |
|---------------------------|----------------------|
| `text-embedding-3-small`  | 1,536                |
| `text-embedding-3-large`  | 3,072                |
| `text-embedding-ada-002`  | 1,536                |

---

