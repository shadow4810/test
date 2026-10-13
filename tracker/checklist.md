# Claude セッション進捗チェックリスト

最終確認: 2026-10-13 22:00 UTC（10/14 7:00 JST）
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）。✅ は仕事全体が終わったものだけ

## ⏰ 期限が近いもの
（なし）

## 🟥 判断待ち
- [ ] 昇格審査の資料作成 ／ レビューが済み、資料と論文はY4相当と判定された（タイトル「水漏れ金型」の修正、部方針への言及の追加、数字の根拠の整理など8項目を指摘）。3点に答える：①鋳造トライは11月か12月か ②指摘①〜⑦のうちどれを自分で直すか ③最新の pptx・docx を `Y4 (1)/` に置く ／ https://claude.ai/code/session_01GvoV5E6ccPcnuh8nYbez9c
- [ ] ノズル閉塞を防ぐ休止条件の検証 ／ （新しいセッション）作られたばかりで、まだ報告がない。開いて内容を確認し、次の指示を出す ／ https://claude.ai/code/session_01SVgbt7VeVyvk4xwFRoSeMe
- [ ] M09教材作成 ／ 草案 v0.1 の PDF（10/7 送付）を確認し、4点について返す：①S2 の時間配分 ②NC の一時停止の手順 ③§4.2.3 の言い回し ④そのほか気になる点 ／ https://claude.ai/code/session_013hd3EPjADEmujSjZePLGam
- [ ] FLOP20260930 ／ 質問が2つ残っている：①close-1 の鍵バックアップを案A（停止）にするか案B（継続）にするか決める ②公式 testnet RPC の URL（testnet 公開は10月下旬〜11月上旬に延期。「公開されたら伝える」と返せばよい）。ほかに、古い出力フォルダ（out_flop/_old）を消すコマンドが用意されている。消すかどうかは中身を見てから決める ／ https://claude.ai/code/session_01MuXFYcS6N5ZZiPWKb662Fr
- [ ] penguin-sunny-cookie ／ （新しいセッション）作られたばかりで、報告の要約がない（Git リポジトリなし）。開いて内容を確認し、次の指示を出す ／ https://claude.ai/code/session_01U8ARTLbr8YRb4KuadYmKCC
- [ ] EPX_generator開発 ／ 修正を進めるための設計判断2点に答える：①属性設定ツールで部品の種類を絞り込むか（推奨：はい）②読み込まれていない部品の扱い（推奨：警告して確認） ／ https://claude.ai/code/session_01FHYT5jSQyJpbRmfs3hZyCQ

## 🟧 手作業
- [ ] LTX表面と内部の欠陥観察（旧 Winroof解析） ／ ログを Google Drive の claudecode/in_ded_general/ に置く：B1・B17・B20 の Data.dat フォルダ、造形条件の表、あれば NC プログラム。置いたらセッションに伝える（参考論文2本の PDF はセッションから受け取り済み：H13 上のアルミ青銅と、アルミ青銅上の H13） ／ https://claude.ai/code/session_01RjyqBTpGvmGbdYC1n6A56g
- [ ] SFWローラの修理・高寿命化 ／ 肉盛り層の詳細を見るため、NiBas 776 W40 の PDF を themes/machine_materials/references/ に置く。あわせて、試験計画スライド v6 の確認と、Höganäs 粉末の入手先のヘガネスジャパン（048-583-5561 か iProS のフォーム）への問い合わせ ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] 鍛造金型へのDED造形適用 ／ 試験計画の説明を受けた（YXR33 の板に Inconel718 を薄く盛り、2段階で造形条件・熱処理（5通り）・厚さを決める）。計画書に沿って試験片の製作・試験を進める ／v0.4）とスライドを更新、Google Drive と USB にも反映済み。試験片13個、寿命の目標は摩耗の約5倍、段付きパッド 0.3／0.7 mm（仮）。計画書に沿って試験片の製作・試験を進める（変形は第3〜4段階で確認） ／ https://claude.ai/code/session_015GonF7YvnSZ2DNCtn1NSw4
- [ ] 電極prt一括エクスポート開発 ／ 多層対応の electrode_export.py は USB で確認済み。NX 実機で多層アセンブリ（レイヤー200＋201）の試験を行い、結果を zip にしてセッションに渡す ／ https://claude.ai/code/session_01PN8DUjPuBCKfHo3QgLGcRA
- [ ] OJT進め方相談室 ／ 10/16（金）の7時間の予定（部品メモの修正1h・事務1h・NX復習1h・現場見学2h・チーム観察1.5h・振り返り15分）ができた。現場の案内役を今日か明日のうちに手配する ／ https://claude.ai/code/session_01VidqCopvRnqEo3jWWDjSX7

## 🟦 外部待ち
- [ ] M08教材作成 ／ M13 は GL 承認済み（10/7、MS-5 は 11/18 承認に変更）。M08 は提出済みで GL レビュー中。結果が届いたらセッションに渡す ／M13 の GL レビュー結果待ち（次の手順は記録済み）。結果が届いたらセッションに渡す ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] DAM-M17 材料技術分析 ／ 材料技術からの分析結果待ち。届いたらセッションを再開する ／ https://claude.ai/code/session_01NMcZKJMWnQZUtyTagcTRFL
- [ ] M2C の使い方 ／ 試験日程待ち。決まったらセッションに伝えると、計画に日付・材料・チェックリストを追記する ／ https://claude.ai/code/session_0183JN1ohfmutn4DiK8dz9iG

## ✅ 完了
- [x] 電極ガス抜き穴自動設定 ／ NX 実機で動作確認済み。最新のジャーナルを USB に入れ、Google Drive と一致を確認（4ファイル、md5 一致）。仕事全体が完了 ／ https://claude.ai/code/session_01Shx2fuvmvcuJHHAVQPfe8p
- [x] 指令塔 ／ ワンページ説明①台本の完了報告を受領。要対応なし ／ https://claude.ai/code/session_01JQhf2wYNJGHJfmmsRPSdGz
- [x] 計画書 ／ 承認済みの計画書（20260929）を正本として確認。Drive と USB の差し替えも済み ／ https://claude.ai/code/session_018fTVUa52tU51Wnww3eyxMr
- [x] 各種ワークブック作成 ／ 週次ふりかえり用のテンプレートを作り直し、Drive と USB に同期済み ／ https://claude.ai/code/session_01En3t9RkumGLdNsLKLXSc1S
- [x] ワンページ ／ 欄名を「ふりかえり実施」に統一し、Drive と USB に配置済み ／ https://claude.ai/code/session_01Jwgu2UER3Cy8wjSCnpLzjg
