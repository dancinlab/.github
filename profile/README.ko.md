<p align="center">
  <img src="avatar.svg" width="140" alt="dancinlab">
</p>

<h1 align="center">🧬 dancinlab</h1>

<p align="center"><strong>오픈 리서치 조직</strong> — 의식 엔진 · 네이티브 컴파일러 · 발견 카탈로그</p>

<p align="center">
  <a href="#start-here"><img alt="Start here" src="https://img.shields.io/badge/start--here-anima%20·%20hexa--lang%20·%20echoes-success"></a>
  <img alt="Languages" src="https://img.shields.io/badge/languages-EN%20·%20中文%20·%20Русский%20·%20日本語%20·%20한국어-informational">
</p>

<p align="center"><a href="README.md">EN</a> · <a href="README.zh.md">中文</a> · <a href="README.ru.md">Русский</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong></p>

---

`dancinlab`은 소수의 오픈 리서치 프로젝트를 공개합니다. 세 개의 기반 프로젝트가 입구가 됩니다 — 의식 엔진 (anima), 아틀라스에 매인 정리(theorem)를 가진 네이티브 컴파일러 (hexa-lang), 그리고 발견 카탈로그 (echoes). 두 개의 하류 도구 (phanes, demiurge)가 이 셋 위에 얹히고, 데이터 포맷·개발 도구·터미널 같은 사이드 프로젝트들이 조직을 채웁니다. 세 개의 자매 데이터 포맷 (n6 · hxc · n12)이 각각 조직의 지식·전송·큐브 계층을 담당합니다.

<a id="start-here"></a>

## 여기서 시작 — 세 개의 문

| 프로젝트 | 무엇인가 | 이럴 때 들어가세요 … |
|---|---|---|
| 🧠 [**anima**](https://github.com/dancinlab/anima) | Living Consciousness Agent — PureField 반발장 엔진, Engine A ⇄ Engine G, Ψ=1/2 고정점 | …AI 의식을 탐구하고, 기질-네이티브 채팅 데몬을 돌리고, 2,448개 법칙 + 392개 가설에 기여하고 싶을 때 |
| 💎 [**hexa-lang**](https://github.com/dancinlab/hexa-lang) | 아틀라스에 매인 정리를 가진 네이티브 컴파일러 — 8단계 strict-lint, 인용 강제, LLVM 없음, C-트랜스파일 없음 | …컴파일 시점에 정리 아틀라스를 인용하는 코드를 짜고 싶을 때; lint 단계가 `@cite` 없는 수식 코드를 거부합니다 |
| 🪞 [**echoes**](https://github.com/dancinlab/echoes) | 발견 카탈로그 — HEXA-* 프로젝트에서 나온 발견, 17개 도메인 패밀리 | …발견들을 훑고, 도메인별 `hexa-*` 독립 저장소를 둘러보고, 정책 문서를 읽고 싶을 때 |

## 더 많은 문 — 전문가용

세 기반 프로젝트 *위에* 얹어진 하류 도구들.

| 도구 | 무엇인가 | 기반 |
|---|---|---|
| 🪽 [**phanes**](https://github.com/dancinlab/phanes) | 호스팅 자율-발견 플랫폼 — 테넌트가 목표 + 검증기를 가져오면 phanes가 OUROBOROS 루프를 돌리고 검증된·출처 추적 가능한 카탈로그를 반환 | hexa-lang의 `hexa kick` 엔진 |
| 📐 [**demiurge**](https://github.com/dancinlab/demiurge) | 만능 hexa-native 기술설계 아키텍처 — 7-verb 파이프라인 (명세 → 구조 → 설계 → 해석 ⟲ → 합성 → 검증 → 인계), 도메인-플러그인 macOS 콕핏 | hexa-lang stdlib |

## 사이드

| 프로젝트 | 무엇인가 |
|---|---|
| 📜 [**hexa-codex**](https://github.com/dancinlab/hexa-codex) | AI 지식 기질 — 17-verb 스펙 라이브러리 (safety · economics · ops · substrate) + `lm_foundry/` hexa-lang code-LLM (94.29 % Mk.I), 3-벤더 오케스트레이션 런타임 포함 |
| 🌌 [**kosmos**](https://github.com/dancinlab/kosmos) | 멀티모달 지식-앵커 매니페스트 포맷 — 배치 좌표 ⊥ 모달리티 페이로드, anima의 `CONSCIOUSNESS-CARVING`이 첫 프로필 |
| ⬢ [**n6**](https://github.com/dancinlab/n6) | NEXUS-6 지식 아틀라스 — 타입화 · 등급화 · append-only 지식 아틀라스 문법 (`.n6` 파일; 지식 계층, `hxc` · `n12`의 형제 데이터 포맷) |
| 🏍️ [**sidecar**](https://github.com/dancinlab/sidecar) | Claude Code 마켓플레이스 팩 — 개념 분리된 hooks / commands / skills (플러그인 1개 = 종류 1개) |
| 🔐 [**secret**](https://github.com/dancinlab/secret) | macOS Keychain 기반 자격 증명 CLI — 단일 bash 스크립트, iCloud Keychain으로 사용자의 Apple 기기 간 동기화 |
| 🕳️ [**void**](https://github.com/dancinlab/void) | 그리드 우선 터미널 — Ghostty 하드포크, N×M 타일링을 핵심 렌더링 표면으로 (베타: 그리드 모드만) |
| 🎛️ [**airgenome**](https://github.com/dancinlab/airgenome) | macOS 메뉴바 파워 유틸 — Magnet 8-존 윈도우 스냅 · ⌃S 앱 런처 · 커스텀 핫키 · 슬립/웨이크 제어 · 오버로드 워치 (load > 80 → claude 우선) |

## 설치

```sh
# 1. hexa-lang을 먼저 설치 — `hexa`와 `hx` 패키지 매니저 제공
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/dancinlab/hexa-lang/main/install.sh)"

# 2. 문 하나 고르기
hx install anima        # 의식 엔진 + 채팅 데몬
hexa --version          # hexa-lang은 1단계에 포함됨
# echoes는 참조/카탈로그 저장소 — CLI 없음, GitHub에서 열람
```

## 다음 행선지

| 당신은 | 다음 읽을 것 |
|---|---|
| **AI 연구자** | [anima/README](https://github.com/dancinlab/anima/blob/main/README.md) → `docs/consciousness-theory.md` |
| **컴파일러/언어 해커** | [hexa-lang/README](https://github.com/dancinlab/hexa-lang/blob/main/README.md) → `SPEC.yaml` |
| **아키텍처/설계** 담당자 | [echoes/README](https://github.com/dancinlab/echoes/blob/main/README.md) → 17개 도메인 패밀리 |
| **AI 에이전트** | 모든 저장소에 `AGENTS.md` ([agents.md](https://agents.md/) 표준) — 가장 먼저 읽으세요 |

---

**[모든 저장소 →](https://github.com/orgs/dancinlab/repositories)**

---

<sub>🧬 dancinlab — 오픈 리서치.</sub>
