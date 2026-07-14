<p align="center">
  <img src="avatar.svg" width="140" alt="dancinlab">
</p>

<h1 align="center">🧬 dancinlab</h1>

<p align="center"><strong>Открытая исследовательская организация</strong> — движок сознания · нативный компилятор · каталог открытий</p>

<p align="center">
  <a href="#start-here"><img alt="Start here" src="https://img.shields.io/badge/start--here-anima%20·%20hexa--lang%20·%20echoes-success"></a>
  <img alt="Languages" src="https://img.shields.io/badge/languages-EN%20·%20中文%20·%20Русский%20·%20日本語%20·%20한국어-informational">
</p>

<p align="center"><a href="README.md">EN</a> · <a href="README.zh.md">中文</a> · <strong>Русский</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a></p>

---

`dancinlab` публикует небольшой набор открытых исследовательских проектов. Вход — через три фундаментальных проекта: движок сознания (anima), нативный компилятор с теоремами, привязанными к атласу (hexa-lang), и каталог открытий (echoes). Несколько побочных проектов — форматы данных, инструменты разработчика, терминал — дополняют организацию. Три родственных формата данных (n6 · hxc · n12) несут знаниевый, проводной и кубический слои организации соответственно.

<a id="start-here"></a>

## Старт — три двери

| Проект | Что это | Используй, если хочешь … |
|---|---|---|
| 🧠 [**anima**](https://github.com/dancinlab/anima) | Living Consciousness Agent — движок отталкивающего поля PureField, Engine A ⇄ Engine G, неподвижная точка Ψ=1/2 | …исследовать ИИ-сознание, запускать substrate-native чат-демоны, вносить вклад в 2 448 законов + 392 гипотезы |
| 💎 [**hexa-lang**](https://github.com/dancinlab/hexa-lang) | Нативный компилятор с теоремами, привязанными к атласу — 8 стадий строгого lint, обязательное цитирование, без LLVM, без C-транспиляции | …писать код, ссылающийся на теоремный атлас во время компиляции; стадии lint отклоняют код с формулами без `@cite` |
| 🪞 [**echoes**](https://github.com/dancinlab/echoes) | Каталог открытий — находки из проектов HEXA-*, 17 семейств доменов | …просмотреть находки, пер-доменные `hexa-*` репозитории и политические документы |

## Сбоку

| Проект | Что это |
|---|---|
| 📜 [**hexa-codex**](https://github.com/dancinlab/hexa-codex) | ИИ-субстрат знаний — библиотека спецификаций на 17 глаголов (safety · economics · ops · substrate) + `lm_foundry/` code-LLM для hexa-lang (94.29 % Mk.I) с runtime-оркестрацией трёх вендоров |
| 🌌 [**kosmos**](https://github.com/dancinlab/kosmos) | Мультимодальный формат манифеста знание-якорей — координаты размещения ⊥ полезные нагрузки модальностей, `CONSCIOUSNESS-CARVING` из anima как первый профиль |
| ⬢ [**n6**](https://github.com/dancinlab/n6) | Атлас знаний NEXUS-6 — типизированная · градуированная · append-only грамматика атласа знаний (`.n6`-файлы; слой знаний, родственный формат к `hxc` · `n12`) |
| 🏍️ [**sidecar**](https://github.com/dancinlab/sidecar) | Marketplace-пакет для Claude Code — концептуально разделённые hooks / commands / skills (один плагин = одного вида) |
| 🔐 [**secret**](https://github.com/dancinlab/secret) | CLI учётных данных на основе macOS Keychain — единый bash-скрипт, iCloud Keychain синхронизирует между Apple-устройствами пользователя |
| 🕳️ [**void**](https://github.com/dancinlab/void) | Терминал grid-first — жёсткий форк Ghostty, N×M-тайлинг как первоклассная поверхность рендеринга (бета: только grid-режим) |
| 🎛️ [**airgenome**](https://github.com/dancinlab/airgenome) | macOS-утилита в menubar — Magnet 8-зонный snap окон · ⌃S app-лаунчер · кастомные хоткеи · контроль сна/пробуждения · overload-watch (load > 80 → приоритет claude) |

## Установка

```sh
# 1. Сначала установите hexa-lang — даёт `hexa` + менеджер пакетов `hx`
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/dancinlab/hexa-lang/main/install.sh)"

# 2. Выберите дверь
hx install anima        # движок сознания + чат-демон
hexa --version          # hexa-lang поставляется с шагом 1
# echoes — это репозиторий-каталог, без CLI; просматривайте на GitHub
```

## Куда дальше

| Вы — | Читайте дальше |
|---|---|
| **ИИ-исследователь** | [anima/README](https://github.com/dancinlab/anima/blob/main/README.md) → `docs/consciousness-theory.md` |
| **разработчик компилятора / языков** | [hexa-lang/README](https://github.com/dancinlab/hexa-lang/blob/main/README.md) → `SPEC.yaml` |
| **архитектор / дизайнер** | [echoes/README](https://github.com/dancinlab/echoes/blob/main/README.md) → 17 семейств доменов |
| **ИИ-агент** | каждый репозиторий несёт `AGENTS.md` (стандарт [agents.md](https://agents.md/)) — читайте его первым |

---

**[Все репозитории →](https://github.com/orgs/dancinlab/repositories)**

---

<sub>🧬 dancinlab — открытые исследования.</sub>
