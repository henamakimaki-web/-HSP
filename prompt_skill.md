# prompt_skill.md
# 画像プロンプトの固定ブロック・レイアウト集・文章の引き出し

---

## 運用方針

- **形式**：1枚文字込み画像（→ 動画化してリール投稿）
- **サイズ**：縦長（1080×1350）推奨、正方形（1080×1080）も可
- **制作ツール**：Canva / Adobe Express
- **背景画像が必要な場合**：以下の固定ブロックをAI画像生成に使用

---

## 画像生成プロンプト（フルテンプレート）

### 比率の選び方

| ステップ数 | 比率 |
|---|---|
| 1〜3ステップ | 3:4 |
| 4〜5ステップ | 4:5 |
| 6〜7ステップ | 2:3 |

> ⚠️ 比率はクロップも変更も禁止。縦長ポートレートを維持すること。

---

### プロンプトテンプレート（毎回このフォーマットで生成）

```
Create a single tall vertical Japanese recipe infographic poster, portrait orientation 
([ratio: 3:4 if 1–3 steps / 4:5 if 4–5 steps / 2:3 if 6–7 steps]). Do NOT crop or change the ratio.
This is a cute-but-clean Japanese "restaurant-style / quick recipe" infographic.
Combine PHOTOREALISTIC food photography (the dishes) with a flat cute graphic design layout.
ALL Japanese text listed below must be rendered accurately, sharply, and legibly inside the image.

━━━ OVERALL STYLE (fixed — keep the same every time) ━━━
- Warm cream / beige paper background (#f6ecd6) with subtle soft texture
- Cute Japanese SNS recipe-infographic aesthetic: rounded boxes, dashed borders, 
  red check-mark (☑) bullets, little hand-drawn accent strokes and sparkles
- Accent colors: hot pink (#f0567a), navy blue (#2a5a9e), leaf green (#3fae6a), gold
- Flat design for graphics, but all FOOD must look like real appetizing photographs
- Rounded sans-serif Japanese font (like Noto Sans JP), bold for titles
- No white gaps; every zone filled edge to edge, evenly balanced top to bottom

━━━ ZONE 1 — HEADER (top ~28%) ━━━
Left side (text stack):
  - Small pink ribbon banner: 「[キャッチ：例 レンジで4分・激安！ / 節約の神メシ！]」
  - Huge bold title: 「[料理名 前半]」(black) + very large 「[料理名 メイン]」([キーワードをpink、残りblack])
  - Navy rounded badge below: 「[サブ badge：例 超速ズボラ飯 / 節約の神メシ]」(white text)
Right side:
  - Large appetizing PHOTO of the finished dish: [完成品の見た目を具体的に描写。器・盛り付け・トッピング・湯気・色・質感まで]
    Realistic and mouth-watering, on a wooden table.

━━━ ZONE 2 — 材料 + ポイント (next ~22%) ━━━
BOX A (white, pink dashed border) header 「材料（[N]人分）」:
  ・[材料1]　[分量]
  ・[材料2]　[分量]
  ・[材料3]　[分量]
  ・[材料4]　[分量]
  ・[材料5以降を必要なだけ]　[分量]
BOX B (white, red border, light-bulb icon) header 「おいしくなるポイント」, with red ☑ checks:
  ☑ [コツ1]
  ☑ [コツ2]
  ☑ [コツ3]
  ☑ [コツ4]

━━━ ZONE 3 — 作り方 STEPS (middle ~30%) ━━━
Pink section label 「作り方（約[所要時間]）」on the left.
[N]個の REALISTIC photo cards arranged in a row (or two rows if 5+ steps), 
each with a pink circular number badge and a pink arrow (→) between them.
Caption under each card:
  ① photo of [工程1の様子] — 「[手順1の説明文]」
  ② photo of [工程2の様子] — 「[手順2の説明文]」
  ③ photo of [工程3の様子] — 「[手順3の説明文]」
  [… 必要な数だけ続ける。最後のステップ写真の近くに red hand-written stamp 「完成」を置く]

━━━ ZONE 4 — アレンジ / もう一品 (next ~14%) ━━━
Green section label 「[おすすめアレンジ / もう一つのオプション]」.
[アレンジが複数あれば 2–4個の mini photo cards を横並び / 1個なら wide card]:
  - 「[アレンジ名1]」([色] tab) → 「[ひとことコメント]」
  - 「[アレンジ名2]」([色] tab) → 「[ひとことコメント]」

━━━ ZONE 5 — FOOTER (bottom ~6%) ━━━
Navy bottom band with gold star sparkles + small food icons, center text:
  「[締めコピー]」([料理名をpinkで強調])
Small account handle bottom: 「@[アカウント名]」

━━━ COLOR PALETTE (fixed) ━━━
- Background: #f6ecd6 / Box white: #ffffff / Text: #333333
- Pink #f0567a / Navy #2a5a9e / Green #3fae6a / Gold sparkles
- Dashed borders pink/red

All Japanese text must be rendered accurately and clearly inside the image.
Food must look photorealistic and delicious; layout must look like a clean cute Japanese SNS recipe card.
```

---

## レイアウト集（役立ち型セット）

| 記号 | 名前 | 向いてるネタ | 使用頻度 |
|---|---|---|---|
| **L** | 時系列フロー | 手順・ステップ解説（標準レシピ） | ★★★ メイン |
| **J** | ランキング | 節約食材TOP5・おすすめ冷凍食材 | ★★ 週1〜2 |
| **K** | 原因→対策 | 「夜遅く帰った日の解決策」系 | ★★ 週1 |
| **M** | 比較表 | レンジ vs フライパン、食材A vs B | ★ 月2〜3 |
| **H** | ティア表 | 「時短食材の神レベル表」「コスパランク」 | ★ 月1〜2 |
| **G** | 漫画コマ | 「帰宅→5分後完成」の流れをコマ割りで | ★ 月1 |

---

## 文章の引き出し

### タイトル（大きい一言）パターン

**[調理法＋時間]＋[料理名]型**
- 「レンジで4分・濃厚バター醤油かまたまうどん」
- 「トースター5分・とろけるチーズ豆腐」
- 「レンジだけ・ふわとろ親子丼」

**[安さ強調]＋[料理名]型**
- 「1人前150円・やみつき塩昆布パスタ」
- 「材料費100円以下・もやしのナムル丼」
- 「200円で満腹・豆腐と卵のあんかけ丼」

**[手軽さ強調]＋[料理名]型**
- 「材料3つで完成・ごま油香る混ぜそば」
- 「洗い物ゼロ・レンジだけ麻婆豆腐」
- 「鍋も包丁もいらない・ツナトマトパスタ」

### サブタイトル（タグライン）パターン
- 「超速ズボラ飯」
- 「節約の神メシ」
- 「5分以内確定」
- 「火なし・鍋なし・洗い物なし」
- 「今夜これで乗り切れ」
- 「冷凍庫があれば作れる」

### ポイント・コツ文言（チェックマーク枠）
- 「〇〇すると△△になるのがポイント！」
- 「冷凍〇〇は5食パックが激安でおすすめ！」
- 「半熟状に絡めるのがコツ！」
- 「最後に黒こしょうを加えると締まる！」
- 「アツアツのうちにすぐ混ぜるのが鉄則」
- 「火を止めてから余熱でOK。過加熱注意」

### ステップ説明（1行・体言止め推奨）
- 「耐熱容器に入れてレンジ〇分」
- 「アツアツのうちに全材料を乗せる」
- 「全体を豪快に混ぜ合わせて完成」
- 「トースターに入れてチーズが溶けたら完成」
- 「水気を切って調味料と和えるだけ」

### フッターキャッチコピー（締め）パターン
- 「疲れた体に染み渡る、超速ごはん！」
- 「帰ったらすぐ食べられる。それだけでいい。」
- 「明日も使えるレシピ、保存しておいて。」
- 「手抜きじゃなくて、時短。」
- 「節約してても、うまいものは食べたい。」

### キャプション構成テンプレート

```
【レシピ名】（1行）

◆ 材料（〇人分）
・食材A…分量
・食材B…分量
（※省略して「詳細は画像をチェック！」でもOK）

◆ 作り方
① 手順1
② 手順2
③ 完成！

💡 コツ：〇〇すると△△になるよ！

📌 保存しておくと便利！
他のズボラ飯レシピも毎日投稿中 → フォローしてね

#時短レシピ #簡単レシピ #ズボラ飯 #節約レシピ #安うまレシピ #レンジレシピ #冷凍食材活用 #ひとり飯 #料理初心者 #[料理固有タグ]
```

---

## 死守ルール（command_center NGの再掲）

- 特定商品・メーカー名は一般化する（「5食入りパック」「コンビニにあるやつ」等）
- 「痩せる」「治る」「美肌になる」「免疫が上がる」等の効果断言は完全禁止
- 材料費300円超・時間15分超のレシピは投稿しない
- PR投稿は通常投稿と明確に区別し、必ず「#PR」を明記する
