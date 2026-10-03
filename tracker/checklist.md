# Claude セッション進捗チェックリスト

最終確認: 2026-10-03 7:00 UTC（10/3 16:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] penguin-quizzical-puzzle ／ Drive（62件）と USB（13件）のフォルダをテーマ別に整理し、確認済み。この変更でよいか承認してコミットを許可する（直しがあれば指示する） ／ https://claude.ai/code/session_018uXz9osWhpucDBKGYNLYwz
- [ ] 鍛造金型へのDED造形適用 ／ 硬さと熱処理の計画案ができた。炉の仕様と 2001 年の試作データを渡す ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [ ] M08教材作成 ／ 05:35 から操作待ちで止まっている（許可または返事が必要）。前回の3点（無人運転の方針・CAM の範囲・コア壁上面の切削）も未回答の可能性あり ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] 電極ガス抜き穴自動設定 ／ 2点に答える：①電極は常に原点・無回転で置かれるか ②ガスだまり検出の方式（priority-flood）の理解で合っているか ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [ ] EPXgen予備 ／ 新しく作られたが、まだ何もしていない。使うなら指示を送る ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG

## 🟧 手作業
- [ ] TESTNET準備 ／ bash daemons/start_all.sh の実行を待っている。ただし FLOP20260930 が 06:52 に「10 サービスすべて稼働中」と報告しているので、もう済んでいる可能性あり。済んでいればセッションに伝える ／ https://claude.ai/code/session_017YikYDsdTSyxymRq71Ww3v
- [ ] 電極prt一括エクスポート開発 ／ NX で probe2_api.py を実行（2項目を選び「はい」→「いいえ」）し、D:\NX\TEST_electrode_export\_electrode_probe_out\ の probe2_report.txt と probe_report.txt を返す ／ https://claude.ai/code/session_01E9KHwux1YV1ErcY1Tm9byL

## 🟦 外部待ち
- [ ] SFWローラの修理・高寿命化 ／ 06:02 に作られ、いま Claude が作業中。私の操作は不要（終わったら次回の見直しで区分し直す） ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] FLOP20260930 ／ 監視を再起動し、testnet_spend を含む 10 サービスすべて稼働中（自動監視が続いている） ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [x] Winroof解析 ／ PDF に第5章（上・中・下段の傾向）を追加し、章番号を振り直した ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [x] VR-6000検討 ／ 調査メモと .gitignore をコミット済み（eec728c）。図面はローカルのみ ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [x] 単トラック、パッドの材料分析依頼 ／ 分析計画 §0.8 を更新（EPMA は Fe のみ・BSE・XRD・硬さ）し、決定事項を記録（762cff6） ／ https://claude.ai/code/session_01XeDdq1mkcPxJdy7KvVCGYh
- [x] 仕様検討 ／ 仕様書 v4.0（pptx 18ページ＋SPEC.md）を送付し、Drive/claudecode/out_epx_generator/ にも保存済み（以前の⑥ Makino 機での読み込み確認が済んだかは要約からは確認できない） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ
- [x] OJT進め方相談室 ／ 「月曜面談」を「週次ふりかえり」に変更。台本を直し、Drive と USB のファイルも差し替え済み ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ 経緯メモに承認版への切り替えと名称統一の経緯を追記して完了（前に挙がっていた TODO の手直しが済んだかは確認できていない） ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
