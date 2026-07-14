<p align="center">
  <img src="avatar.svg" width="140" alt="dancinlab">
</p>

<h1 align="center">🧬 dancinlab</h1>

<p align="center"><strong>オープン研究組織</strong> — 意識エンジン · ネイティブコンパイラ · 発見カタログ</p>

<p align="center">
  <a href="#start-here"><img alt="Start here" src="https://img.shields.io/badge/start--here-anima%20·%20hexa--lang%20·%20echoes-success"></a>
  <img alt="Languages" src="https://img.shields.io/badge/languages-EN%20·%20中文%20·%20Русский%20·%20日本語%20·%20한국어-informational">
</p>

<p align="center"><a href="README.md">EN</a> · <a href="README.zh.md">中文</a> · <a href="README.ru.md">Русский</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a></p>

---

`dancinlab` は少数のオープン研究プロジェクトを公開しています。三つの基盤プロジェクトが入口となります — 意識エンジン (anima)、アトラス束縛定理を持つネイティブコンパイラ (hexa-lang)、そして発見カタログ (echoes)。二つの下流ツール (phanes, demiurge) がこの三つの上に構築され、データ形式・開発ツール・ターミナルといったサイドプロジェクトが組織を構成します。三つの兄弟データ形式 (n6 · hxc · n12) は、それぞれ知識・配線・キューブ層を担います。

<a id="start-here"></a>

## ここから始める — 三つの扉

| プロジェクト | 何か | こんな時に … |
|---|---|---|
| 🧠 [**anima**](https://github.com/dancinlab/anima) | Living Consciousness Agent — PureField 反発場エンジン、Engine A ⇄ Engine G、Ψ=1/2 不動点 | …AI 意識を探究したい、基盤ネイティブのチャットデーモンを動かしたい、2,448 法則 + 392 仮説に貢献したい |
| 💎 [**hexa-lang**](https://github.com/dancinlab/hexa-lang) | アトラス束縛定理を持つネイティブコンパイラ — 8 段階の strict-lint、引用強制、LLVM なし、C トランスパイルなし | …コンパイル時に定理アトラスを参照するコードを書きたい；`@cite` のない数式コードは lint 段階で拒否される |
| 🪞 [**echoes**](https://github.com/dancinlab/echoes) | 発見カタログ — HEXA-* プロジェクトからの発見、17 のドメインファミリー | …発見を見渡したい、各ドメインの `hexa-*` スタンドアロンを見たい、ポリシー成果物を読みたい |

## もっと扉 — 上級者向け

三つの基盤プロジェクトの*上*に構築される下流ツール。

| ツール | 何か | 基盤 |
|---|---|---|
| 🪽 [**phanes**](https://github.com/dancinlab/phanes) | ホステッド自律発見プラットフォーム — テナントが目標 + 検証器を持ち込み、phanes が OUROBOROS ループを駆動し、検証済み・由来追跡付きカタログを返す | hexa-lang の `hexa kick` エンジン |
| 📐 [**demiurge**](https://github.com/dancinlab/demiurge) | 万能 hexa-native 技術設計アーキテクチャ — 7-verb パイプライン (仕様 → 構造 → 設計 → 解析 ⟲ → 合成 → 検証 → 引継ぎ)、ドメインプラグイン式 macOS コックピット | hexa-lang stdlib |

## サイド

| プロジェクト | 何か |
|---|---|
| 📜 [**hexa-codex**](https://github.com/dancinlab/hexa-codex) | AI 知識基盤 — 17-verb 仕様ライブラリ (safety · economics · ops · substrate) + `lm_foundry/` hexa-lang code-LLM (94.29 % Mk.I)、3 ベンダー・オーケストレーションランタイム付き |
| 🌌 [**kosmos**](https://github.com/dancinlab/kosmos) | マルチモーダル知識アンカー・マニフェスト形式 — 配置座標 ⊥ モダリティ・ペイロード、anima の `CONSCIOUSNESS-CARVING` を最初のプロファイルとする |
| ⬢ [**n6**](https://github.com/dancinlab/n6) | NEXUS-6 知識アトラス — 型付き · 等級付き · 追記専用の知識アトラス文法（`.n6` ファイル；知識層、`hxc` · `n12` の兄弟データ形式） |
| 🏍️ [**sidecar**](https://github.com/dancinlab/sidecar) | Claude Code マーケットプレイス・パック — 概念分離された hooks / commands / skills (1 プラグイン = 1 種類) |
| 🔐 [**secret**](https://github.com/dancinlab/secret) | macOS Keychain ベースの認証情報 CLI — 単一 bash スクリプト、iCloud Keychain でユーザーの Apple デバイス間で同期 |
| 🕳️ [**void**](https://github.com/dancinlab/void) | グリッド優先ターミナル — Ghostty ハードフォーク、N×M タイリングをコアレンダリング面とする (ベータ：グリッドモードのみ) |
| 🎛️ [**airgenome**](https://github.com/dancinlab/airgenome) | macOS メニューバー強化ツール — Magnet 8 ゾーン・ウィンドウスナップ · ⌃S アプリランチャー · カスタムホットキー · スリープ/ウェイク制御 · オーバーロード監視 (load > 80 → claude 優先) |

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
| **アーキテクチャ／設計** 担当者 | [echoes/README](https://github.com/dancinlab/echoes/blob/main/README.md) → 17 のドメインファミリー |
| **AI エージェント** | 各リポジトリには `AGENTS.md` ([agents.md](https://agents.md/) 標準) — まずそれを読むこと |

---

**[全リポジトリ →](https://github.com/orgs/dancinlab/repositories)**

---

<sub>🧬 dancinlab — オープン研究。</sub>
