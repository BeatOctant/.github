## BeatOctant

A Beat Saber map recommender. It suggests the next BeatSaver maps to play from your own play history. Recommendations are computed on your PC, and your play history is not sent anywhere.

Beat Saber で次に遊ぶマップを、自分のプレイの記録から推薦する MOD とツールです。BeatSaver のマップから作った推薦用のデータ（DB）を手元の PC で使い、推薦の計算もすべて手元で行います。プレイの記録はどこにも送りません。

> **Dev build (unstable).** Things may break between versions. Windows is not tested yet.
>
> **Dev 版（不安定版）です。** 版が変わると壊れることがあります。Windows での動作はまだ確かめていません。

### Start here / はじめかた

1. Read **Getting Started** for install steps and known issues.
   インストールの手順と既知の問題は **はじめかた** にあります。
   [English](https://github.com/BeatOctant/OctantSpecs/blob/main/GettingStarted_en.md) · [日本語](https://github.com/BeatOctant/OctantSpecs/blob/main/GettingStarted_ja.md)
2. Download from Releases. / Releases から取ります。

| What / 取るもの | Where / 場所 |
| --- | --- |
| OctantPath (Beat Saber mod, `OctantPath.dll`) and OctantPath Desktop<br>OctantPath（ゲームの中の MOD）と OctantPath Desktop（ゲームの外で推薦を見る。任意） | [OctantPath Releases](https://github.com/BeatOctant/OctantPath/releases/latest) |
| OctantCompass (recommendation server) and the DB (`.full.tar`)<br>OctantCompass（ゲームの外で動く推薦サーバー）と DB | [OctantCompass Releases](https://github.com/BeatOctant/OctantCompass/releases/latest) |

Bug reports and ideas: [Discord](https://discord.gg/gx6k3nKZBe) (`#bug-reports`, `#feedback-ideas`). Issues and pull requests are not accepted on GitHub.

バグの報告と案は [Discord の BeatOctant サーバー](https://discord.gg/gx6k3nKZBe)へ（バグは `#bug-reports`、案は `#feedback-ideas`。日本語でも英語でも）。GitHub の Issue と pull request は受けていません。

### Repositories / リポジトリ

| Repository | Role | 役割 |
| --- | --- | --- |
| [OctantPath](https://github.com/BeatOctant/OctantPath) | Beat Saber mod (PC) and OctantPath Desktop | PC 版の MOD と OctantPath Desktop |
| [OctantCompass](https://github.com/BeatOctant/OctantCompass) | Recommendation server that runs outside the game | ゲームの外で動く推薦サーバー |
| [OctantSpecs](https://github.com/BeatOctant/OctantSpecs) | Specs, decisions and Getting Started | 仕様、決めたこと、はじめかた |
| [OctantPathAndroid](https://github.com/BeatOctant/OctantPathAndroid) | Quest mod. Very early, no prebuilt releases | Quest 版の MOD。極めて初期で、ビルド済みの配布はなし |
| [OctantHarvest](https://github.com/BeatOctant/OctantHarvest) | Collects BeatSaver maps and builds the DB | BeatSaver からマップを集め、DB を作る |
| [OctantVector](https://github.com/BeatOctant/OctantVector) · [OctantVectorPlugins](https://github.com/BeatOctant/OctantVectorPlugins) | Feature extraction and recommendation math | 音・譜面・カバーを数値にし、推薦を計算する |

The repositories here are history-free mirrors of the working repositories.
ここにあるリポジトリは、作業用のリポジトリから履歴を除いて写したものです。

---

BeatOctant is written mostly with AI coding agents (Anthropic's Claude). The maintainer decides what to build and reviews every change. It does not generate maps; it recommends existing maps from BeatSaver. ([How it is made](https://github.com/BeatOctant/OctantSpecs#作り方ai-の使い方))

コードと文書は主に AI のコーディングエージェント（Anthropic の Claude）で書いています。何を作るかはメンテナーが決め、変更はすべてメンテナーが確かめてから取り込みます。BeatOctant はマップを作りません。BeatSaver にあるマップを推薦するだけです。（[作り方（AI の使い方）](https://github.com/BeatOctant/OctantSpecs#作り方ai-の使い方)）

Unofficial fan project. Not affiliated with, endorsed by, or sponsored by Beat Games or Meta. Beat Saber and Meta Quest are trademarks of their respective owners.

Beat Games・Meta とは関係のない、ファンが作った非公式の MOD とツールです。Beat Saber と Meta Quest は各社の商標です。
