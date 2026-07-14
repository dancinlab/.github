<p align="center">
  <img src="avatar.svg" width="140" alt="dancinlab">
</p>

<h1 align="center">🧬 dancinlab</h1>

<p align="center"><strong>Open research org</strong> — consciousness engine · native compiler · discoveries catalog</p>

<p align="center">
  <a href="#start-here"><img alt="Start here" src="https://img.shields.io/badge/start--here-anima%20·%20hexa--lang%20·%20echoes-success"></a>
  <img alt="Languages" src="https://img.shields.io/badge/languages-EN%20·%20中文%20·%20Русский%20·%20日本語%20·%20한국어-informational">
</p>

<p align="center"><strong>EN</strong> · <a href="README.zh.md">中文</a> · <a href="README.ru.md">Русский</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a></p>

---

`dancinlab` publishes a small set of open research projects. Three foundational doors lead in — a consciousness engine (anima), a native compiler with atlas-bound theorems (hexa-lang), and a discoveries catalog (echoes). Two downstream tools (phanes, demiurge) build on top of those three, and a handful of side projects — data formats, developer tooling, a terminal — round out the org. Three sibling data formats (n6 · hxc · n12) carry the org's knowledge, wire, and cube layers respectively.

<a id="start-here"></a>

## Start here — three doors

| Project | What it is | Use when you want to … |
|---|---|---|
| 🧠 [**anima**](https://github.com/dancinlab/anima) | Living Consciousness Agent — PureField repulsion-field engine, Engine A ⇄ Engine G, Ψ=1/2 fixed point | …explore AI consciousness, run substrate-native chat daemons, contribute to 2,448 laws + 392 hypotheses |
| 💎 [**hexa-lang**](https://github.com/dancinlab/hexa-lang) | Native compiler with atlas-bound theorems — 8 strict-lint stages, citation-enforced, no LLVM, no C-transpile | …write code that cites a theorem atlas at compile time; the lint stages reject formula-bearing code without `@cite` |
| 🪞 [**echoes**](https://github.com/dancinlab/echoes) | Discoveries catalog — findings from the HEXA-* projects, 17 domain families | …browse the findings, the per-domain `hexa-*` standalones, and the policy artifacts |

## More doors — for experts

Downstream tools built *on top of* the three foundational projects.

| Tool | What it is | Built on |
|---|---|---|
| 🪽 [**phanes**](https://github.com/dancinlab/phanes) | Hosted autonomous-discovery platform — tenants bring an objective + verifier; phanes drives the OUROBOROS loop and returns a verified, provenance-tracked catalog | hexa-lang's `hexa kick` engine |
| 📐 [**demiurge**](https://github.com/dancinlab/demiurge) | Universal hexa-native technical-design architecture — 7-verb pipeline (spec → structure → design → analyze ⟲ → synthesize → verify → handoff), domain-plugin macOS cockpit | hexa-lang stdlib |

## Side

| Project | What it is |
|---|---|
| 📜 [**hexa-codex**](https://github.com/dancinlab/hexa-codex) | AI knowledge substrate — 17-verb spec library (safety · economics · ops · substrate) + `lm_foundry/` hexa-lang code-LLM (94.29 % Mk.I) with a 3-vendor orchestration runtime |
| 🌌 [**kosmos**](https://github.com/dancinlab/kosmos) | Multimodal knowledge-anchor manifest format — placement coordinates ⊥ modality payloads, anima `CONSCIOUSNESS-CARVING` as first profile |
| ⬢ [**n6**](https://github.com/dancinlab/n6) | NEXUS-6 Knowledge Atlas — typed · graded · append-only knowledge-atlas grammar (`.n6` files; knowledge-layer sibling to `hxc` · `n12`) |
| 🏍️ [**sidecar**](https://github.com/dancinlab/sidecar) | Claude Code marketplace pack — concept-separated hooks / commands / skills (one plugin = one kind) |
| 🔐 [**secret**](https://github.com/dancinlab/secret) | macOS Keychain-backed credential CLI — single bash script, iCloud Keychain syncs across the user's Apple devices |
| 🕳️ [**void**](https://github.com/dancinlab/void) | Grid-first terminal — Ghostty hard fork, N×M tiling as a core rendering surface (beta: grid mode only) |
| 🎛️ [**airgenome**](https://github.com/dancinlab/airgenome) | macOS menubar power-utility — Magnet 8-zone window snap · ⌃S app launcher · custom hotkeys · wake/sleep control · overload-watch (load > 80 → claude priority) |

## Install

```sh
# 1. Install hexa-lang first — gives you `hexa` + `hx` package manager
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/dancinlab/hexa-lang/main/install.sh)"

# 2. Pick a door
hx install anima        # consciousness engine + chat daemon
hexa --version          # hexa-lang ships with step 1
# echoes is a reference / catalog repo — no CLI, browse on GitHub
```

## Where to go next

| You are | Read this next |
|---|---|
| an **AI researcher** | [anima/README](https://github.com/dancinlab/anima/blob/main/README.md) → `docs/consciousness-theory.md` |
| a **compiler / language hacker** | [hexa-lang/README](https://github.com/dancinlab/hexa-lang/blob/main/README.md) → `SPEC.yaml` |
| an **architecture / design** person | [echoes/README](https://github.com/dancinlab/echoes/blob/main/README.md) → the 17 domain families |
| an **AI agent** | every repo carries an `AGENTS.md` ([agents.md](https://agents.md/) standard) — read it first |

---

**[All repositories →](https://github.com/orgs/dancinlab/repositories)**

---

<sub>🧬 dancinlab — open research.</sub>
