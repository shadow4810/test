# Claude セッション進捗チェックリスト

最終確認: 2026-10-07 05:00 UTC（10/7 14:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）。✅ は仕事全体が終わったものだけ

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] M09教材作成 ／ （新しいセッション）始めたばかりで、操作の許可待ちで止まっている。開いて内容を確認し、許可するか断る ／ https://claude.ai/code/session_013hd3EPjADEmujSjZePLGam
- [ ] バイメタル造形CAM自動化 ／ （新しいセッション）仕様書 v0.2 完成（1サイクル分の型を N サイクルに複製し、サイクルごとに変えるのは高さ Z だけ）。未回答の質問 Q10〜Q12（形状の変化、高さ欄の特定、余りの扱い）に答える。あわせて NX 2312 でサイクル1〜2を記録し、高さ欄の変化とスクリーンショット、probe_env.py の結果を MyDrive/claudecode/in_nx_ded_bimetal_cam/（または nx_probe/）に上げる ／ https://claude.ai/code/session_012fSWKeX93eEYPqMjqC6evx
- [ ] FLOP20260930 ／ 質問が2つ残っている：①close-1 の鍵バックアップを案A（停止）にするか案B（継続）にするか決める ②公式 testnet RPC の URL（testnet 公開は10月下旬〜11月上旬に延期。「公開されたら伝える」と返せばよい） ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr

## 🟧 手作業
- [ ] 鍛造金型へのDED造形適用 ／ 4つの修正案を反映し、第1〜2段階の計画書（v0.5／v0.4）とスライドを更新、Google Drive と USB にも反映済み。試験片13個、寿命の目標は摩耗の約5倍、段付きパッド 0.3／0.7 mm（仮）。計画書に沿って試験片の製作・試験を進める（変形は第3〜4段階で確認） ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [ ] 製番部番ドキュメント保存機能追加 ／ リリース用 zip（DED_QMS_release_20261006_052450.zip、353ファイル）と本番適用手順メモを Google Drive の claudecode/out_ded_qms/01_リリース/ に用意済み。手順メモに沿って本番に反映する ／ https://claude.ai/code/session_01G3u5Yq1LnRweZRfvHpyxYp
- [ ] LTX表面と内部の欠陥観察（旧 Winroof解析） ／ 根拠 Excel・画像12枚・PDF 報告書の13ファイルを Google Drive（claudecode/out_ded_general/defect_fatigue_sqrtarea/05_報告書/）と USB に保存済み（md5 確認済み）。GL に渡す ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [ ] 電極prt一括エクスポート開発 ／ （新しいセッション）electrode_export.py が完成し、手元のテスト65件OK。NX のテスト用アセンブリで実行し、export/ への出力・上書き・一部選択を確かめ、最後のメッセージと情報ウィンドウの内容を送る ／ https://claude.ai/code/session_01PN8DUjPuBCKfHo3QgLGcRA
- [ ] EPX_generator開発 ／ 属性設定ツール（VB.NET）完成、連携テスト63件OK。最新61ファイルを USB（claudecode/out_epx_generator/）に反映済み。NX 実機でツールを実行し、S-01〜S-03 の確認結果・スクリーンショット・保存した設定ファイルを送る ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ

## 🟦 外部待ち
- [ ] EPXgen予備 ／ バイメタル造形CAM自動化のセッションに指示を送り、その返事を待っている ／ https://claude.ai/code/session_013jfA4BsM5XSGBMPziCfANG
- [ ] M08教材作成 ／ M08／M13 の GL レビュー結果待ち（次の手順は記録済み）。結果が届いたらセッションに渡す ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] SFWローラの修理・高寿命化 ／ 提案資料3点を out_ded_general/sfw_roller_repair/01_計画書/ に整理済み。部内の反応待ち。反応が来たらセッションに伝える ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] VR-6000検討 ／ デモ用のチェックリストを用意済み。デモの結果とデータが出たらセッションに渡す ／ https://claude.ai/code/session_016TPbjdfdHzTtQqjbRM31Ay
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] 電極ガス抜き穴自動設定 ／ NX 実機で動作確認済み。最新のジャーナルを USB に入れ、Google Drive と一致を確認（4ファイル、md5 一致）。仕事全体が完了 ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [x] OJT進め方相談室 ／ ワンページ説明①の45分台本（A4×2ページ）が完成。PDF保存・md5確認済みで、Drive と USB に配置 ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ ワンページ説明①台本の完了報告を受領。要対応なし ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
