# HARBOR97

> Market Stress Defense Overlay for Structural Risk Monitoring

<p align="center">
  <img src="https://github.com/user-attachments/assets/74ca218a-2668-4310-b074-822ae65da4da" width="680">
</p>


## Overview

HARBOR97 is a defensive market stress overlay designed to monitor structural instability conditions that may degrade the risk characteristics of existing trading strategies.

The system does not attempt to predict market direction, generate alpha, optimize entries/exits, or replace existing execution infrastructure.

Its primary role is to:

- monitor structural stress conditions
- classify market states
- provide defensive positioning recommendations
- reduce operator fatigue through selective alerting
- maintain operational auditability

HARBOR97 is designed as an external defensive overlay that can operate independently from existing alpha engines and portfolio logic.

---

## Philosophy

HARBOR97 is built around the idea that many operational failures occur not because alpha disappears instantly, but because market structure changes faster than existing strategies can adapt.

The system focuses on structural market stress, abnormal market behavior, and operational risk conditions.

The objective is not prediction.

The objective is operational survivability.

---
<p align="center">
  <img width="680" alt="Overlay Positioning" src="https://github.com/user-attachments/assets/b4098242-0413-4cde-9ee8-809784c21c86" />
</p>


## What HARBOR97 Does

HARBOR97 continuously monitors market conditions and classifies structural stress states.

The system provides:

- market state classification
- defensive action recommendations
- defensive posture guidance
- operational monitoring
- audit-ready state logs

Typical operational outputs include:

- Watch / Caution states
- Risk-Off states
- Defensive posture states
- positioning reduction recommendations
- state normalization notifications

The system prioritizes actionable alerts over continuous notifications.

---

## What HARBOR97 Does NOT Do

HARBOR97 does NOT:

- predict market direction
- generate alpha signals
- optimize execution
- control trade execution
- provide discretionary trading advice
- replace portfolio management systems
- replace institutional risk governance

Final execution authority always remains with the operator or institution.

HARBOR97 is intended as a defensive telemetry and advisory overlay.

---

## Operational Design Principles

### Stateful Monitoring

HARBOR97 emphasizes state continuity rather than isolated signal generation.

### Layered Defensive Actions

The system differentiates between:

- current market state
- triggered defensive action
- recommended positioning posture

This structure reduces unnecessary repeated alerts while preserving defensive continuity.

### Alert Selectivity

The system is intentionally designed to minimize operator fatigue.

Notifications are primarily issued when:

- operationally relevant changes occur
- defensive posture updates are required
- normalization conditions are observed

### Auditability

HARBOR97 maintains structured logs and ledger-based records for operational review and replay analysis.

---

## False Positive Philosophy

HARBOR97 is intentionally asymmetric.

The system is designed to tolerate limited false positives in exchange for reducing catastrophic structural misses during unstable market conditions.

---

## Responsibility Boundary

HARBOR97 provides:

- structural stress classification
- defensive action recommendations
- operational telemetry

HARBOR97 does not directly execute trades.

Portfolio construction, execution logic, and final operational decisions remain under the responsibility of the operator or institution.

---

## Development Status

Current public version:

- HARBOR97 Ver1
- index-level structural monitoring prototype
- validation workflow implemented
- operational ledger system implemented
- recovery-state handling implemented
- alert prioritization implemented

Future development may include:

- regime persistence extensions
- cross-asset monitoring
- operational replay visualization
- institutional deployment layers
- broader defensive infrastructure applications

---

## Disclosure Policy

HARBOR97 intentionally abstracts:

- internal feature construction
- exact thresholds
- weighting logic
- score composition
- proprietary signal generation methods

Public documentation focuses on operational philosophy and system behavior rather than implementation details.

---

## Operational Example

Example of operational defensive overlay notifications generated during live monitoring conditions.

<img width="420" alt="14919" src="https://github.com/user-attachments/assets/49726e53-60c8-42e6-b2a7-76144ec5cfdc" />


---

## Examples

Illustrative operational abstractions are available in the `/examples` directory.

---

## License / Disclaimer

HARBOR97 is a research and operational monitoring project.

This repository does not provide investment advice or portfolio management services.

The public materials in this repository are provided for research, monitoring, and system design discussion purposes only.

Commercial and institutional deployment may require separate agreements.

All rights reserved unless explicitly stated otherwise.

---

## Additional Documents

- [PHILOSOPHY.md](./PHILOSOPHY.md)
- [CHANGELOG.md](./CHANGELOG.md)
- [Operational Examples](./examples/sample_operational_states.md)
- [profile.md](./profile.md)

-------------------------------------------------------------------------------------------------------------------

# HARBOR97 (Japanese ver.)

市場構造ストレス監視用 Defensive Overlay

---

## 概要

HARBOR97 は、市場構造側のストレス状態を継続監視し、既存戦略のリスク特性が劣化し始める市場環境を段階的に分類する、防御専用Overlayです。

本システムは以下を目的としません。

- 相場方向予測
- アルファ生成
- 執行最適化
- 自動売買制御

HARBOR97 は、既存アルファ戦略とは独立した、防御側の補助レイヤーとして設計されています。

---

## 主な特徴

- structural stress monitoring
- stateful market classification
- defensive positioning recommendation
- selective alerting
- operational audit logging

通知は「本当に必要な状態変化」を優先する設計となっています。

---

## 責任範囲

HARBOR97 は市場状態分類および防御推奨を提供します。

最終的な売買判断・執行責任は、運用者または運用機関側にあります。

HARBOR97 自体は execution engine ではなく、risk telemetry / advisory overlay として位置づけられます。

---

## 設計思想

HARBOR97 は短期予測よりも、以下を重視しています。

- structural survivability
- operational continuity
- stress detection
- operator fatigue reduction
- auditability

また、false positive を完全排除するよりも、不安定市場における catastrophic structural miss の回避を優先しています。

---

## 現在の状態

- Ver1 operational prototype
- index-level monitoring
- validation workflow
- recovery-state handling
- ledger-based audit structure

---

## 注意事項

本リポジトリは研究・監視用途であり、投資助言を目的とするものではありません。

内部ロジック、閾値、重み付け、signal construction の詳細は公開対象外です。

---

## Additional Documents

- [PHILOSOPHY.md](./PHILOSOPHY.md)
- [CHANGELOG.md](./CHANGELOG.md)
- [Operational Examples](./examples/sample_operational_states.md)
- [profile.md](./profile.md)
