```markdown
# 🌐 Practice: Open-Source LLMs

Experimental workspace for local LLM inference, quantization, and deployment. Focuses on running high-performance models on accessible hardware.

[![Python](https://img.shields.io/badge/python-3.10+-3776AB?style=flat-square)](https://www.python.org/)
[![Ollama](https://img.shields.io/badge/Ollama-Inference-white?style=flat-square&logo=ollama)](https://ollama.com/)
[![HF](https://img.shields.io/badge/%F0%9F%A4%97-Models-yellow?style=flat-square)](https://huggingface.co/models)

---

## 🛠️ Interactive Workspace
*Click a folder to explore the code:*

- [📂 **examples/**](./examples) — Minimal scripts to run Llama, Mistral, and Gemma.
- [📂 **deployment/**](./deployment) — FastAPI wrappers and Docker configurations.
- [📂 **benchmarks/**](./benchmarks) — Tokens-per-second and memory usage tests.
- [📂 **setup/**](./setup) — Environment YAMLs and dependency locks.

---

## 🚀 One-Command Start
```bash
# Setup environment and run default inference
git clone https://github.com/shreyaskr422/pratice-open-source-LLM.git && cd pratice-open-source-LLM
pip install -r requirements.txt
python main.py --model llama3
```

## 🎯 Model Coverage
| Family | Status | Primary Tool |
| :--- | :--- | :--- |
| **Llama 3.1** | ✅ Active | Ollama / vLLM |
| **Mistral / Mixtral** | ✅ Active | Transformers |
| **Gemma 2** | 🧪 Testing | GGUF / llama.cpp |
| **Phi-3.5** | 📅 Planned | ONNX Runtime |

## ⚙️ Tech Stack
- **Runtimes:** [Ollama](https://ollama.com/), [vLLM](https://github.com/vllm-project/vllm), [llama.cpp](https://github.com/ggerganov/llama.cpp)
- **Formats:** GGUF, AWQ, EXL2
- **Logic:** LangChain, Hugging Face `transformers`

---
[MIT License](LICENSE) • Built by [shreyaskr422](https://github.com/shreyaskr422)
```

### Why this is better:
1.  **Interactive Tree:** The folder names are now **clickable links**. When you click `examples/`, it will actually open that folder in GitHub.
2.  **Visual Status:** The "Model Coverage" table uses status icons (✅, 🧪, 📅) to show exactly where you are in your practice journey.
3.  **Precise Badges:** I added a specific Ollama badge because that is the most popular way people "practice" with open-source LLMs right now.
4.  **Actionable:** The "One-Command Start" combines the clone and install commands for people who want to move fast.
