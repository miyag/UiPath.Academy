
UipathCertification Online Quiz & Practical Exam

UiPath認定試験で出題される小テストと実装課題

# 試験

2019年8月現在、問題は全て英語

https://www.uipath.com/ja/academy/certifications


## フェーズ１

小テスト

> Phase I - Theoretical exam (Quiz)
> 
> You can take the quiz anytime. After you comply with the Legal & Payment terms, you have 90 minutes at your disposal to answer 45 multiple answer questions, with a minimum passing score of 70%. You have three attempts to pass the quiz, otherwise a new payment will be required. Keep in mind that you have to wait 24H before attempting to take the quiz again. For each additional attempt, a number of points will be deducted from your score.

- 90分で45問の試験。
  - 100問以上の中からランダムに出題
- 70％（32問）の正解で合格
  - 24時間おきに合計3回の試験を受けられる
- 問題構成は下記の通り
  - Foundation Questions 10
  - Orchestrator Questions 10
  - Advanced Training Questions 25


回答集） [quiz.md](https://github.com/miyag/Uipath_Academy/blob/master/AdvancedCertification/CertificationQuiz/quiz.md) （全103問を記録）

## フェーズ２

実装課題

> Phase II - Practical exam
>
> You have 3 hours at your disposal to solve the exercise displayed, with a minimum passing score of 70%. Keep in mind that there are only three attempts to pass the practical exam, otherwise a new voucher will be required.
>
> You have 3h30m at your disposal to solve the exercise displayed, with a minimum passing score of 70%. Keep in mind that there are only three attempts to pass the practical exam, otherwise a new voucher will be required. Last but not least, you have to wait 24 H before attempting to take the exam again.

- 開始から３時間以内に提出
  - 再提出は不可（再度、試験を受け直す必要あり）
- 実行結果の成功率などから判定し、70%のスコアで合格
- 不合格の場合、再試験が可能（3回まで）
  - ただし、24時間は再試験が受けられない
- 課題は３パターンの中から出題
  - チェック対象の都市名や出力フォーマットなどが少し変わるが、大筋は３パターン
- 2019年12月末までは、試験料が無料
  - 試験料は1万円
  
回答集） 

- [InvoiceCheck](https://github.com/miyag/Uipath_Academy/tree/master/AdvancedCertification/CertificationExam_InvoiceCheck)
  - Transactionltemのdatatypeは「Queueltem」
  - Dispatcher（ジョブ登録）とPerformer（ジョブ実行）を作成し、Invoiceの内容をチェック
- [VendorCheck](https://github.com/miyag/Uipath_Academy/tree/master/AdvancedCertification/CertificationExam_VendorCheck)
  - TransactionItemのdatatypeは「DataRow」
  - Vendorの内容をチェックし、チェックOKの内容をExcelに出力
- [WorkItemCheck](https://github.com/miyag/Uipath_Academy/tree/master/AdvancedCertification/CertificationExam_WorkItemCheck)
  - Transactionltemのdatatypeは「String」
  - WorkItems内容をチェックし、チェックOKの内容をExcelに出力
