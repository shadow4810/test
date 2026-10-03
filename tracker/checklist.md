# Claude セッション進捗チェックリスト

最終確認: 2026-10-03 17:00 UTC（10/4 2:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] penguin-quizzical-puzzle ／ ダッシュボード「Claude Code 作業台帳」を公開した（https://claude.ai/artifact/918mferKE7n1eeKZDjUVNe）。中身を確認し、フックと絞り込みのテスト→コミットに進めてよいか返事をする ／ https://claude.ai/code/session_018uXz9osWhpucDBKGYNLYwz
- [ ] SFWローラの修理・高寿命化 ／ 試験方法6案（費用・納期・精度の比較表）とサンプル候補6つ（R1〜R3・A・B1〜B2）をスライドにまとめた。「①＋⑤」の進め方でよいか OK を出す（OK ならメーカーへの問い合わせと鋳物工場への確認に進む） ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] M08教材作成 ／ 仕様を v0.7 に作り直した（コアを 4mm ずつ A/B/C の3段で重ねる。S1 は CAM と講義、S2 は観察）。コア高さ 12mm と最終的な LTX 高さを反映した形状データを渡す ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] 電極ガス抜き穴自動設定 ／ 2点に答える：①電極は常に原点・無回転で置かれるか ②ガスだまり検出の方式（priority-flood）の理解で合っているか ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [ ] EPXgen予備 ／ 新しく作られたが、まだ何もしていない。使うなら指示を送る ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG

## 🟧 手作業
- [ ] 電極prt一括エクスポート開発 ／ probe2_api.py と probe_api.py を Drive と USB（claudecode/out_nx_electrode_export/01_probe/）に置いた。NX で probe2_api.py を実行し、出てきたレポート（probe2_report.txt と probe_report.txt）を返す ／ https://claude.ai/code/session_01E9KHwux1YV1ErcY1Tm9byL

## 🟦 外部待ち
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] TESTNET準備 ／ testnet の faucet 準備が完了（テスト15件合格、バックアップ確認済み、初日の手順書 tasks/testnet_dayone.md） ／ https://claude.ai/code/session_017YikYDsdTSyxymRq71Ww3v
- [x] 鍛造金型へのDED造形適用 ／ 段階1（試験片の造形）と段階2（高温試験）の計画書をスライドにし、Drive と USB（out_ded_general/forging_die_ded/01_計画書/）に配置済み ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [x] FLOP20260930 ／ 監視を再起動し、testnet_spend を含む 10 サービスすべて稼働中（自動監視が続いている） ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [x] Winroof解析 ／ 図3の横軸を指標ごとにそろえて PDF を作り直し、Drive と USB を更新済み ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [x] VR-6000検討 ／ 調査メモと .gitignore をコミット済み（eec728c）。図面はローカルのみ ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [x] 仕様検討 ／ 仕様書 v4.0（pptx 18ページ＋SPEC.md）を送付し、Drive/claudecode/out_epx_generator/ にも保存済み（以前の⑥ Makino 機での読み込み確認が済んだかは要約からは確認できない） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ
- [x] OJT進め方相談室 ／ 「月曜面談」を「週次ふりかえり」に変更。台本を直し、Drive と USB のファイルも差し替え済み ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ 経緯メモに承認版への切り替えと名称統一の経緯を追記して完了（前に挙がっていた TODO の手直しが済んだかは確認できていない） ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
