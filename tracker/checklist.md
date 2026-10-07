# Claude セッション進捗チェックリスト

最終確認: 2026-10-07 19:00 UTC（10/8 4:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）。✅ は仕事全体が終わったものだけ

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] ノズル閉塞を防ぐ休止条件の検証 ／ （新しいセッション）作られたばかりで、まだ報告がない。開いて内容を確認し、次の指示を出す ／ https://claude.ai/code/session_01SVgbt7VeVyvk4xwFRoSeMe
- [ ] M09教材作成 ／ M09 の仕様・本文・チェックリストの案（v0.2.1／v0.1）と確認用 PDF ができた。v1.0 にする前に3点を確認して返す：①S2 の時間配分は現実的か ②NC の一時停止の手順 ③HAZ の説明の言い回し ／ https://claude.ai/code/session_013hd3EPjADEmujSjZePLGam
- [ ] バイメタル造形CAM自動化 ／ （新しいセッション）仕様書 v0.2 完成（1サイクル分の型を N サイクルに複製し、サイクルごとに変えるのは高さ Z だけ）。未回答の質問 Q10〜Q12（形状の変化、高さ欄の特定、余りの扱い）に答える。あわせて NX 2312 でサイクル1〜2を記録し、高さ欄の変化とスクリーンショット、probe_env.py の結果を MyDrive/claudecode/in_nx_ded_bimetal_cam/（または nx_probe/）に上げる ／ https://claude.ai/code/session_012fSWKeX93eEYPqMjqC6evx
- [ ] FLOP20260930 ／ 質問が2つ残っている：①close-1 の鍵バックアップを案A（停止）にするか案B（継続）にするか決める ②公式 testnet RPC の URL（testnet 公開は10月下旬〜11月上旬に延期。「公開されたら伝える」と返せばよい）。ほかに、古い出力フォルダ（out_flop/_old）を消すコマンドが用意されている。消すかどうかは中身を見てから決める ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr

## 🟧 手作業
- [ ] LTX表面と内部の欠陥観察（旧 Winroof解析） ／ ログを Google Drive の claudecode/in_ded_general/ に置く：B1・B17・B20 の Data.dat フォルダ、造形条件の表、あれば NC プログラム。置いたらセッションに伝える ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [ ] SFWローラの修理・高寿命化 ／ Höganäs の粉末は、公開されている代理店が見つからなかった（日本語・英語で5通り検索）。ヘガネスジャパン（048-583-5561 か iProS のフォーム）に、扱っている商社か直接購入できるかを問い合わせ、結果をセッションに伝える ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] 鍛造金型へのDED造形適用 ／ 試験計画の説明を受けた（YXR33 の板に Inconel718 を薄く盛り、2段階で造形条件・熱処理（5通り）・厚さを決める）。計画書に沿って試験片の製作・試験を進める ／v0.4）とスライドを更新、Google Drive と USB にも反映済み。試験片13個、寿命の目標は摩耗の約5倍、段付きパッド 0.3／0.7 mm（仮）。計画書に沿って試験片の製作・試験を進める（変形は第3〜4段階で確認） ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [ ] 電極prt一括エクスポート開発 ／ 多層アセンブリでの試験を途中で止め、明日用の引き継ぎメモ（tasks/handoff_20261007_multilayer_test.md）を作成済み。明日 NX 実機で多層アセンブリの試験を続ける ／ https://claude.ai/code/session_01PN8DUjPuBCKfHo3QgLGcRA
- [ ] EPX_generator開発 ／ 部品が読み込まれない原因を特定（epx_generator.py は ELECTRODE_NAME/WORK_PIECE_NAME 属性付きの部品だけを対象にし、属性設定ツールは全部品を表示する仕様）。明日 NX で行う3つの作業と、そこで決める3点を記録済み。明日 NX 実機で続きを行う ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ

## 🟦 外部待ち
- [ ] M08教材作成 ／ M13 は GL 承認済み（10/7、MS-5 は 11/18 承認に変更）。M08 は提出済みで GL レビュー中。結果が届いたらセッションに渡す ／M13 の GL レビュー結果待ち（次の手順は記録済み）。結果が届いたらセッションに渡す ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] 電極ガス抜き穴自動設定 ／ NX 実機で動作確認済み。最新のジャーナルを USB に入れ、Google Drive と一致を確認（4ファイル、md5 一致）。仕事全体が完了 ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [x] OJT進め方相談室 ／ 週次ふりかえり（10分）の進め方ガイド（褒める→1〜2行補足→基準伝達）を作成。要対応なし ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7
- [x] 指令塔 ／ ワンページ説明①台本の完了報告を受領。要対応なし ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
