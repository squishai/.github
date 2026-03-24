# Squish AI: Squeeze the Most Out of Your Models 🤖🗜️⚡️

Welcome to **Squish AI**. We build high-performance tools designed to make local AI development as fast and efficient as possible, specifically optimized for Apple Silicon and modern developer workflows.

## 🚀 Featured Projects

### [squish](https://github.com/squishai/squish)

<img height="400" alt="11f7fc5a-e873-4ec3-9b48-8d58c0aba1a5_removalai_preview_upscayl_2x_digital-art-4x" src="https://github.com/user-attachments/assets/696cc561-571e-4f9b-84ce-84712a8e7f3d" />

**Compress local LLMs once, run them forever at sub-second load times.**
Squish is a drop-in replacement for OpenAI + Ollama workflows on Apple Silicon. It focuses on eliminating the "cold start" problem of local LLMs.

  * **Performance:** 54× faster cold starts compared to standard local runners.
  * **Accuracy:** Statistically identical accuracy to original models.
  * **Compatibility:** Seamless integration for existing Python-based AI applications.

### [drex](https://github.com/squishai/drex)

<img width="400" height="400" alt="Drex Logo" src="https://github.com/user-attachments/assets/b4640e58-7389-496d-b205-b51b10fb1009" />

The transformer is a brilliant hack scaled past its limits. DREX is what comes next — tiered memory, sparse execution, and a learned controller that knows what to remember.

-----

## 🛠 Why Squish?

Most local AI tools are bulky and slow to initialize. Squish AI projects are built with a **"Speed First"** mentality:

1.  **Sub-second Load Times:** No more waiting for weights to move to VRAM.
2.  **Apple Silicon Native:** Deeply optimized for Metal and unified memory architectures.
3.  **Developer Experience:** Simple APIs that don't require rewriting your entire codebase.

## 📈 Quick Start

To get started with our flagship compression tool:

```bash
pip install squishai
```

Then, replace your existing client:

```python
from squish import SquishClient

# Statistically identical to OpenAI/Ollama API
client = SquishClient()
response = client.chat.completions.create(
    model="llama3-8b-squish",
    messages=[{"role": "user", "content": "Squeeze this data!"}]
)
```

## 🤝 Community & Support

  * **Issues:** Please use the respective repository issue trackers for bugs and feature requests.
  * **Contributions:** We welcome PRs\! Please check the `CONTRIBUTING.md` in each repo.
  * **Location:** United States 🇺🇸

-----

*Built for speed. Optimized for accuracy. Squeezed for performance.*
