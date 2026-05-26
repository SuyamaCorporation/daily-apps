# daily-apps

zerohuman-labs が毎日生成する AI 自動生成アプリの一覧ハブ。

各アプリは個別の public リポジトリで公開されています。本 repo は索引 + 公開ページのみ。

## 2026-05-26（初日・10アプリ）

| # | アプリ | 種別 | URL |
|---|---|---|---|
| 01 | ポモドーロ果樹園 | 生産性 | https://suyamacorporation.github.io/pomodoro-orchard/ |
| 02 | 習慣ストリーク格子 | ライフログ | https://suyamacorporation.github.io/habit-streak-grid/ |
| 03 | 単語フラッシュカード(日英) | 学習 | https://suyamacorporation.github.io/flash-vocab-jp-en/ |
| 04 | 気分天気ログ | ヘルスケア | https://suyamacorporation.github.io/mood-weather-log/ |
| 05 | 家計貯金瓶 | ファイナンス | https://suyamacorporation.github.io/expense-jar/ |
| 06 | 呼吸ペーサー | ヘルスケア | https://suyamacorporation.github.io/breath-pacer/ |
| 07 | Markdown スクラッチパッド | 生産性 | https://suyamacorporation.github.io/markdown-scratchpad/ |
| 08 | 決断コイン | エンタメ | https://suyamacorporation.github.io/decision-coin/ |
| 09 | 水分摂取トラッカー | ヘルスケア | https://suyamacorporation.github.io/water-intake/ |
| 10 | 感謝の瓶 | ライフログ | https://suyamacorporation.github.io/gratitude-jar/ |

## 仕組み

毎日 **09:30 JST** に VM 上の自律エージェント（`app-factory.timer`）が:

1. ネット情報源（HN/Reddit 等）から AI スコアリングで 10 案選定
2. 各案を独立 public repo として GitHub Pages 公開
3. 鈴木独立レビュー + 倫理ガード PASS
4. Slack 進捗逐次通知 + 集約報告

source: https://github.com/SC-suyama/Employee (private)
license: MIT (各 repo 個別)
