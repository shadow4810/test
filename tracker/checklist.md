# Claude セッション進捗チェックリスト

最終確認: 2026-10-03 2:00 UTC（10/3 11:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] 電極ガス抜き穴自動設定 ／ 2点に答える：①電極は常に原点・無回転で置かれるか ②ガスだまり検出の方式（priority-flood）の理解で合っているか ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [ ] VR-6000検討 ／ インレットインサートの情報を渡す：寸法（縦×横×全高）、質量、最も深い部分の深さと開口幅、インレットの形状と壁の高さ、材質と表面処理 ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [ ] TESTNET準備 ／ sr25519 鍵を作ってよいか承認する。復号鍵は close-1 と共用にするか別にするかを決める ／ https://claude.ai/code/session_017YikYDsdTSyxymRq71Ww3v
- [ ] M08教材作成 ／ 仕様 v0.5 更新済み。3点に答える：①無人運転の方針（退勤後・監視）②CAM の範囲（工程作成まで？レーザー条件は？）③コア壁の上面をサイクルごとに削るか ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] EPXgen予備 ／ 新しく作られたが、まだ何もしていない。使うなら指示を送る ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG

## 🟧 手作業
- [ ] 電極prt一括エクスポート開発 ／ NX で probe2_api.py を実行（2項目を選び「はい」→「いいえ」）し、D:\NX\TEST_electrode_export\_electrode_probe_out\ の probe2_report.txt と probe_report.txt を返す ／ https://claude.ai/code/session_01E9KHwux1YV1ErcY1Tm9byL

## 🟦 外部待ち
（なし）

## ✅ 完了
- [x] 仕様検討 ／ 仕様書 v4.0（pptx 18ページ＋SPEC.md）を送付し、Drive/claudecode/out_epx_generator/ にも保存済み（以前の⑥ Makino 機での読み込み確認が済んだかは要約からは確認できない） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ
- [x] OJT進め方相談室 ／ 「月曜面談」を「週次ふりかえり」に変更。台本を直し、Drive と USB のファイルも差し替え済み ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ 経緯メモに承認版への切り替えと名称統一の経緯を追記して完了（前に挙がっていた TODO の手直しが済んだかは確認できていない） ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
- [x] FLOP20260930 ／ テストネットの監視だけが自動で続いている ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [x] DAM-M17 パッドの報告書 ／ 用語の統一と縦割れの記述の修正をコミット済み。USB への転送も済み ／ https://claude.ai/code/session_01YPkvahR8CvpM5uZAKDRZ4h
