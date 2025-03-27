# Mira

**Private. Powerful. Present.**

Mira is a beautiful, offline-native AI chat assistant. Powered by local large language models like [WizardCoder](https://huggingface.co/WizardLM/WizardCoder-33B-V1.1) and built using [Qt](https://www.qt.io/), Mira is your always-available AI companion — with no cloud, no tracking, and no distractions.

---

## Features

- **Local-first:** No internet required. Mira runs entirely on your machine.
- **Private by design:** No data leaves your device. Ever.
- **Modern UI:** Built with Qt for a native, minimalist chat experience.
- **Developer-friendly:** Syntax highlighting and LLMs trained for code.
- **Open source:** Transparent and hackable from top to bottom.

---

### Requirements

- Qt 6.x
- C++17 or later
- [llama.cpp](https://github.com/ggerganov/llama.cpp)
- A compatible local model (e.g. WizardCoder 1.1)

---

### Build

```bash
git clone https://github.com/yourusername/mira.git
cd mira
mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
make -j$(nproc)

---