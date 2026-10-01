# Claude セッション進捗チェックリスト

最終確認: 2026-10-02 00:00 UTC（10/2 9:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）

## ⏰ 期限が近いもの
- [ ] 🟧 仕様検討 ／ 【10/1 予定分】USB の中身は最新と確認済み。01_ツール/ と 07_試験/ を NX の PC にコピーして再テストし（手順1〜3）、EPX と属性ダンプをアップロードする ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ

## 🟥 判断待ち
- [ ] VR-6000検討 ／ インレットインサートの情報を渡す：寸法（縦×横×全高）、質量、最も深い部分の深さと開口幅、インレットの形状と壁の高さ、材質と表面処理 ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [ ] TESTNET準備 ／ sr25519 鍵を作ってよいか承認する。復号鍵は close-1 と共用にするか別にするかを決める ／ https://claude.ai/code/session_017YikYDsdTSyxymRq71Ww3v
- [ ] M08教材作成 ／ 仕様 v0.3 について2点に答える：(1) S1 以降の自律運用のルール、(2) CAM の検査範囲（その後の報告は USB の確認と M13 の PDF 送付だけ。この2点に答えたかは確認できず） ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] EPXgen予備 ／ 新しく作られたが、まだ何もしていない。使うなら指示を送る ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG

## 🟧 手作業
- [ ] 電極prt一括エクスポート開発 ／ NX で電極データの入ったアセンブリに対して probe_api.py を実行し、probe_report.txt を送る ／ https://claude.ai/code/session_01E9KHwux1YV1ErcY1Tm9byL
- [ ] 電極ガス抜き穴自動設定 ／ NX で probe_api.py を2回実行する（1回目は電極を原点に置く、2回目はずらして回転させる）。probe_report.txt を保存する ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [ ] 仕様検討 ／ （上の「期限が近いもの」を参照） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ

## 🟦 外部待ち
（なし）

## ✅ 完了
- [x] OJT進め方相談室 ／ 「月曜面談」を「週次ふりかえり」に変更。台本を直し、Drive と USB のファイルも差し替え済み ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ 経緯メモに承認版への切り替えと名称統一の経緯を追記して完了（前に挙がっていた TODO の手直しが済んだかは確認できていない） ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
- [x] FLOP20260930 ／ テストネットの監視だけが自動で続いている ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [x] DAM-M17 パッドの報告書 ／ 用語の統一と縦割れの記述の修正をコミット済み。USB への転送も済み ／ https://claude.ai/code/session_01YPkvahR8CvpM5uZAKDRZ4h
