# 🎮 Echoes of Arcana
**2.5D Fantasy JRPG | Unreal Engine 5 Gameplay / Systems Programming Portfolio Project**

---

## Portfolio Use Notice

This repository is shared publicly for **portfolio and recruitment purposes only**.

The source code and project structure are provided to demonstrate **gameplay programming ability, system design, and Unreal Engine architecture**.

Please **do not copy, reuse, redistribute, or submit this work as your own** for academic, professional, or recruitment purposes.

© Ramzel Suarez

---

# Overview (English)

**Echoes of Arcana** is a 2.5D fantasy JRPG developed as a personal **Unreal Engine 5 gameplay programming portfolio project**.

Inspired by classic HD-2D JRPGs, the project focuses on **turn-based battle systems, party mechanics, and modular UI architecture**.

The goal of this project is to demonstrate:

- gameplay system design
- structured Blueprint architecture
- scalable UI and combat logic
- extensible RPG system implementation

The project emphasizes **system design and programming structure rather than large-scale content production.**

---

# 概要（日本語）

**『Echoes of Arcana（秘術の残響）』**は、Unreal Engine 5を使用して制作した  
**ゲームシステム実装を中心としたポートフォリオ用2.5DファンタジーJRPG**です。

HD-2DスタイルのクラシックJRPGに影響を受け、主に以下のシステムを中心に開発しています。

- ターン制バトルシステム  
- パーティ制御ロジック  
- UIフロー管理  
- ステート駆動型ゲームロジック  

本作品は**コンテンツ量よりもゲームシステム設計と実装力を示すこと**を目的としたデモプロジェクトです。

---

# Story / ストーリー（Demo Scope）

## English

In the frontier settlement of **Ironvale Camp**, strange magical disturbances have begun to emerge from the nearby **Ironvale Forest**.

Creatures once native to the woods now behave unpredictably, drawn toward faint echoes of arcane energy.

**Cassel**, a wandering swordsman, prepares to investigate the forest.

During his stay in Ironvale Camp, he encounters:

- **Seris (Paladin)** — monitoring abnormal magical activity
- **Aria (Mage)** — researching arcane fluctuations
- **Dorin (Hunter)** — tracking aggressive beasts

Recognizing a shared objective, the four form a temporary party and venture into **Ironvale Forest** to uncover the source of the disturbance.

*Current demo scope: Ironvale Camp → Ironvale Forest exploration and turn-based battle system implementation.*

---

## 日本語

辺境の集落 **アイアンヴェイル・キャンプ** では、  
近隣の **アイアンヴェイルの森** から不穏な魔力反応が確認されています。

森に棲む魔物たちは、微弱な秘術の残響に引き寄せられるように  
異常な行動を見せ始めました。

旅の剣士 **カセル** は森の調査に向かおうとします。

キャンプ滞在中に彼は次の三人と出会います。

- **聖騎士セリス**（魔力異常の監視任務）
- **魔法使いアリア**（秘術変動の研究）
- **ハンタードリン**（凶暴化した魔物の追跡）

目的を同じくする四人はパーティを結成し、  
森の異変の原因を探るため調査へ向かいます。

※本デモでは **キャンプ → 森 → バトルシステム** の流れを中心に構成されています。

---

# Playable Characters / プレイアブルキャラクター

⚔️ **Cassel – Warrior**  
Frontline attacker with high HP and physical damage.

🔮 **Aria – Mage**  
Uses MP-based offensive magic.

🛡️ **Seris – Paladin**  
Defensive support and healing abilities.

🏹 **Dorin – Hunter**  
Fast ranged attacker with high mobility.

---

# Core Features / 主な特徴

- ターン制JRPGバトルシステム
- HP / MP 計算および管理ロジック
- 最大4人パーティバトル
- デモ用エネミー3体
- ステート駆動型バトルフロー
- モジュラーUI構造（Widgetベース）
- 2.5D表現（3D空間内2Dスプライト）

---

# Technical Implementation / 技術実装

### Engine

- Unreal Engine 5
- Blueprint-driven gameplay architecture
- C++ gameplay programming (currently expanding)

### Gameplay Systems

- Turn-based battle state machine
- Character stat management system
- Party-based battle control
- Enemy encounter system

### UI Systems

- Modular Widget-based menu system
- Battle command UI
- Menu navigation logic

### Rendering Style

- 2D sprite characters placed in 3D environments
- HD-2D inspired visual composition

The architecture emphasizes **clean gameplay system separation and extensibility**, allowing future expansion into new areas, enemies, and narrative content.

---

## Controls / 操作方法

### Keyboard
- Movement (ASDF) — Character movement  
- Enter — Confirm / Select  
- Esc — Cancel / Back
- E  — Interact

### Input & UI Navigation
- Integrated Unreal Engine UI Navigation plugin  
- Configured unified input handling for keyboard, mouse, and controller  
- Ensured consistent UI navigation and interaction across all input methods  

※操作方法は開発中に変更される可能性があります。

---

# Development Purpose / 開発目的

This project demonstrates:

- RPG battle system implementation
- gameplay state management
- UI flow control
- party-based combat logic
- system-driven gameplay architecture

Content scope is intentionally limited to focus on **system design and implementation quality.**

---

# Author / 制作者

**Ramzel Suarez**

Gameplay / Systems Programming  
Unreal Engine Portfolio Project

---

# License / ライセンス

This project is a **portfolio demonstration project** and is not intended for commercial distribution in its current form.

All third-party assets are used in accordance with their respective licenses.

---

# Asset Credits

## Cobra Code – Unreal Engine JRPG Masterclass Assets

Party characters, enemies, sprites, pixel grass, and related materials are used under the **Cobra Code Asset License v1.0**.

These assets are permitted for use in free and commercial projects.

All rights remain with Cobra Code.

License file included in the project directory.

---

## Chicken NPC Sprite

Chicken sprite asset by **AVS / amicu (itch.io)**.

License terms:

- Free for commercial and non-commercial use
- May be modified
- May NOT be redistributed as a standalone asset
- Not permitted for AI training or NFT usage

Original creator credit:
AVS / amicu
