# pilgrimage-planner
An app designed to plan pilgrimage itineraries and generate a dedicated viewer for use on the go. It’s versatile enough to be used not only for pilgrimages but also for planning general travel or business trips.

English follows Japanese

概要
巡礼プランナーは、札所マスタ・日程・移動経路をブラウザ上で編集し、
最終的に 静的HTMLの行程表（viewer.html） を生成できるツールです。

ローカルのみで動作（サーバ不要）

JSON 保存・読込に対応

札所ごとに経路を紐付け

Claude/Copilot で生成した HTML ビューアをワンクリック出力

GitHub Pages で公開可能

🔧 使い方（操作手順）
① 巡礼設定
巡礼名

出発地

全体メモ
を入力します。

② 札所マスタ
番号、名称、住所、メモを入力

「札所を追加」で登録

並べ替え（↑↓）・編集・削除が可能

Google Maps で住所検索も可能

③ 日程編集
「日程タブ追加」で日程を作成

「札所追加」で訪問する札所を選択

「経路セグメント追加」で移動区間を追加

出発地・到着地・時刻・運賃・メモ・手段を入力

セグメントは ↑↓ で並べ替え可能

④ プレビュー
巡礼概要

日程ごとの行程表

JSON の構造
を確認できます。

⑤ ビューアHTML生成
「ビュー用HTML生成」ボタンを押すと、
viewer.html がダウンロードされます。

このファイルは単体で動作し、
スマホ・PC・印刷・PDF化に対応します。

💾 JSON の保存・読込
「保存」→ localStorage に保存

「再読込」→ localStorage から復元

「JSON出力」→ JSON を表示

「JSON読込」→ ファイルから読み込み

📄 免責事項（Disclaimer）
本ツールは個人利用を前提とした補助ツールです。
生成される行程表の正確性・最新性・安全性は保証されません。
交通機関の時刻・運賃・経路は必ず公式情報をご確認ください。
本ツールの利用により生じたいかなる損害についても、
作者および協力したAIは責任を負いません。

📂 ライセンス
MIT License（必要に応じて変更してください）

🇺🇸 English Version
Overview
Pilgrimage Planner is a browser-based tool for creating and exporting pilgrimage itineraries.
You can edit sites, days, and travel segments, then export a standalone viewer.html file.

Works entirely offline (no server required)

Supports JSON import/export

Travel segments are linked to pilgrimage sites

One-click HTML viewer generation

Suitable for GitHub Pages publishing

🔧 How to Use
1. Pilgrimage Settings
Enter:

Pilgrimage name

Starting location

Notes

2. Site Master
Add each pilgrimage site:

Number

Name

Address

Notes

You can reorder, edit, or delete sites.
Google Maps search is available.

3. Schedule Editing
Add a new day

Select a site to visit

Add travel segments

Enter departure/arrival locations, times, fare, memo, and mode

Reorder segments with ↑↓

4. Preview
Displays:

Pilgrimage summary

Daily itinerary

JSON structure

5. Generate Viewer HTML
Click “Generate Viewer HTML” to download viewer.html.
This file works standalone and is suitable for mobile, desktop, printing, and PDF export.

💾 JSON Import/Export
Save → store to localStorage

Reload → restore from localStorage

Export JSON → show JSON

Import JSON → load from file

📄 Disclaimer
This tool is provided for personal use only.
Accuracy of routes, fares, and timetables is not guaranteed.
Always verify transportation information with official sources.
The author and assisting AI assume no liability for any damages arising from use.

📂 License
MIT License (modifiable)
