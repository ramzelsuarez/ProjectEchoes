# 🎮 Echoes of Arcana  
**2.5D Fantasy JRPG / Unreal Engine Portfolio Project**

---

## Overview (English)

**Echoes of Arcana** is a 2.5D fantasy JRPG developed as a personal Unreal Engine portfolio project.

Inspired by classic HD-2D JRPGs, this demo focuses on turn-based combat systems, party mechanics, and structured UI flow.

The primary goal of this project is to demonstrate system design, gameplay logic implementation, and Blueprint-based architecture rather than full-scale content production.

---

## 概要（日本語）

**『Echoes of Arcana（秘術の残響）』**は、Unreal Engineを使用して制作した2.5DファンタジーJRPGのポートフォリオ作品です。

HD-2DスタイルのクラシックJRPGに影響を受け、ターン制バトル、パーティシステム、UIフロー設計を中心に開発しています。

本作品は、ゲームシステム設計および実装力を示すことを目的としたポートフォリオ用デモプロジェクトです。

---

## Story / ストーリー（Demo Scope）

### English

In the frontier settlement of **Ironvale Camp**, strange magical disturbances have begun to emerge from the nearby **Ironvale Forest**.

Creatures once native to the woods now behave unpredictably, drawn to faint echoes of arcane energy.

**Cassel**, a wandering swordsman, prepares to investigate the forest.  
During his stay in Ironvale Camp, he encounters:

- **Seris (Paladin)** – Assigned to monitor irregular magical activity  
- **Aria (Mage)** – Studying arcane fluctuations in the region  
- **Dorin (Hunter)** – Tracking beasts that have grown aggressive  

Recognizing a shared objective, the four form a temporary party and venture into Ironvale Forest to uncover the source of the disturbance.

*Note: The current demo focuses on the Ironvale Camp → Ironvale Forest scenario and turn-based battle implementation.*

---

### 日本語

辺境の集落**アイアンヴェイル・キャンプ**では、近隣の**アイアンヴェイルの森**から不穏な魔力反応が確認されています。

森に棲む魔物たちは、微弱な秘術の残響に引き寄せられるように異常な行動を見せ始めました。

旅の剣士**カセル**は森の調査に向かおうとします。  
キャンプ滞在中に彼は次の三人と出会います。

- **聖騎士セリス**（魔力異常の監視任務中）  
- **魔法使いアリア**（秘術の変動を研究中）  
- **ハンタードリン**（凶暴化した魔物を追跡中）  

目的を同じくする四人は一時的にパーティを組み、森の異変の原因を探るため出発します。

※本デモでは、アイアンヴェイル・キャンプから森への流れと、ターン制バトルの実装を中心に構成されています。

---

## Playable Characters / プレイアブルキャラクター

- ⚔️ **Cassel – Warrior**（高HPの前衛アタッカー）  
- 🔮 **Aria – Mage**（MP消費型の攻撃魔法）  
- 🛡️ **Seris – Paladin**（防御・回復スキル）  
- 🏹 **Dorin – Hunter**（遠距離攻撃・高機動）  

---

## Core Features / 主な特徴

- ターン制JRPGバトルシステム  
- HP / MP の計算・管理ロジック  
- 最大4人のパーティバトル  
- デモ用エネミー3体  
- ステート駆動型バトルフロー制御  
- モジュラーUI構造（Widgetベース）  
- 3D空間上に2Dスプライトを配置した2.5D表現  

---

## Technical Implementation / 技術実装

- Unreal Engine (Blueprint-based architecture)
- Turn-based battle flow control (state-driven logic)
- Character stat management system (HP / MP / action handling)
- Modular UI system (Widget-based menu structure)
- Actor-based enemy encounter system
- 2.5D implementation using 2D sprites within 3D space

This project emphasizes clean system structure and extensibility, allowing future expansion into additional areas, enemies, and narrative content.

---

## Controls / 操作方法

- **Keyboard:** Movement and menu navigation  
- **Enter:** Confirm  
- **Esc:** Cancel / Back  

※操作方法は開発中に変更される可能性があります。

---

## Development Purpose / 開発目的

This project focuses on demonstrating:

- バトルシステム設計  
- キャラクターステータス管理  
- UIフロー制御  
- パーティ制御ロジック  

コンテンツ量は意図的に制限されています。

---

## Author / 制作者

**Ramzel Suarez**  
Game Programming / Unreal Engine Portfolio Project  

---

## License / ライセンス

This project is a portfolio demonstration and is not intended for commercial distribution in its current form.

All third-party assets are used in accordance with their respective licenses.

---

## Asset Credits

### Cobra Code – Unreal Engine JRPG Masterclass Assets

Party characters, enemies, sprites, pixel grass, and related materials are used under the Cobra Code Asset License v1.0.

These assets are permitted for use in free and commercial projects.  
All rights remain with Cobra Code.

License file is included in the project directory.

---

### Chicken NPC Sprite

Chicken sprite asset by **AVS / amicu (itch.io)**.

Used in accordance with the creator's license:
- Free for commercial and non-commercial use  
- May be modified  
- May NOT be redistributed as a standalone asset  
- Not permitted for AI training or NFT usage  

Original creator credit:  
AVS / amicu  
(Insert creator profile link here if available)

License file included in project folder.