<h1 align="center">Darrel Wihandi</h1>

<p align="center">
  <b>Software Engineering @ University of Waterloo</b>
</p>

<p align="center">
  I build AI pipelines, compilers, ML tooling, and full-stack systems.
  <br/>
  Mostly working with <b>C++</b>, <b>Python</b>, <b>TypeScript</b>, and AI infrastructure.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/darrel-wihandi/">LinkedIn</a>
  ·
  <a href="mailto:dfwihand@uwaterloo.ca">Email</a>
  ·
  <a href="https://darrelfw321.github.io/Flux/">Flux Demo</a>
  ·
  <a href="https://www.aerix5.com/">Aerix</a>
</p>

---

## Featured

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/DarrelFW321/flux">Flux</a>
      </h3>
      <p>
        <b>C++17 · LLVM · WebAssembly · React · FastAPI</b>
      </p>
      <p>
        DSL compiler and live pipeline visualizer for numerical kernels.
      </p>
      <ul>
        <li>Designed a statically typed language for fixed-size arrays, <code>sum</code>, <code>dot</code>, and loops</li>
        <li>Built lexer → parser → type checker → MIR → LLVM native codegen</li>
        <li>Added MIR optimizations: constant folding, algebraic simplification, loop fusion, and DCE</li>
        <li>Built a WebAssembly frontend for tokens, AST, MIR, per-pass diffs, and LLVM IR</li>
      </ul>
      <p>
        <a href="https://darrelfw321.github.io/Flux/"><b>Try it in the browser →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://www.aerix5.com/">Aerix</a>
      </h3>
      <p>
        <b>FastAPI · Next.js · PostgreSQL · Playwright · Gemini</b>
      </p>
      <p>
        Prompt-to-API web scraping SaaS that turns a URL and plain-English prompt into a live structured JSON endpoint.
      </p>
      <ul>
        <li>Built self-healing extraction with cached navigation plans</li>
        <li>Added rediscovery when target websites change</li>
        <li>Validated extraction behavior across 1,000+ test endpoints</li>
      </ul>
      <p>
        <a href="https://www.aerix5.com/"><b>Check it out →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/DarrelFW321/KnowledgeQA">AI Knowledge Q&A</a>
      </h3>
      <p>
        <b>Python · LangChain · FastAPI · Next.js · Qdrant · Ollama</b>
      </p>
      <p>
        Full-stack RAG assistant with PDF/web ingestion and cited answers.
      </p>
      <ul>
        <li>Semantic chunking, vector search, and retrieval-aware prompting</li>
        <li>Llama-3 via Ollama with cross-encoder re-ranking</li>
        <li>Streaming chat UI with PDF source highlighting</li>
        <li>Docker Compose stack for local deployment</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/shader-slang/slang">Slang</a>
      </h3>
      <p>
        <b>Khronos / NVIDIA · GPU shading compiler</b>
      </p>
      <p>
        Contributor to the Slang GPU shading compiler across SPIR-V, HLSL, WGSL, and CUDA backends.
      </p>
      <ul>
        <li>Implemented texture intrinsic functions across compiler backends</li>
        <li>Added validation and unit tests for core compiler behavior</li>
      </ul>
    </td>
  </tr>
</table>

---

## More projects

<details>
<summary><b>RISC-V Web Emulator</b> — C++, WebAssembly, JavaScript</summary>

<br/>

Browser-based RISC-V emulator with live registers and memory.

- Step/run execution
- Modular embind bindings for CPU ↔ UI sync
- Used as a classroom learning tool

**Repo:** [github.com/DarrelFW321/riscv-emulator](https://github.com/DarrelFW321/riscv-emulator)

</details>

<details>
<summary><b>Pepper</b> — bytecode interpreter and compiler in C</summary>

<br/>

Small dynamic language implementation.

- Stack-based virtual machine
- Recursive-descent parser
- Bytecode emitter
- Closures and inheritance
- Mark-and-sweep garbage collection

**Repo:** [github.com/DarrelFW321/pepper](https://github.com/DarrelFW321/pepper)

</details>

<details>
<summary><b>Cook Buddy</b> — voice-powered cooking assistant on edge hardware</summary>

<br/>

**Python · Flask · Socket.IO · LoRA**

- Fine-tuned LLaMA-8B with Unsloth LoRA
- Reduced training VRAM by around 40%
- Built a low-latency Socket.IO bridge between Raspberry Pi and Flask server
- Added sensor-triggered prompts for step-by-step cooking assistance

**Repo:** [github.com/DarrelFW321/cook-buddy](https://github.com/DarrelFW321/cook-buddy)

</details>

---

## Stack

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/C-555555?style=flat&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
</p>

---
