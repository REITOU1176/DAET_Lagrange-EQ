# Lagrange EQ

**Lagrange EQ** is a free beta Windows VST3 parametric equalizer plug-in by **DAET**  
**Digital Audio Engineering Tools**.

It uses large-window bidirectional IIR processing to provide a high-quality, linear-phase-like EQ workflow while keeping the familiar feel of a modern parametric EQ.

Current version: **v0.9.0 beta**

## Features

- 8-band parametric EQ
- Bell, High Shelf, Low Shelf, High Pass, and Low Pass filters
- Per-band Stereo / Mid / Side / Left / Right targeting
- x2 oversampling mode
- Quality modes for internal processing window length
- Pre / Post spectrum analyzer
- I/O meters and output gain
- A/B comparison and copy
- Undo / Redo
- User preset save/load
- Piano grid for pitch-based frequency editing
- Windows VST3 support

## Download

Download the latest ZIP package from the GitHub Releases page.

The ZIP package contains:

- `Lagrange EQ.vst3`
- `README.md`
- `README.txt`

## Installation

1. Close your DAW.
2. Copy `Lagrange EQ.vst3` to:

   ```text
   C:\Program Files\Common Files\VST3\
   ```

3. Start your DAW and rescan VST3 plug-ins if needed.

## User Presets

User presets are stored separately from DAW project state.

The plug-in creates the preset folder when needed:

```text
Documents/DAET/Lagrange EQ/Presets/
```

## Notes

- Lagrange EQ uses high-latency processing.
- A DAW with plug-in delay compensation is recommended.
- It is best suited for mixing, mastering, sound design, and precise EQ work.
- It is not intended as a zero-latency live monitoring EQ.
- Oversampling and higher Quality settings may increase CPU usage and/or latency.
- The analyzer is visual-only and does not change the audio signal.

## Beta Terms

By using this beta version, you agree to the following terms:

1. This software is provided as-is, without warranty of any kind.
2. DAET and the developer are not responsible for data loss, project issues, system problems, audio damage, or any other damages caused by use of this software.
3. This beta version may contain bugs, unstable behavior, or changes that affect compatibility with future versions.
4. Redistribution is allowed only as the original unmodified ZIP package, unless explicit permission is given by the developer.
5. Reverse engineering, resale, rebranding, or claiming authorship of this software is not permitted.
6. Factory presets are not included in this beta. User presets created by users remain their own work.
7. This beta version is intended for personal evaluation, testing, and feedback.

Copyright (c) 2026 DAET / Digital Audio Engineering Tools. All rights reserved.

---

# Lagrange EQ 日本語

**Lagrange EQ** は、**DAET**  
**Digital Audio Engineering Tools** による無料 beta 版の Windows VST3 パラメトリックEQプラグインです。

大きな処理窓を使った双方向IIR処理により、一般的な片方向IIR EQよりも位相変化を抑えた、リニアフェイズ寄りの高品質なEQワークフローを目指しています。

現在のバージョン: **v0.9.0 beta**

## 主な機能

- 8バンド パラメトリックEQ
- Bell / High Shelf / Low Shelf / High Pass / Low Pass
- バンドごとの Stereo / Mid / Side / Left / Right 処理
- x2 Oversampling
- 内部処理窓長を切り替える Quality モード
- Pre / Post スペクトラムアナライザー
- I/Oメーター、Output Gain
- A/B比較、Copy
- Undo / Redo
- ユーザープリセット保存/読み込み
- 音程ベースで周波数を操作できる Piano Grid
- Windows VST3対応

## ダウンロード

GitHub Releases から最新の ZIP パッケージをダウンロードしてください。

ZIP パッケージには以下が含まれます:

- `Lagrange EQ.vst3`
- `README.md`
- `README.txt`

## インストール方法

1. DAWを終了します。
2. `Lagrange EQ.vst3` を以下へコピーします:

   ```text
   C:\Program Files\Common Files\VST3\
   ```

3. DAWを起動し、必要に応じてVST3プラグインを再スキャンしてください。

## ユーザープリセット

ユーザープリセットはDAWプロジェクト保存とは別に管理されます。

必要に応じて、プラグインが以下のフォルダを作成します:

```text
Documents/DAET/Lagrange EQ/Presets/
```

## 注意事項

- Lagrange EQ は高レイテンシー処理を使用します。
- DAW側のプラグインディレイ補正が有効な環境での使用を推奨します。
- ミックス、マスタリング、音作り、精密なEQ処理に向いています。
- ゼロレイテンシーのライブモニター用途向けではありません。
- Oversampling や高い Quality 設定では、CPU負荷やレイテンシーが増える場合があります。
- Analyzer表示は視覚表示のみで、音声信号自体は変更しません。

## Beta版 利用規約

この beta 版を使用することで、以下の条件に同意したものとします。

1. 本ソフトウェアは現状のまま提供され、いかなる保証もありません。
2. 本ソフトウェアの使用によって発生したデータ損失、プロジェクトの問題、システムの問題、音声上の損害、その他一切の損害について、DAETおよび開発者は責任を負いません。
3. この beta 版には、不具合、不安定な挙動、将来バージョンとの互換性に影響する変更が含まれる可能性があります。
4. 再配布は、開発者から明示的な許可がない限り、改変されていない元のZIPパッケージのまま行ってください。
5. リバースエンジニアリング、再販売、別ブランド化、自作と偽る行為は禁止します。
6. この beta 版にはファクトリープリセットは含まれません。ユーザーが作成したプリセットは、そのユーザー自身の制作物です。
7. この beta 版は、個人での評価、テスト、フィードバックを目的としています。

Copyright (c) 2026 DAET / Digital Audio Engineering Tools. All rights reserved.
