# daily-apps

zerohuman-labs が毎日生成する AI 自動生成アプリの一覧ハブ。

各アプリは個別の public リポジトリで公開されています。本 repo は索引 + 公開ページのみ。

## 2026-05-26（初日・**20アプリ** Cycle1+Cycle2）

### Cycle 1（15:32-15:55 JST・実用系中心）

| # | アプリ | 種別 | URL |
|---|---|---|---|
| 01 | ポモドーロ果樹園 | 生産性 | https://mock.suyama-corporation.co.jp/pomodoro-orchard/ |
| 02 | 習慣ストリーク格子 | ライフログ | https://mock.suyama-corporation.co.jp/habit-streak-grid/ |
| 03 | 単語フラッシュカード(日英) | 学習 | https://mock.suyama-corporation.co.jp/flash-vocab-jp-en/ |
| 04 | 気分天気ログ | ヘルスケア | https://mock.suyama-corporation.co.jp/mood-weather-log/ |
| 05 | 家計貯金瓶 | ファイナンス | https://mock.suyama-corporation.co.jp/expense-jar/ |
| 06 | 呼吸ペーサー | ヘルスケア | https://mock.suyama-corporation.co.jp/breath-pacer/ |
| 07 | Markdownスクラッチパッド | 生産性 | https://mock.suyama-corporation.co.jp/markdown-scratchpad/ |
| 08 | 決断コイン | エンタメ | https://mock.suyama-corporation.co.jp/decision-coin/ |
| 09 | 水分摂取トラッカー | ヘルスケア | https://mock.suyama-corporation.co.jp/water-intake/ |
| 10 | 感謝の瓶 | ライフログ | https://mock.suyama-corporation.co.jp/gratitude-jar/ |

### Cycle 2（18:04-18:29 JST・遊び心+ビジュアル拡張）

| # | アプリ | 種別 | URL |
|---|---|---|---|
| 11 | タイピングテスト | 生産性 | https://mock.suyama-corporation.co.jp/typing-test/ |
| 12 | タイムスタンプ変換 | ツール | https://mock.suyama-corporation.co.jp/timestamp-converter/ |
| 13 | 正規表現テスター | ツール | https://mock.suyama-corporation.co.jp/regex-tester/ |
| 14 | 単位変換ツール | ツール | https://mock.suyama-corporation.co.jp/unit-converter/ |
| 15 | インターバルタバタ | ヘルスケア | https://mock.suyama-corporation.co.jp/interval-tabata/ |
| 16 | TRPGダイスロール | エンタメ | https://mock.suyama-corporation.co.jp/dice-roller-trpg/ |
| 17 | 決断ルーレット | エンタメ | https://mock.suyama-corporation.co.jp/roulette-decision/ |
| 18 | Lo-Fiサウンドボード | エンタメ | https://mock.suyama-corporation.co.jp/lofi-soundboard/ |
| 19 | パーティクル遊び場 | ビジュアル | https://mock.suyama-corporation.co.jp/particle-playground/ |
| 20 | 星座シミュレーター | ビジュアル | https://mock.suyama-corporation.co.jp/starfield-constellation/ |

## 仕組み

毎日 **09:30 JST** に VM 上の自律エージェント（`app-factory.timer`）が:

1. ネット情報源（HN/Reddit/Product Hunt/GitHub Trending）から AIスコアリングで案選定
2. 各案を独立 public repo として GitHub Pages 公開
3. 鈴木独立レビュー + 倫理ガード PASS
4. Slack 進捗逐次通知 + 集約報告

source: https://github.com/SC-suyama/Employee (private)  
license: MIT (各 repo 個別)  
仕様: zerohuman-labs daily app-factory v1.1
