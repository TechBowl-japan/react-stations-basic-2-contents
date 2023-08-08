---
id: 163
order: 4
title: タスクに期限を設定できるようにしよう
confirmation_method: meeting
design_contents: https://www.figma.com/file/agx0kBamVoQOFCSu3wstht/TODO_app?node-id=0%3A1
skill_id: 28
abilities:
  - 61
  - 68
  - 93
  - 69
clear_conditions:
  - id: 296
    contents: タスクに期限日時の設定・編集ができる
  - id: 297
    contents: タスク表示に期限日時も一緒に表示されている
  - id: 298
    contents: 期限日時とは別に残り日時を表示されている
---

# 問題文

現在 Todo アプリにはタスクに期限を設定する機能がありません。新機能の一つとして期限を設定できるようにしましょう。

## ※注意

- limit のフォーマット「YYYY-MM-DDTHH:MM:SSZ」に気を付けてください。
  - 例）2022-07-15T11:11:11Z

## やること

- タスク作成時に期限日時を設定できるようにする
- タスク編集時に期限日時を編集できるようにする
- タスク表示に期限日時も一緒に表示させる
- 期限日時とは別に残り日時を表示させる
- ここでの日時情報は分単位まで考慮すること

## ヒントとなる検索

「js Date」
