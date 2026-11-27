# Claude セッション進捗チェックリスト

最終確認: 2026-11-27 02:00 UTC
区分はセッション名の頭の絵文字で表示（🟥 / 🟧 / 🟦 / ✅）。✅ は仕事全体が終わったものだけ

## ⏰ 期限が近いもの
- [ ] 11/25 EDU00001 の修了予定 ／ 18本中11本が修了。残り6本は間に合わない見込み（M08 の S2 は期限切れ）。修了予定を延ばすか残りの進め方を決める（受講状況セッションは11/8にアーカイブ済み） ／ https://claude.ai/code/session_01CYJnVurKNhrYNxhR4zx29W
- [ ] 11/9 EDU00001 の M09 実践（PT など）／ 割り付け案はチェックリストに反映済み。当日実施し、終わったら結果を「M09実践形式まとめ」に伝える ／ https://claude.ai/code/session_01CYJnVugiBUHase4M39htmJ

## 🟥 判断待ち
- [ ] EDU00002実施記録 ／ m03_equipment.pdf（15ページ）が届いている。p.3 と p.14 を印刷する。進行ガイド v0.3 は未コミットのまま。内容を確認してコミットしてよいか指示する ／ https://claude.ai/code/session_01CYJnVr7BDv593UeaZZsLpz
- [ ] EDU00002準備 ／ M00〜M05 の抜粋時間割を1ファイルで受け取った（リポジトリには未保存）。内容を確認し、旧一体版 script_short_course_m00_m07.md をどうするか決める（M06〜M07 は未着手） ／ https://claude.ai/code/session_01CYJnVuo7eUV5paETemqMBq
- [ ] M15教材作成 ／ spec・本文・確認テスト10問の v0.1 ができた（未コミット）。下書きをレビューし、未決事項3件を決める ／ https://claude.ai/code/session_01CYJnVt7JjKeDRY242ZM8Q7
- [ ] M14 学習目標と確認テスト ／ 提案1（演習②を②-1〜②-3の3回に分ける）と提案3（§4.3.1に用語の予告）を本文・specに反映してコミットし、PDFを送付済み。PDFを確認して内容を承認する ／ https://claude.ai/code/session_01CYJnVurHQANEfMxrWC9AZ5
- [ ] DED造形のスパッタ過多不具合 ／ 提示された条件案（1.6mm: LPC 1000→550W、目標面積2500、IPTC (250,900,300) 毎層／薄壁は 3mm・1.6mm 案）と試し手順を見て、試すか決める（調査メモ §5.1/5.2 は未コミット） ／ https://claude.ai/code/session_01CYJnVrhM3Z3WA1AiuVJei2
- [ ] 放電加工たわみ計算ツール ／ 深さ方向の削りすぎは電極の傾きでは説明できないと分かった（7枚目の「合わない」はそのまま）。pptx（1枚目修正済み）の表示を確認し、原因をどう追うか決める ／ https://claude.ai/code/session_01CYJnVr5dxXHPjrhgdxLwNL
- [ ] 20261116 測定データ ／ 電極長手は139.6mmで摩耗なし。壁の段は電極形状ではなく加工時の動きか放電状態が原因と判断（docs/data_reference_20261116.md 7章）。この結論を確認し、次に動き・放電状態を調べるか決める ／ https://claude.ai/code/session_01CYJnVsVKGNyMEDywm8se3j
- [ ] 実運用時のルールぎめ ／ 判定スクリプト src/edm_squeeze/screen.py が完成。DA4007 は仮定値の試算で NG（最大189N、たわみ196µm）。仮定値を実値に置き換えるか、ジャーナル用の確認事項4点に進むかを決める ／ https://claude.ai/code/session_01CYJnVsMuHRz5kc29K37fiX
- [ ] Zジャンプの時のたわみについて理解を深める ／ 「ロッドは図心ではなく力の作用線上に付ける」と説明があった。電極ごとに作用線を求めてたわみを再計算するよう進めるか決める ／ https://claude.ai/code/session_01CYJnVtRFE2RnHY7YmwuT2p
- [ ] 不具合考察 ／ 0.5ms刻みの座標データからジャンプ速度・加減速・揺動の形を読めるが、電極のたわみは直接出ず、放電の有無には極間電圧などの信号が要る、と回答あり。座標データで解析を進めるか、電圧信号も用意するかを決める ／ https://claude.ai/code/session_01CYJnVqPAd7uoRJW45Ew8gi
- [ ] ノズル閉塞を防ぐ休止条件の検証 ／ （新しいセッション）作られたばかりで、まだ報告がない。開いて内容を確認し、次の指示を出す ／ https://claude.ai/code/session_01SVgbt7VeVyvk4xwFRoSeMe
- [ ] M09教材作成 ／ 草案 v0.1 の PDF（10/7 送付）を確認し、4点について返す：①S2 の時間配分 ②NC の一時停止の手順 ③§4.2.3 の言い回し ④そのほか気になる点 ／ https://claude.ai/code/session_013hd3EPjADEmujSjZePLGam
- [ ] M08教材作成 ／ M08 の GL 承認を記録済み（承認済みは計12モジュール）。残りの作業（S2 の実施、講義スライド、形状レビュー）をどう進めるかと、M09 に着手してよいかを指示する ／ https://claude.ai/code/session_01VcRiswB5sYcoK6PQqF8c6K
- [ ] M13講師メモ ／ EDU00001 M13第1期修了を記録済み（実技9/9、Forms 90/100）。変更はまだコミットされていないので、コミットするよう指示する ／ https://claude.ai/code/session_01G7qbF8WDGPVjYBcqwzYuqW
- [ ] バイメタル ／ 未コミットだった3件をコミットして保存中。依頼書は依頼先が決まるのを待っている：依頼先は材技かキグチかを答える ／ https://claude.ai/code/session_01CYJnVtzzF23mHpSAowznjm
- [ ] DAM-M17 材料技術分析 ／ 材技への依頼文ができた（A案を推奨）。今日送ってよいか決める。送る前に、相手が知らない前提が書かれていないか最終確認する ／ https://claude.ai/code/session_01CYJnVqjRHudNee37DEh26Q
- [ ] 回転曲げ疲労試験片 ／ 11/8 の 07:26 にも返答があったが、要約がない。前回は回転曲げ（I-6）での開始を推奨し、GLレビュー後に計画v3へ進む段階だった。開いて内容を確認し、次の指示を出す ／ https://claude.ai/code/session_01CYJnVudJnh8hmT4RChEtGa
- [ ] M10実践形式まとめ（旧 EDU00001 厚膜コーティングテスト） ／ M10 試行（11/4 CAM 約2h、講師立会い）は記録済み。追加の評価項目の提案に対し4点答える：①造形品は実使用品か、断面を採ってよいか ②DED_QMS 報告書の対象か ③ビッカース硬さ計はあるか ④仮のチェックリスト・予測表を今日作ってよいか ／ https://claude.ai/code/session_01CYJnVsNx3SMVoQsxYcdM6m
- [ ] M08実践形式まとめ ／ 進める順番の案が出た：①日程ずれの記録 ②講義進行資料 script_m08 の作成（期限超過）③S2 の実施と記録 ④押印 PDF の SharePoint 格納確認。この順で着手してよいか指示する ／ https://claude.ai/code/session_01CYJnVqu5iYU5Hbdrw9RY64

## 🟧 手作業
- [ ] テストネット ／ GitHub での申請を自分で出す（issue 2件は無反応、ウォレット登録は 404 のまま。セッションの毎時チェックは停止済み） ／ https://claude.ai/code/session_01CYJnVqTjUQjL5MMntpcdRF
- [ ] エージェント構築 ／ doe-kit v1 完成。zip 3件は .txt でも受け取り済み。Lists 追加、Copilot への登録、試験1・2を自分で行う ／ https://claude.ai/code/session_01CYJnVqtPHXPLvXRhc1xXrc
- [ ] EDU00001実施記録 ／ 11/25 の M09 再造形を実施ログ・チェックリスト・進捗に記録済み。#7 の PT は未実施なので日程を決めて実施し、SharePoint への反映も行う ／ https://claude.ai/code/session_01CYJnVuW4E6snDUHYaqfEMo
- [ ] EPX_generator開発 ／ 電極名順の修正で変わった9ファイルを、半角英数字名の zip で受け取り済み（開けることは確認済み）。ドライブへ反映し、NX では epx_generator.py だけ差し替えて、牧野さんの実機で確認する（M-17） ／ https://claude.ai/code/session_01CYJnVtHLULuVYYbT3HRPyx
- [ ] EPXeditor開発 ／ v3.7 の ZIP を受け取り済み（深さ違いの電極は1つのポットを共有する形に変更）。社内 PC の Chrome と Hyper i で動作を確認する ／ https://claude.ai/code/session_01CYJnVtiw7DdKU1y9Fhiv4U
- [ ] 開発ツール作成 ／ edm_detail_info を電極名順に並べ替え、SPEC 4.7・TESTPLAN 7.6 に改訂済み（テスト104件通過）。USB を挿して反映してもらい、NX で 07_試験 のチェックリストを確認する ／ https://claude.ai/code/session_01CYJnVuCHejbEX7423usvtQ
- [ ] Copilot環境改善 ／ doc-review-kit.zip を作り直した（用語の指摘は Linter の結果だけ、MUST が0件なら「配布可（WANT n件）」と判定）。Copilot で改善ログを登録し、ZIP を差し替えて、もう一度レビューして確かめる ／ https://claude.ai/code/session_01CYJnVt5xMzd8pvaqQEtia4
- [ ] Perpdex残高付きウォレットポートフォリオ ／ `pf` コマンド（最新残高を取得してページを開く）と「最新に更新」ボタンを追加、テスト118件通過、未コミット。変更をコミットし、config/wallets.toml に Aave アカウントと EtherFi Cash Vault のアドレスを登録して `pf` で結果を確認する ／ https://claude.ai/code/session_01CYJnVrqZfCJo69P5GkJ7CJ
- [ ] FLOP20260930 ／ セッションが以前のメッセージで示したコマンドを実行する ／ https://claude.ai/code/session_01CYJnVsHcZh7y7pvtFkyFbJ
- [ ] 入力UIツール作成 ／ 電極の属性を body から読む形に変更し、入力ツール・一括付与・Python のテストは全件成功（Drive 反映済み）。設定ツールは未テストで、確認シートに COMMENT 項目も未追加。USB に入れて NX で動作を確認する ／ https://claude.ai/code/session_01CYJnVsgu3QrfadqrYHpRgv
- [ ] SFWローラの修理・高寿命化 ／ 肉盛り層の詳細を見るため、NiBas 776 W40 の PDF を themes/machine_materials/references/ に置く。あわせて、試験計画スライド v6 の確認と、Höganäs 粉末の入手先のヘガネスジャパン（048-583-5561 か iProS のフォーム）への問い合わせ ／ https://claude.ai/code/session_01VhcnY2XVmxoGGmjiRfGqa3
- [ ] 電極prt一括エクスポート開発 ／ 多層対応の electrode_export.py は USB で確認済み。NX 実機で多層アセンブリ（レイヤー200＋201）の試験を行い、結果を zip にしてセッションに渡す ／ https://claude.ai/code/session_01PN8DUjPuBCKfHo3QgLGcRA
- [ ] モアレ3D形状測定による欠陥観察 ／ 次の3つを行う：①依頼書の空欄（両品の材料・造形条件・切削取り代、モアレ装置名）を埋める ②材技に3点（装置の原理と分解能、凹みのしきい値、10〜20µm の割れの見え方）を確認する ③WinROOF 担当に、040235 と同じしきい値で8枚を処理できるか問い合わせる ／ https://claude.ai/code/session_01CYJnVtWfewxTeYgV1FFRdR
- [ ] M09実践形式まとめ ／ 11/9 の割り付け案と再造形での補完計画をチェックリスト §6 に追加し、progress §7 に順序変更を記録済み。11/9 に PT などを実施し、終わったら結果をセッションに伝える ／ https://claude.ai/code/session_01CYJnVugiBUHase4M39htmJ

## 🟦 外部待ち

## ✅ 完了
- [x] キグチの試験結果におけるCu-10Al降伏応力 ／ Cu-10Al の硬さは HV0.5 で A条件 177HV・C条件 173HV と回答済み（HRB は換算の参考値、比較には HV0.5 を使う）。要対応なし ／ https://claude.ai/code/session_01CYJnVu3nutyZjEwgjtWqMW
