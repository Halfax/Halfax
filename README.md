# Hi, I'm Halfax 👋

**Senior infrastructure & automation engineer.** By day: large-scale storage, cloud, and
end-to-end automation. Off the clock I bring the same discipline home to a self-hosted lab
where I own and control **every layer, silicon to reverse proxy** — and run it like production.

> *One idea runs through all of it: **never trust a confident claim — human or AI — until it's
> checked against what's real.** It's why my news engine corroborates instead of pronounces,
> why my story world pauses rather than invent, and how I catch an AI agent the moment it
> starts confidently making things up.*

🌐 **Full portfolio & write-ups → [www.guywithgames.com](https://www.guywithgames.com)** · **No cloud LLMs in the loop.**

---

### 📊 The lab, by the numbers
`6` hosts in a private WireGuard mesh · `120B` LLM on an integrated GPU · `3` models resident on one iGPU · `1` operating system from scratch · `0` cloud LLMs

---

### 🟢 Live right now — running on my own hardware, go poke at them
[![Halfax AI Chat](https://img.shields.io/badge/🧠_Halfax_AI_Chat-live-5aaeff?style=for-the-badge)](https://gamer.guywithgames.com/)
[![Heimdall Augur](https://img.shields.io/badge/📰_Heimdall_Augur-live-5aaeff?style=for-the-badge)](https://heimdall.guywithgames.com/)
[![Story Universe](https://img.shields.io/badge/🌍_Story_Universe-live-5aaeff?style=for-the-badge)](https://www.guywithgames.com/universe/)
[![Ashes of Grace](https://img.shields.io/badge/🎮_Ashes_of_Grace-play-5aaeff?style=for-the-badge)](https://grace.guywithgames.com/)
[![Fleet Live](https://img.shields.io/badge/📈_Fleet_Live-live-5aaeff?style=for-the-badge)](https://www.guywithgames.com/livelook/)
[![Bird Cam](https://img.shields.io/badge/🐦_Bird_Cam-live-5aaeff?style=for-the-badge)](https://cam.guywithgames.com/bird)

---

### 🤖 AI & Story
| Project | What it is |
|---|---|
| **Halfax AI Stack** | A private multi-model server running **GPT-OSS-120B on an integrated GPU** (AMD Strix Halo, 96 GiB UMA, Vulkan) — OpenAI-compatible, three models resident at once, ~78 GiB. No cloud. |
| [**Heimdall Augur**](https://github.com/Halfax/halfax-augur) | A news engine that **fact-checks itself**: reads ~50 sources, validates every quote against the source text, and confirms facts only when *differently-framed* outlets agree. Corroborates — never pronounces. |
| **The Story Universe** | An AI-driven world running unattended across three machines. Pauses the entire world before it will fabricate a single scene. |
| [**Halfax AI VSCode**](https://github.com/Halfax/halfax-ai-vscode) | A from-scratch IDE client — chat, agent, autocomplete — that talks to my own GPU and **resumes its agent mid-task after a crash**. |
| [**PictureAI**](https://github.com/Halfax/picture-ai) | Local image generation entirely on an integrated GPU — no CUDA, no cloud, no account (SDXL, Flux, SD3.5, Chroma). |

### 🛠️ Infrastructure & Operations
| Project | What it is |
|---|---|
| [**hal-web-mcp**](https://github.com/Halfax/hal-web-mcp) | An AI agent's web reach behind a real **SSRF wall** — DNS-rebinding defense, private-range blocking, 31 tests. |
| **Homelab MCP** | Natural-language control of the whole fleet — 40+ services checked concurrently in under two seconds. |
| **AI Collaboration Memory** | A single ADR-style rulebook (`DECISIONS.md`) that every AI coding agent obeys — **my rules outrank the model's defaults**, some enforced by hooks that block the wrong action before it runs. |
| **Recovery Plan + Drift Detector** | The whole stack rebuilds from compose files and encrypted secrets bundles in an afternoon — the drift guard recently caught a service silently dead for six months. |

### 🔐 Systems & Security
| Project | What it is |
|---|---|
| [**HalfaxOS**](https://github.com/Halfax/33rd) | A **64-bit capability-based OS written from scratch** in C and assembly — boots to a Ring-3 windowed desktop, a from-scratch TCP/IP stack, 52 syscalls, SMP bring-up. No borrowed kernel code. |
| [**Halfax KeySecrets**](https://github.com/Halfax/keysecrets-mcp) | A self-hosted, end-to-end encrypted vault — **hybrid post-quantum by default** (X25519 + ML-KEM-768); the server only ever sees ciphertext. |
| [**Halfax System Reporter**](https://github.com/Halfax/halfax_system_reporter) | A Windows **Ring-0 kernel driver** reading MSRs, PCI config space, and SMBus directly — the same access commercial telemetry tools use, from scratch. |
| **tor-recon** | Security recon that turns Tor into an attacker's-eye view of my own network — its first runs found a public dev server running as root over plaintext. |

### 🎮 Games
**Halfax Dungeons** (Godot 4 roguelike, 100 levels, with an autonomous *Borg* autoplayer) · **Ashes of Grace** (browser RPG, permadeath-as-mechanic) · **Skyhaven** (vanilla-JS Elder-Scrolls-like) · **Halcity** (Python/Pygame city-builder)

---

### 🧰 Built with
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![x86-64 asm](https://img.shields.io/badge/x86--64_asm-525252?style=flat-square)
![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

*Most projects are primary on a self-hosted GitLab and mirrored here.*

📫 **[www.guywithgames.com](https://www.guywithgames.com)** · [Discord](https://discord.gg/HrnWnTJsyz) · [Steam](https://steamcommunity.com/id/halfax/)
