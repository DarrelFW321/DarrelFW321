# Darrel Wihandi

**Software Engineering @ University of Waterloo**

I build AI Pipelines, compilers, ML tooling, and full-stack apps — mostly in **C++**, **Python**, and **TypeScript**.

<p align="center">
  <a href="https://darrelfw321.github.io/Flux/"><strong>Flux live demo</strong></a>
  ·
  <a href="https://www.linkedin.com/in/darrel-wihandi/">LinkedIn</a>
  ·
  <a href="mailto:dfwihand@uwaterloo.ca">Email</a>
</p>

---

## Open source

### [Slang](https://github.com/shader-slang/slang) · Khronos / NVIDIA

Contributor to the **Slang** GPU shading compiler (SPIR-V, HLSL, WGSL, CUDA).

- Implemented **texture intrinsic** functions across backends
- Added **validation / unit tests** for core compiler behavior

---

## Projects

### [Flux](https://github.com/DarrelFW321/flux) · C++17, LLVM, WebAssembly, React, FastAPI

DSL compiler + **live pipeline visualizer** for numerical kernels.

- Designed a statically typed language for fixed-size arrays, `sum` / `dot`, and loops
- Full pipeline: lexer → parser → type checker → **FluxIR (MIR)** → **LLVM** native codegen
- MIR optimizations: constant folding, algebraic simplification, **loop fusion**, DCE
- **WebAssembly** frontend for in-browser tokens, AST, MIR (with per-pass diffs), and LLVM IR
- **Benchmarks** page: fixed kernels (`dot`, `saxpy`, `relu`, `bigdot`) vs `gcc -O2` C and **NumPy**

**[Try it in the browser](https://darrelfw321.github.io/Flux/)**

---

### Aerix · FastAPI, Next.js, PostgreSQL, Playwright, Gemini

Prompt-to-API web scraping SaaS — turn a URL + plain-English prompt into a live structured JSON endpoint.

- Self-healing extraction: cached navigation plans, rediscovery when sites change (~5–10s per run)
- End-to-end validation across **1,000+** test endpoints

**[Go here to check it out](https://www.aerix5.com/)**

---

### AI Knowledge Q&A · Python, LangChain, FastAPI, Next.js, Qdrant, Ollama

Full-stack **RAG** assistant with PDF/web ingestion and cited answers.

- Semantic chunking, vector search (Qdrant), retrieval-aware prompting
- **Llama-3** via Ollama, cross-encoder re-ranking, streaming chat UI
- PDF viewer with inline source highlighting · **Docker Compose** stack

**Repo:** https://github.com/DarrelFW321/KnowledgeQA

---

### RISC-V Web Emulator · C++, WebAssembly, JavaScript

Browser-based **RISC-V** emulator with live registers and memory.

- Step/run execution, modular **embind** bindings for CPU ↔ UI sync
- Used as a classroom learning tool (course-endorsed)

*Repo:* https://github.com/DarrelFW321/riscv-emulator

---

### Pepper · C

Bytecode **interpreter + compiler** for a small dynamic language.

- Stack VM, closures, inheritance, **mark-and-sweep** GC
- Recursive-descent parser and bytecode emitter

**Repo:** https://github.com/DarrelFW321/pepper 

---

### Cook Buddy · Python, Flask, Socket.IO, LoRA

Voice-powered cooking assistant on edge hardware.

- Fine-tuned **LLaMA-8B** with Unsloth LoRA (~40% lower VRAM in training)
- Low-latency **Socket.IO** bridge (Raspberry Pi ↔ Flask server)
- Sensor-triggered prompts (heat, motion) for step-by-step guidance

**Repo:** https://github.com/DarrelFW321/cook-buddy 

---

## Stack I reach for often

**Languages:** Python · C/C++ · TypeScript · Java · Rust · WebAssembly  

**ML / data:** PyTorch · LangChain · RAG · OpenCV · LoRA fine-tuning  

**Systems / cloud:** LLVM · CMake · AWS · Kubernetes · Docker · FastAPI  

**Web:** React · Next.js · PostgreSQL

---

