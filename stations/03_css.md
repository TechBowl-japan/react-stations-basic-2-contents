---
id: 162
order: 3
title: CSSを書き換えよう
confirmation_method: meeting
design_contents: https://www.figma.com/file/agx0kBamVoQOFCSu3wstht/TODO_app?node-id=0%3A1
skill_id: 28
abilities:
  - 86
clear_conditions:
  - id: 295
    contents: CSS-in-JS または CSS Modules で CSS を書き換えている
---

### 問題文

現在の TODO アプリでは、 CSS　フレームワーク等を使用していない、通常の CSS によるスタイリングが行われています。

開発を進める中で、通常の CSS でのスタイリングでは、 グローバルな名前空間によるクラス名の衝突リスクがあり、コンポーネント指向な開発との相性が悪いと考えました。

そんな中、 React に関連してスタイリングについて調べていると、

React では他にも様々なスタイリングの適用方法があることを知りました。

今回、CSS-in-JS、CSS Modules についてピックアップし、メリットやデメリットを調べ、

どちらか一方を導入してみることとしました。


### やること

- CSS-in-JS または CSS Modules を導入する
- 既存の CSS を上記のいずれかに書き換える

### ヒントとなる検索

「CSS-in-JS」
「emotion」
