<div align="center"><h3>====== PR ======</h3></div>

## Goal / ゴール

- *`Энэ PR-н өөрчлөлтөөр ямар үр дүнд хүрсэн байх ёстой вэ`*

----

## Related issues / 関連イシュー

- *`Хамааралтай issue линк холбох`*

## Changes / 修正内容

- *`Тухайн PR-ээр ямар зүйлс орж байгааг жагсаан бичих, Жишээ нь:`*
- Google Auth-р sign up хийх боломжтой болсон
- Login дээр Google Auth нэмсэн
- гэх мэт

## Merge steps / マージ方法 

- *`Доорхи нь жишээ бөгөөд өөрийн ажлын агуулгад нийцүүлэн өөрчилнө үү.`*
- **Developer**
  - [ ] check creator-self checklist
  - [ ] summarize check result and evidences
- **Reviewer**
  - review code
  - check reviewer-self checklist
  - approve and merge PR

## Remarks / 備考

`Нэмэлт тайлбар байвал оруулах, Жишээ нь:`
- Google Auth-ийг developer@unimedia.mn дээр XXX project гэж нэмсэн

## Visual changes(evidences) / エビデンス

`Дэлгэц эсвэл хүн хараад мэдэхээр өөрчлөлт орсон бол түүний Screenshot-ууд эсвэл Screen record оруулах`  

## Checklist / チェックリスト
<details>
<summary>🟦 <strong>Checklist for ISSUE / イシューPR用チェックリスト</strong></summary>

## For PR creator / PR作成者向けのチェックリスト
**Доорхи нь стандарт чеклист бөгөөд, PR үүсгэгч тал өөрийн ажлын агуулгад нийцүүлэн өөрчилнө үү.**
- [ ] Have you completed the following checkpoints based on the contents of this PR?
- Have you conducted unit tests in the local environment? / ローカル環境で単体テストを実施していますか。
- Have you documented evidence comparing pre- and post-change results? / 対応前と対応後を比較した結果エビディンスを記載していますか。
- If additional or updated test cases are necessary, have you added or updated them appropriately? / テストケースの追加や更新が必要な場合、適切なテストを追加または更新しましたか。
- Have you ensured that existing tests are not broken by code changes? / コード変更によって既存のテストが壊れないことを確認しましたか。
- Have you confirmed that code changes do not impact related functionalities or modules? / コード変更が関連する機能やモジュールに影響を与えないことを確認しましたか。
- Have you verified that code changes do not impact performance or security? / コード変更によってパフォーマンスやセキュリティに影響を与えないことを確認しましたか。
- If this PR includes a Drizzle migration, does it follow expand/contract (`apps/api/drizzle/README.md`)? No DROP/RENAME/NOT NULL-without-default in the same release as the code that stops using the old shape.

## For PR reviewer / PRレビュアー向けのチェックリスト
**Доорхи нь стандарт чеклист бөгөөд, PR шалгагч тал шалгах ажлын агуулгад нийцүүлэн өөрчилнө үү.**

- [ ] Have you carefully checked the contents of this PR and gone through the checkpoints below?
- Have you confirmed that conflicts are resolved and the code is in a mergable state? / コンフリクトが解決され、コードがマージ可能な状態にあることを確認しましたか。
- Have you ensured that the code after merging is buildable and deployable? / マージ後のコードがビルドおよびデプロイ可能な状態にあることを確認しましたか。
- Are you confirming that the code after merging does not negatively impact the overall quality and performance of the project? / マージ後のコードがプロジェクトの全体的な品質
やパフォーマンスに悪影響を与えないことを確認していますか。
</details>

<details>
<summary>🟥 <strong>Checklist for RELEASE / リリースPR用チェックリスト</strong></summary>

## For PR creator / PR作成者向けのチェックリスト
**Доорхи нь стандарт чеклист бөгөөд, PR үүсгэгч тал өөрийн ажлын агуулгад нийцүүлэн өөрчилнө үү.**
- [ ] Unimedia хөгжүүлэлийн баг, рилийз хийх өөрчлөлтийн тест документыг шалгасан уу?
- [ ] Unimedia хөгжүүлэлийн баг, тестийн дараахи үр дүнг шалгасан уу?
- [ ] Unimedia хөгжүүлэлийн баг, шаарлагаас хамаарч operation тест хийсэн үү?
- [ ] Unimedia operation баг шаардлагаас хамаарч operation тест хийсэн үү?

## For PR reviewer / PRレビュアー向けのチェックリスト
**Доорхи нь стандарт чеклист бөгөөд, PR шалгагч тал шалгах ажлын агуулгад нийцүүлэн өөрчилнө үү.**

- [ ] PR үүсгэгчийн чеклист бүрдсэн байна уу?
- [ ] `develop` бранчаас `master` бранчруу PR үүссэн байна уу?
- [ ] PR-н код нь зөвхөн тухайн рилийзэд хамааралтай бөгөөд өөр код холилдоогүй эсэхийг шалгасан уу?
</details>
