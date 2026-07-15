# ぽんず工房 サイト全体生成デザイン v1

作成日: 2026-07-16
生成方法: OpenAI Image Generation（built-in）

## 進め方

1. サイト全体のデスクトップ完成イメージを画像生成する。
2. デスクトップ案を参照し、スマホ版の完成イメージを画像生成する。
3. 2枚に共通する構図・密度・余白・配色をHTML/CSSへ実装する。
4. 生成画像そのものを画面背景として使わず、文字・カード・リンクは実際のHTMLとして構築する。

## 採用した設計

- 上部は細いブランドヘッダー。
- 導入パネルは全体の約2割に抑える。
- 「工房の道具たち」と4つのカードを主役にする。
- デスクトップは大きな色鉛筆画を持つ2×2カード。
- スマホは絵を左、説明を右にした短い1列カード。
- Paper Beige、Sage、Quiet Blue、Clay、Deep Indigoを部屋ごとに使う。

## デスクトップ生成プロンプト

Use case: ui-mockup. Asset type: complete high-fidelity desktop website design mockup, full homepage shown from header through footer. Design the complete homepage for a personal Japanese tool portal called "ぽんず工房". The four tools must be the visual center of the page, while the introductory hero stays compact. Use a warm off-white drawing-paper backdrop with subtle paper fibers and colored-pencil grain. Structure: slim brand header; compact horizontal introduction panel occupying no more than 22 percent of the page; dominant section "工房の道具たち"; four large practical tool cards in a 2 by 2 grid for ぽんずTodo, ぽんずさんぽ, ぽんず時間ログ, and ひらけ！ほしこうじょう; restrained footer. Style: shippable website UI combined with authentic colored-pencil miniature rooms, refined adult picture-book tone. Fully original. Avoid a giant hero, flat corporate vectors, glossy 3D, neon colors, busy patterns, and watermarks.

## スマホ生成プロンプト

Use case: ui-mockup. Input image: the generated desktop design reference. Create the responsive mobile version of the same complete "ぽんず工房" portal. Preserve its design language, palette, colored-pencil room illustrations, card hierarchy, and content. Use a slim header, very compact introduction, heading "工房の道具たち", the same four tools in a readable vertical flow, and a restrained footer. The heading and top of the first card must be visible in the first phone screen. Keep practical touch targets and avoid an oversized hero, horizontal overflow, tiny text, corporate vectors, glossy 3D, neon colors, and watermarks.

## 生成画像

- `site-concept-desktop-v1.png`
- `site-concept-mobile-v1.png`
