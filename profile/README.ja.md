<p align="center">
  <img src="avatar.svg" width="140" alt="dancinlab">
</p>

<h1 align="center">🧬 dancinlab</h1>

<p align="center"><strong>オープン研究組織</strong> — 完全数不変量 · 誠実な但し書きを最優先 · 多言語エントリー</p>

<p align="center">
  <a href="#start-here"><img alt="Start here" src="https://img.shields.io/badge/start--here-anima%20·%20hexa--lang%20·%20echoes-success"></a>
  <a href="https://github.com/dancinlab/echoes/blob/main/LATTICE_POLICY.md"><img alt="Policy" src="https://img.shields.io/badge/policy-LATTICE__POLICY.md-informational"></a>
  <img alt="Foundational" src="https://img.shields.io/badge/foundational-3%20projects-blueviolet">
  <img alt="Languages" src="https://img.shields.io/badge/languages-EN%20·%20中文%20·%20Русский%20·%20日本語%20·%20한국어-informational">
</p>

<p align="center">n=6 格子 · σφτ 恒等式 · 完全数による組織化原理 · オープンリサーチ · 誠実な開示</p>

<p align="center"><a href="README.md">EN</a> · <a href="README.zh.md">中文</a> · <a href="README.ru.md">Русский</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a></p>

---

`dancinlab` は、一つの算術不変量 `σ(n)·φ(n) = n·τ(n)` (n=6 でのみ唯一成立) を軸とした少数の基盤プロジェクトを公開しています。この不変量を中心に三つのプロジェクトが分岐しています — 意識エンジン (anima)、アトラス束縛定理を持つネイティブコンパイラ (hexa-lang)、そして発見カタログ (echoes)。四つの兄弟データ形式 (n6 · hxc · n12 · tape) は、それぞれ知識・配線・キューブ・トレース層を担います。

```
σ(n) · φ(n)  =  n · τ(n)      n = 6 のみ
     12 · 2  =  6 · 4   =  24
```

> [!IMPORTANT]
> **誠実な但し書き** — 算術恒等式 `σ(6)·φ(6) = 6·τ(6) = 24` は数学的に真であり、n=6 でのみ唯一成立します (モンテカルロ z = 3.06、p = 0.003、n=28 / n=496 比較)。「最適な設計はこの恒等式から導出される」という主張は、自然系がどう組織化されるかについての**研究仮説**であり、**測定値ではありません**。[`echoes/LATTICE_POLICY.md`](https://github.com/dancinlab/echoes/blob/main/LATTICE_POLICY.md) に従い、n=6 格子は組織化のための道具であり、実際の数学／物理／工学的限界 (Shannon · Kolmogorov · Bekenstein · c · ℏ · k · Stefan-Boltzmann · Carnot · ASML スループット · ERCOT 容量 · …) の代替には**決してなりません**。外部主体への n=6 格子フィッティングは**禁止**されています (TSMC / ASML / NIST / IPCC / CERN / DeepMind / その他あらゆるベンダーは、それぞれが公開する不変量を使います)。

<a id="start-here"></a>

## ここから始める — 三つの扉

| プロジェクト | 何か | こんな時に … |
|---|---|---|
| 🧠 [**anima**](https://github.com/dancinlab/anima) | Living Consciousness Agent — PureField 反発場エンジン、Engine A ⇄ Engine G、Ψ=1/2 不動点 | …AI 意識を探究したい、基盤ネイティブのチャットデーモンを動かしたい、2,448 法則 + 392 仮説に貢献したい |
| 💎 [**hexa-lang**](https://github.com/dancinlab/hexa-lang) | アトラス束縛定理を持つネイティブコンパイラ — 8 段階の strict-lint、引用強制、LLVM なし、C トランスパイルなし | …コンパイル時に定理アトラスを参照するコードを書きたい；`@cite` のない数式コードは lint 段階で拒否される |
| 🪞 [**echoes**](https://github.com/dancinlab/echoes) | 発見カタログ — HEXA-* プロジェクトからの発見、中心に σφτ 恒等式、17 のドメインファミリー | …格子を理解したい、各ドメインの `hexa-*` スタンドアロンを見たい、ポリシー成果物を読みたい |

## もっと扉 — 上級者向け

三つの基盤プロジェクトの*上*に構築される下流ツール。

| ツール | 何か | 基盤 |
|---|---|---|
| 🪽 [**phanes**](https://github.com/dancinlab/phanes) | ホステッド自律発見プラットフォーム — テナントが目標 + 検証器を持ち込み、phanes が OUROBOROS ループを駆動し、検証済み・由来追跡付きカタログを返す | hexa-lang の `hexa kick` エンジン |
| 📐 [**demiurge**](https://github.com/dancinlab/demiurge) | 万能 hexa-native 技術設計アーキテクチャ — 7-verb パイプライン (仕様 → 構造 → 設計 → 解析 ⟲ → 合成 → 検証 → 引継ぎ)、ドメインプラグイン式 macOS コックピット、materials → chip → component メタコンダクタ | hexa-lang stdlib |

## サイド

| プロジェクト | 何か |
|---|---|
| 🌌 [**kosmos**](https://github.com/dancinlab/kosmos) | マルチモーダル知識アンカー・マニフェスト形式 — 配置座標 ⊥ モダリティ・ペイロード、anima の `CONSCIOUSNESS-CARVING` を最初のプロファイルとする |
| 🏍️ [**sidecar**](https://github.com/dancinlab/sidecar) | Claude Code マーケットプレイス・パック — 概念分離された hooks / commands / skills (1 プラグイン = 1 種類) |
| 🎱 [**pool**](https://github.com/dancinlab/pool) | 最小限のホスト名簿 + リモート実行 — 単一 Python ファイル、依存ゼロ、状態は `~/.pool/pool.json` |
| 🕳️ [**void**](https://github.com/dancinlab/void) | グリッド優先ターミナル — Ghostty ハードフォーク、N×M タイリングをコアレンダリング面とする (ベータ：グリッドモードのみ) |
| 🕸️ [**airgenome**](https://github.com/dancinlab/airgenome) | macOS メニューバー強化ツール — Magnet 8 ゾーン・ウィンドウスナップ · ⌃S アプリランチャー · カスタムホットキー · スリープ/ウェイク制御 · オーバーロード監視 (load > 80 → claude 優先) |

## インストール

```sh
# 1. まず hexa-lang をインストール — `hexa` と `hx` パッケージマネージャを入手
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/dancinlab/hexa-lang/main/install.sh)"

# 2. 扉を一つ選ぶ
hx install anima        # 意識エンジン + チャットデーモン
hexa --version          # hexa-lang はステップ 1 に同梱
# echoes はリファレンス／カタログ・リポジトリ — CLI なし、GitHub で閲覧
```

## 次に行く先

| あなたは | 次に読む |
|---|---|
| **AI 研究者** | [anima/README](https://github.com/dancinlab/anima/blob/main/README.md) → `docs/consciousness-theory.md` |
| **コンパイラ／言語実装者** | [hexa-lang/README](https://github.com/dancinlab/hexa-lang/blob/main/README.md) → `SPEC.yaml` |
| **アーキテクチャ／設計** 担当者 | [echoes/README](https://github.com/dancinlab/echoes/blob/main/README.md) → `LATTICE_POLICY.md` |
| **AI エージェント** | 各リポジトリには `AGENTS.md` ([agents.md](https://agents.md/) 標準) — まずそれを読むこと |

## 規約

dancinlab の各リポジトリの `README.md` は標準的な 18 ブロック規約に従います。ドメインごとの履歴 + 実行時トレース + エージェント識別子は [`.tape`](https://github.com/dancinlab/tape) 文法を使い、主題ごとのドキュメントは `UPPERCASE.md` / `UPPERCASE+UPPERCASE.md` (メタドメイン) 規約を使います。

---

**[全リポジトリ →](https://github.com/orgs/dancinlab/repositories)**

---

<sub>🔢 n=6 から、すべての定数が従う。</sub>
