# Claude セッション進捗チェックリスト

最終確認: 2026-10-04 5:00 UTC（10/4 14:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] 鍛造金型へのDED造形適用 ／ 単トラックの段階は社内で色の確認と寸法測定だけで済ませ、断面の分析はパッドの段階で行う案ができた。設備が使えるか確認するか、「進めて」と返して計画書 §5.1 の改訂に進ませる ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [ ] FLOP20260930 ／ 「TESTNET準備セッションを落としてよいか」の承認を求めている（TESTNET準備はすでにアーカイブ済み）。OK と返す。公式 testnet RPC エンドポイントも引き続き待っている ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [ ] M08教材作成 ／ モジュール文書（docs/modules/m08_bimetal_mold.md）の下書き v0.1 を読んで、直してほしい点を返す ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] EPXgen予備 ／ 新しく作られたが、まだ何もしていない。使うなら指示を送る ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG

## 🟧 手作業
- [ ] EPX_generator開発 ／ NX で検証した結果を渡す（結果を見て進め方を決めるとのこと） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ
- [ ] 電極ガス抜き穴自動設定 ／ NX の実機で動作を確かめ、結果（エラーメッセージ、情報ウィンドウの内容、またはスクリーンショット）を返す ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [ ] 電極prt一括エクスポート開発 ／ NX で probe2_api.py を実行し、D:\NX\TEST_electrode_export\_electrode_probe_out\ の probe2_report.txt と probe_report.txt を返す（引き続き待ち） ／ https://claude.ai/code/session_01E9KHwux1YV1ErcY1Tm9byL

## 🟦 外部待ち
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] SFWローラの修理・高寿命化 ／ SRV 試験機の試験球をアルミに変えることは寸法上可能。ただし実機での確認が必須で、材料技術部に4項目（ホルダが使えるか、温度上限、荷重・振幅・周波数、円板の寸法）を確かめて試験できるか判断する必要がある ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [x] Winroof解析 ／ 図3の横軸を指標ごとにそろえて PDF を作り直し、Drive と USB を更新済み ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [x] VR-6000検討 ／ 調査メモと .gitignore をコミット済み（eec728c）。図面はローカルのみ ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [x] OJT進め方相談室 ／ 「月曜面談」を「週次ふりかえり」に変更。台本を直し、Drive と USB のファイルも差し替え済み ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ 経緯メモに承認版への切り替えと名称統一の経緯を追記して完了（前に挙がっていた TODO の手直しが済んだかは確認できていない） ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
