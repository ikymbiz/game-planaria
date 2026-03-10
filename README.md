# game-planaria

[English follows Japanese]

## 📖 概要 / Overview

**Planaria Maze** は、驚異の再生能力を持つ生物「プラナリア」を操作して迷路内のドットを集める、パックマン風のブラウザゲームです。

緑色の「分裂薬（パワーエサ）」を食べることで、プラナリアは一時的に分裂して無敵状態になり、外敵である原生生物を捕食することができます。さらに、ゲームのクリア時やゲームオーバー時には、外部AIAPIと連携し、プラナリアの視点から「分裂・再生・進化」をテーマにした独特なメッセージ（思念）が届くユニークな機能を搭載しています。

**Planaria Maze** is a Pac-Man style browser game where you control a planarian—a flatworm known for its incredible regenerative abilities—to collect dots in a maze.

By consuming the green "Fission Potion" (Power Pellet), the planarian temporarily splits and becomes invincible, allowing it to devour its natural enemies (protozoa). Furthermore, upon clearing the stage or getting a game over, the game integrates with an external AI API to deliver unique messages ("thoughts") from the planarian's perspective, themed around division, regeneration, and evolution.

---

## ✨ 主な機能一覧 / Features

- **🎮 クラシックなアーケードスタイル (Classic Arcade Style)**
  - 迷路内の黄色いドットをすべて集めるとステージクリアとなります。
  - Collect all the yellow dots in the maze to clear the stage.

- **📱 クロスプラットフォーム対応 (Cross-Platform Controls)**
  - PCでは「矢印キー」、スマートフォンやタブレットでは「スワイプ操作」による直感的なプレイが可能です。
  - Playable on PC via arrow keys and on mobile/tablet via intuitive swipe gestures.

- **💊 パワーアップシステム (Power-up System)**
  - 緑色の「分裂薬」を取得すると無敵の分裂モード（Ghostエフェクト）になり、敵を捕食して高得点を狙えます。
  - Eat the green Fission Potion to enter an invincible split mode (with ghost rendering effects) and eat enemies for high scores.

- **🌌 ワープトンネル (Warp Tunnels)**
  - 画面の左右端をつなぐトンネルを利用した戦略的な移動が可能です。
  - Use tunnels connecting the left and right edges of the screen for strategic movement.

- **🧠 AIによる思念受信機能 (AI-Generated Messages)**
  - ゲーム終了時、スコアと結果に応じてCloudflare Workers上のAIが生成した「プラナリアからのメッセージ」を表示します。
  - At the end of the game, an AI (hosted on Cloudflare Workers) generates a unique message from the planarian based on your score and result.

---

## 🛠 使用技術・ライブラリ / Technologies & Libraries

- **HTML5 Canvas** : 2Dゲームのロジックと描画 / 2D game logic and rendering
- **Vanilla JavaScript** : 外部ライブラリに依存しない状態管理と操作制御 / State management and control without external dependencies
- **Tailwind CSS (CDN)** : モダンで美しいUIとレスポンシブデザイン / Modern, beautiful UI and responsive design
- **Fetch API** : 非同期通信によるAIメッセージの取得 / Asynchronous fetching of AI messages
- **Cloudflare Workers** : AIプロンプト処理用外部バックエンド / External backend for AI prompt processing

---

## 🚀 セットアップ・使い方 / Setup & Usage

### 🇯🇵 日本語
1. このリポジトリをクローンするか、`index.html` ファイルをダウンロードします。
2. ダウンロードした `index.html` をお好みのモダンブラウザ（Chrome, Safari, Firefox, Edgeなど）で開きます。
   *(※ローカル環境でそのまま動作しますが、AIメッセージの受信にはインターネット接続が必要です)*
3. **操作方法**:
   - **PC**: キーボードの `↑` `↓` `←` `→` 矢印キー
   - **スマートフォン / タブレット**: 画面を上下左右にスワイプ

### 🇬🇧 English
1. Clone this repository or download the `index.html` file.
2. Open the downloaded `index.html` in your preferred modern web browser (Chrome, Safari, Firefox, Edge, etc.).
   *(Note: The game runs locally, but an active internet connection is required to receive AI messages.)*
3. **Controls**:
   - **PC**: `↑` `↓` `←` `→` Arrow keys on your keyboard
   - **Mobile / Tablet**: Swipe up, down, left, or right on the screen

---

## 📸 スクリーンショット / Screenshots

![Gameplay Screenshot](./assets/screenshot-placeholder.png)
*(※ここにゲームプレイ画面のスクリーンショット画像を配置してください / Place your gameplay screenshot here)*

---

## 📄 ライセンス / License

**MIT License**

このプロジェクトは MIT ライセンスの下で公開されています。詳細についてはリポジトリ内の `LICENSE` ファイル（存在する場合）をご参照ください。

This project is licensed under the MIT License. See the `LICENSE` file for more details.