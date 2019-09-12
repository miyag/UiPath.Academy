# FoundationTraining MiniTest

Level 1 - Foundation (基礎)トレーニング 小テスト


## Lesson-1

UiPath概要

### 1.1

Q) UiPath Studio で既存のアクティビティ以外のアクティビティを作成することはできますか？
- [o] はい、カスタムアクティビティとして作成することができます
- [-] いいえ、既存のアクティビティに制限されています

Q) Are you restricted to the existing activities in UiPath Studio?
- [o] No, you can create and use Custom Activities.
- [-] Yes, you are restricted to the existing activities.
- [o] No, you can download more activities via the Package Manager and UiPath Go!

---
### 1.2

Q) プロセスのスケジュール設定には、どれを使用しますか？
- [-] UiPath Robot
- [-] UiPath Studio
- [o] UiPath Orchestrator

Q) Scheduling a process is done from:
- [-] UiPath Robot.
- [-] UiPath Studio.
- [o] Orchestrator Server.

---
### 1.3

Q) [レコーディング(Recording)]の記録された操作は何に変換されますか？
- [-] 新規のUiPath Robot
- [o] レコーディングされた各ステップのアクティビティを含むシーケンス
- [-] [プロセス(Process)]

Q) What is the output of a recording session?
- [-] A new robot.
- [o] A sequence with an activity for each recorded step.
- [-] A process.

---
### 1.4

Q) UiPath Orchestrator に[プロセス(Process)]を送信する方法はなんですか?
- [-] 各ファイルを UiPath Orchestrator に手動でアップロードします
- [-] プロセスファイルを使用して、管理者にメールを送信します
- [o] [パブリッシュ(Publish)]を使用して、UiPath Studio から直接送信します

Q) ）How can you Publish a process to the Orchestrator server?
- [-] Manually upload each file to Orchestrator Server.
- [-] Send an email to the administrator with the process files.
- [o] Directly from UiPath Studio, with the Publish functionality.

---
### 1.5

Q) UiPath から自動的にメールを送信することはできますか？
- [o] はい
- [-] いいえ

Q) Can you send an email from UiPath, automatically?
- [o] Yes
- [-] No

---
### 1.6

Q) UiPath の [データスクレイピング (Data Scraping)] のは何ですか？(該当するものをすべて選択してください)
- [o] ウェブページから表形式データを抽出する
- [o] ウェブページからリスト・または構造化データを抽出する
- [-] ウェブページからすべての情報を抽出する

Q) What web scraping capabilities can UiPath implement? 
- [o] Extracting the content of a table from a webpage.
- [o] Extracting lists or other structured data from a webpage.
- [o] Extracting text based content from a webpage
- [-] Extracting image content from a webpage.

---
### 1.7

Q) 同じ[プロセス(Process)]を同時に複数実行することはできますか？
- [o] はい、別の UiPath Robotで実行できます
- [-] はい、同じ UiPath Robotで実行できます
- [-] いいえ

Q) Can you run multiple instances of the same process, in parallel?
- [o] Yes, on different robots.
- [-] Yes, on the same robot.
- [-] No.

---
### 1.8

Q) 再利用可能なコンポーネントとは何ですか？(該当するものをすべて選択してください)
- [-] 人の手によってプロセスを実行する行為
- [-] Orchestrator サーバーの機能
- [o] 共通部品として、他のプロセス(Process)に対しても実装が可能であるワークフロー

Q) What is a reusable component?
- [-] The artifact of a Publish operation.
- [-] A functionality of the Orchestrator server.
- [o] A workflow that implements a very common action repeated throughout all your automations.

---

## Lesson-2

入門知識

---
### 2.1

Q) [変数] パネルから変数の名前を変更すると、どうなりますか？
- [-] 変数の範囲が変更されます
- [-] その変数を使用するすべてのアクティビティの名前を更新する必要があります
- [o] その変数を使用するすべてのアクティビティで名前が自動的に更新されます
- [-] 変数の名前を変更することはできません。削除してから、新しい名前を作成する必要があります

Q) What happens if you rename a variable from the Variables tab?
- [-] The scope of the variable will change.
- [-] You need to update the name in all activities that use that variable.
- [o] The name will be automatically updated in all the activities that use it.
- [-] You cannot rename a variable: you need to delete it and create a new one.

---
### 2.2

Q) UiPath Studio で使用できるワークフローのタイプは何ですか？
- [o] フローチャート (Flowchart)
- [-] アクティビティ (Activity)
- [o] シーケンス (Sequence)
- [o] ステートマシン (Statemachine)

Q) Which of these are workflow types available in UiPath Studio?
- [o] Flowchart
- [-] Activity
- [o] Sequence
- [-] REFramework

---
### 2.3

Q) 文字列の配列を反復処理できるようにするアクティビティはどれですか？
- [o] 繰り返し(前判定) (While)
- [-] 繰り返し(各行) (ForEachRow)
- [o] 繰り返し(後判定) (DoWhile)
- [o] 繰り返し(コレクションの各要素) (ForEach)

Q) Which activity can you use if you want to loop through a collection of items?
- [-] Flow Decision activity
- [-] If activity
- [-] Assign activity
- [o] For Each activity

---
### 2.4

Q) 配列内に保存できるデータ型は何ですか？
- [o] ブーリアン (Boolean) 型
- [o] 文字列 (String) 型
- [o] Double
- [o] 整数 (Integer) 型

Q) What data types can be stored inside an array?
- [o] Boolean
- [o] String
- [o] Double
- [o] Integer

---
### 2.5

Q) [メッセージボックス (MessageBox)] ウィンドウ内には 整数 (Integer) 値、myNumber をどのように表示できますか？
- [-] “My number is “ + myNumber.Value
- [-] “My number is ” + myNumber
- [o] “My number is “ + myNumber.ToString
- [-] “My number is $myNumber”

Q) How can you display an Integer value, myNumber, inside a Message Box window?
- [-] “My number is “ + myNumber.Value
- [-] “My number is ” + myNumber
- [o] “My number is “ + myNumber.ToString
- [-] “My number is $myNumber”

---
### 2.6

Q) 2 つの ジェネリック (Generic) 変数 (A (値 “123”) と B (値 456)) がある場合、A + B の [1 行を書き込み (WriteLine)] 出力はどのようになりますか？
- [-] 123 + 456
- [o] 123456
- [-] 579
- [-] 例外とされます

Q) Given two Generic variables, A with value “123” and B with value 456, what would the Write Line output of A + B be?
- [-] 123 + 456
- [o] 123456
- [-] 579
- [-] An exception will be thrown.

---
### 2.7
 
Q) ジェネリック (Generic) 型の変数内に保存できるコンテンツの型はどれですか？
- [o] 数字
- [o] テキスト
- [o] 日付
- [o] True／False

Q) What type of content can you store inside a Generic type variable? 
- [o] Numbers
- [o] Text
- [o] Dates
- [o] True/False

---
### 2.8

Q) 判別をシーケンス内に表すように設計されているアクティビティは何ですか？
- [-] [代入 (Assign)]
- [-] [トライキャッチ (Try Catch)]
- [o] [条件分岐 (If)]
- [o] [フロー条件分岐 (Flow Decision)]

Q) Which activity designed to represent a decision inside a Sequence?
- [-] The Assign activity
- [-] The Try Catch activity
- [o] The If activity
- [o] The Decision activity

---
### 2.9

Q) テキストを保存できる変数の型はどれですか？
- [-] Double
- [o] 文字列 (String) 型
- [o] ジェネリック (Generic) 型
- [-] 整数 (Integer) 型

Q) In which variable types can you store text? 
- [-] Double
- [o] String
- [o] Generic
- [-] Integer

---

Q) Can you insert a Flowchart activity in a Sequence activity?
- [-] No
- [o] Yes

---
### 2.10

Q) What kind of workflow should you use when performing multiple activities in a fixed sequential order? 
- [o] Sequence
- [-] State machine
- [-] Flowchart
- [-] None of the options

---
### 2.11

Q) When should you use the Flowchart workflow?
- [o] When having a process with many decision blocks
- [-] When modelling a process that has loops to previous states
- [-] When having multiple activities executed in a fixed order

---

## Lesson-3

データ操作

---
### 3.1
 
Q) コレクションカテゴリに含まれるデータ型は、次のうちどれですか？
- [-] Int32
- [o] Array
- [o] List
- [o] Dictionary

Q) Which of the following data types are included in the Collections category?
- [-] Int32
- [o] Array
- [o] List
- [o] Dictionary

---
### 3.2
 
Q) どのようにしてデータテーブルの列を識別することができますか？ (該当するものすべてを選択してください)
- [-] 行のインデックスを使用する
- [-] 行名を使用する
- [o] 列のインデックスを使用する
- [o] 列名を使用する

Q) How can you identify a column in a data table?(Select all that apply.)
- [-] Using the row index
- [-] Using the row name
- [o] Using the column name
- [o] Using the column index

---
### 3.3
 
Q) dtNewHires データテーブルに、[ID, Name, Age, Sex] という順序の 4 つの列と[1, Daniel, 38, M] ; [2, Andra, 24, F] という 2 つの行がある場合、dtNewHires.Rows(0)(1) 式の結果はどうなりますか？ (該当するものをすべて選択してください)
- [o] Daniel
- [-] Andra
- [-] 2
- [-] 1

Q) If the dtNewHires datatable has 4 columns, in this order : [ID, Name, Age, Sex] and 2 rows: [1, Daniel, 38, M] ; [2, Andra, 24, F], what is the result of the expression dtNewHires.Rows(0)(1)?
- [o] Daniel
- [-] Andra
- [-] 2
- [-] 1

---
### 3.4
 
Q) 指定された住所 (fullAddress という文字列変数) が特定の通り (streetName という文字列変数) で見つけることができるかどうかをテストするにはどうすればよいですか？
- [-] streetName.Has(fullAddresss)
- [-] streetName.Contains(fullAddress)
- [-] fullAddress.Has(streetName)
- [o] fullAddress.Contains(streetName)

Q) How can we test if a given address (a string variable called fullAddress) can be found on a particular street (a string variable called streetName)?
- [-] streetName.Has(fullAddresss)
- [-] streetName.Contains(fullAddress)
- [-] fullAddress.Has(streetName)
- [o] fullAddress.Contains(streetName)

---
### 3.5
 
Q) アクティビティのプロパティフィールドから変数を自動的に作成するためのキーの組み合わせを選択してください
- [-] Ctrl + N
- [-] Ctrl + P
- [-] Ctrl + A
- [o] Ctrl + K

Q) What key combination allows you to automatically create a variable from an activity’s property field?
- [-] Ctrl + N
- [-] Ctrl + P
- [-] Ctrl + A
- [o] Ctrl + K

---
### 3.6
 
Q) ワークフローの中で現在の時間を効率的に保存するために使用できる変数の型は何ですか？
- [-] String
- [o] DateTime
- [-] Array
- [-] Integer

Q) Which variable type can you use to efficiently store the current time inside your workflows?
- [-] String
- [o] DateTime
- [-] Array<String>
- [-] Integer

---
### 3.7
 
Q) myString という文字列変数を、将来使用するために、すべて大文字に変換するにはどうすればよいですか？
- [o] アクティビティは [代入 (Assign)] を使用し、 [左辺値 (To)] に myString を入力し、[右辺値 (Value)] に myString.ToUpper を入力します
- [-] アクティビティは [メソッドを呼び出し (InvokeMethod)] を使用し、プロパティの [ターゲット型 (TargetType)] を String 、[ターゲットオブジェクト (TargetObject)] を myString 、[メソッド名 (MethodName)] を ToUpper に設定します
- [-] アクティビティは [１行を書き込み (WriteLine)] を使用し、プロパティの [テキスト (Text)] に myString ToUpper を設定します

Q) How can a string variable called myString be converted to an all-capitals representation for future use?
- [o] By using an Assign activity with myString on the left side and myString.ToUpper on the right side.
- [-] By using an Invoke Method activity with the TargetType property set to String, the TargetObject property set to myString and the MethodName property to ToUpper.
- [-] By using an Invoke Method activity with the TargetType property set to null, the TargetObject property set to myString and the MethodName property to ToUpper.
- [-] By using a Write Line with the Text property set to myString.ToUpper.

---
### 3.8
 
Q) データテーブルから各行をループ処理するために使用できるアクティビティはどれですか？ (該当するものをすべて選択してください)
- [-] データテーブルを構築 (BuildDataTable)
- [-] 条件分岐 (If)
- [-] フロー条件分岐 (Flow Decision)
- [o] 繰り返し(各行) (ForEachRow)

Q) Which activity can be used to loop through each row from a DataTable?
- [-] Build DataTable
- [-] If
- [-] Flow Decision
- [o] For Each Row

---
### 3.9
 
Q) Index Integer 変数を [メッセージボックス (MessageBox)] 内に表示するには、どのようにすればよいですか？
- [-] “Current index is: $index”
- [-] “Current index is: “ + index
- [o] “Current index is: “ + index.ToString
- [-] “Current index is: + index.ToString”

Q) How can the index integer variable be displayed inside a Message Box activity?
- [-] “Current index is: $index”
- [-] “Current index is: “ + index
- [o] “Current index is: “ + index.ToString
- [-] “Current index is: + index.ToString”

---
### 3.10
 
Q) リストと配列についての正しい説明はどれですか？
- [o] 繰り返し(コレクションの各要素) (ForEach)を使用してリストを反復処理することができます
- [o] 配列とリストの要素には、インデックスを使用してアクセスできます
- [-] 任意の数の要素を配列に追加することができます
- [o] コレクションに追加 (AddToCollection) を使用してリスト項目を追加することができます

Q) Which of the following statements are true regarding Lists and Arrays? 
- [o] You can iterate through a List using a For Each loop activity.
- [o] Array and List elements can be accessed by index.
- [-] You can add maximum 100 elements to an array.
- [o] List items can be added using an Add to Collection activity.

---
### 3.11
 
Q) CurrentRow が、Name および Age の順序の2つの列を含むデータテーブルの行を表している場合は、Age 列から値を取得するためにどのような式を使用できますか？ (該当する項目をすべて選択してください)
- [o] currentRow("Age")
- [o] currentRow(1)
- [-] currentRow.Age
- [-] currentRow(2)

Q) If currentRow represents a row from a DataTable with two columns in this order: Name and Age, which expressions can be used to obtain the value from the column Age?(Select all that apply.)
- [o] currentRow("Age")
- [o] currentRow(1)
- [-] currentRow.Age
- [-] currentRow(2)

---
### 3.12
 
Q) Output DataTable [データテーブルを出力 (OutputDataTable)] (該当するものをすべて選択してください)
- [-] データテーブルを Excel ファイルに書き込みます
- [o] データテーブルに格納されているデータを csv 形式の文字列として返します
- [-] データテーブルオブジェクトを返します
- [-] データテーブルを csv ファイルに書き込みます

Q) Which of the following statements are true regarding the Output DataTable activity?
- [-] Writes a DataTable to an Excel file
- [o] Returns the data contained in a DataTable as a string in a csv format
- [-] Returns a DataTable object
- [-] Writes a DataTable to a csv file

---
### 3.13
 
Q) [CSVを読み込む (ReadCSV)] の出力としてどの型の変数を使用できますか？
- [o] DataTable 変数
- [-] List 変数
- [-] Array 変数
- [-] String 変数

Q) Which variable types can be used as output for the Read CSV activity?
- [o] DataTable variables
- [-] List<DataRow> variables
- [-] Array<DataRow> variables
- [-] String variables

---
### 3.14
 
Q) データテーブルの既存のセルの値を変更するには、どのアクティビティを使用できますか？ (該当するものをすべて選択してください)
- [o] [代入 (Assign)]
- [-] Modify Cell アクティビティ
- [-] [データ列を追加 (AddDataColumn)]
- [-] [データ行を追加 (Add Data Row )]

Q) Which activity can be used to modify the value of an existing cell in a DataTable?
- [o] Assign activity
- [-] Modify Cell activity
- [-] Add Data Column activity
- [-] Add Data Row activity

---
### 3.15
 
Q) データベースオブジェクトのどの .Net メソッドを使用して条件によってテーブルをフィルタリングすることができますか？ (該当する項目をすべて選択してください)
- [-] Clone
- [-] Filter
- [o] Select
- [-] ToString

Q) Which .Net method of the datatable object can be used to filter a table by a condition?
- [-] Clone
- [-] Filter
- [o] Select
- [-] ToString

---
### 3.16
 
Q) 特定のデータテーブルの行の特定のセルから値を取得するには、どのようなアクティビティを使用できますか？(該当するものをすべて選択してください) 
- [-] セルを書き込む (WriteCell)
- [-] セルを読み込む (ReadCell)
- [o] 行項目を取得 (GetRowItem)
- [-] データ行を削除 (RemoveDataRow)

Q) Which activity can you use to get the value from a certain cell, from a specific data table row? 
- [-] Write Cell
- [-] Read Cell
- [o] Get Row Item
- [-] Remove Data Row

---
### 3.16

Q) The String.Format(“Input = {0} and Output = {1}”, “1”,”2”) expression returns which of the following text:
- [-] Input = 1 and Output = 1
- [-] Input = {0} and Output = {1}
- [-] Input = 0 and Output = 0
- [o] Input = 1 and Output = 2


## Lesson-4

レコーディング機能

---
### 4.1
 
Q) レコーディングを停止するには、どうすればよいですか？(該当するものをすべて選択してください)
- [-] F12 キー
- [-] Esc キーを押してダブルクリック
- [o] Esc キー
- [-] F4 キーと Del キー

Q) How do you stop the recording?
- [-] F12
- [-] Escape and Double click
- [o] Escape
- [-] F4 and Delete

---
### 4.2
 
Q) 仮想マシンのアクションを自動化するために使用するレコーディング機能は何ですか？
- [-] [デスクトップレコーディング (DesktopRecording)]
- [-] [ウェブレコーディング (WebRecording)]
- [o] [Citrixレコーディング (CitrixRecording)]
- [-] [ベーシックレコーディング (BasicRecording)]

Q) Which recording wizard would you use to automate Virtual Machine actions? 
- [-] Desktop Recording
- [-] Web Recording
- [o] Citrix Recording
- [-] Basic Recording

---
### 4.3
 
Q) ウェブアプリケーションの開始をレコーディングするには、どうすればよいですか？(該当するものをすべて選択してください)
- [o] [レコーディング (Recording)] - [ウェブ (Web)] - [ブラウザーを開く (OpenBrowser)] をクリックして、ブラウザを選択する
- [-] [レコーディング (Recording)] - [ベーシック (Basic)] - [アプリを開始 (Start App)] をクリックして、ブラウザを選択する
- [-] [アプリケーションを開く (OpenApplication)] を使用する

Q) How can you record the start of a Web application?
- [o] Hit Record - Web - Open Browser - select browser
- [-] Hit Record - Basic - Start App - select browser
- [-] Use the open Application activity

---
### 4.4
 
Q) 自動レコーダーに関する次の文の中で正しいものはどれですか？(該当するものをすべて選択してください)
- [o] 文字を入力 (TypeInto)を生成できる
- [o] UI 自動化構造を作成する
- [o] さまざまな種類の UI コントロールを認識できる
- [o] クリック (Click)を生成できる

Q) Which of the following statements regarding the Automatic Recorder are true:(Select all that apply.)
- [o] Creates a skeleton for UI automation
- [o] Can generate Type Into activities
- [o] Can recognize different types of UI controls
- [o] Can generate Click activities

---
### 4.5
 
Q) ウェブレコーディングで生成されるコンテナー (Container)の種類は何ですか？
- [-] [コンテナ (Container)] は生成されない
- [-] [ウィンドウにアタッチ (AttachWindow)]
- [-] [Excel アプリケーションスコープ (ExcelApplicationScope)]
- [o] [ブラウザーにアタッチ (AttachBrowser)]

Q) Which container will Web Recording generate?
- [-] No container
- [-] Attach Window
- [-] Excel Application Scope
- [o] Attach Browser

---
### 4.6
 
Q) デスクトップレコーディングの使用を推奨するタイミングはいつですか？(該当する項目をすべて選択してください)
- [o] 同じウィンドウで多くのステップを自動化するとき
- [-] Citrix アプリケーションを自動化するとき
- [-] ウェブページを自動化するとき
- [-] 1つのステップを自動化するとき

Q) When is it recommended to use Desktop recording?
- [o] When you automate more steps in the same window
- [-] When you automate Citrix Applications
- [-] When you automate Web pages
- [-] When you automate one step

---
### 4.7
 
Q) 同じレコーディングシーケンスで、自動レコーディングと手動レコーディングを結合できますか？
- [o] はい
- [-] いいえ

Q) Can you combine automatic recording with step-by-step recording in the same recording sequence?
- [o] Yes
- [-] No

---
### 4.8
 
Q) 自動レコーディングを一時停止するには、どうすればよいですか？
- [o] F2 キーを押す
- [-] 右クリックする
- [-] 画面の右隅をクリックする
- [-] Esc キーを押す

Q) How can you delay the Automatic Recording?
- [o] By hitting the F2 key
- [-] By right clicking
- [-] By clicking in the right corner of the screen
- [-] By hitting the Escape key

---
### 4.9
 
Q) アクティビティをワークフローに追加するには、どうすればよいですか？(該当するものをすべて選択してください)
- [o] アクティビティパネルからドラッグアンドドロップして追加する
- [o] 自動レコーダーを使用して追加する
- [o] 手動レコーディングを使用して追加する

Q) How do you add activities to a workflow?(Select all that apply.)
- [o] From the Activities Panel by dragging and dropping
- [o] Using Automatic Recorder
- [o] From the Step by Step Recording Action pane

---
### 4.10
 
Q) 自動レコーディングを使用してレコーディングできるアクションは何ですか？
- [o] [文字を入力 (TypeInto)]
- [-] [画面スクレイピング (ScreenScraping)]
- [-] [テキストをコピー (CopyText)]
- [o] [クリック (Click)]

Q) Which actions can you record using Automatic Recording? 
- [o] Type Into
- [-] Screen Scraping
- [-] Copy text
- [o] Click

---
### 4.11
 
Q) ベーシックレコーディングで生成されるコンテナーの種類は何ですか？
- [-] [ブラウザーにアタッチ (AttachBrowser)]
- [-] [ウィンドウにアタッチ (AttachWindow)]
- [-] [Excel アプリケーションスコープ (ExcelApplicationScope)]
- [o] [コンテナ (container)]は生成されない

Q) Which container will Basic Recording generate?
- [-] Attach Browser
- [-] Attach Window
- [-] Excel Application Scope
- [o] No container

---
### 4.12
 
Q) セレクターのサポートを提供していないアプリケーションで UI インタラクションを自動化するには、どのレコーディング機能を使用しますか
- [-] [デスクトップレコーディング (DesktopRecording)]
- [o] [Citrixレコーディング (CitrixRecording)]
- [-] [ベーシックレコーディング (BasicRecording)]
- [-] [ウェブレコーディング (WebRecording)]

Q) Which recording wizard would you use to automate UI interactions in an application where elements can not be selected individually?
- [-] [Desktop Recording
- [o] Citrix Recording
- [-] [Basic Recording
- [-] [Web Recording


---
### 4.13
 
Q) What recording profiles are available in UiPath Studio?
- [-] Automatic recording and Step by Step recording
- [o] Basic, Desktop, Web, Citrix
- [-] Click, Check, Type Into and Select Item


---

## Lesson-5

UI上の高度な操作

---
### 5.1
 
Q) デスクトップアプリケーションの青い背景に書かれた白色のテキストを抽出する場合、どの方法が最適ですか？(該当するものをすべて選択してください)
- [-] Microsoft OCR エンジンを使用する
- [-] Google OCR エンジンのプロパティ [白黒反転 (Invert)] にチェックを付けて使用する
- [o] [フルテキスト (FullText)] メソッドを使用する
- [-] Google OCR エンジンを使用する

Q) What is the best method to extract white text written on blue background in a desktop app?
- [-] By using the Microsoft OCR engine
- [-] By using the Google OCR engine with Invert flag
- [o] By using the FullText method
- [-] By using the Google OCR engine

---
### 5.2
 
Q) Citrix の青い背景に書かれている白色のテキストを抽出する方法は？(該当するものをすべて選択してください)
- [-] [ネイティブ (Native)] メソッドを使用する
- [o] Microsoft OCR エンジンのプロパティ [白黒反転 (Invert)] にチェックを付けて使用する
- [-] [フルテキスト (FullText)] メソッドを使用する
- [-] [テキストを取得 (GetText)] を使用する

Q) How can you extract white text written on blue background in Citrix?
- [-] By using the Native Method
- [o] By using the Microsoft OCR engine invert property
- [-] By using FullText method
- [-] By using Get Text

---
### 5.3
 
Q) [フルテキスト (FullText)] メソッドを使用しているときに、そのロボットは非表示情報を無視するようにプログラムすることができますか？
- [o] はい
- [-] いいえ

Q) Can the robot be programed to ignore taking hidden information while using the Full Text method?
- [o] Yes
- [-] No

---
### 5.4
 
Q) [OCR] メソッドの主な利点を選択してください
- [-] そのアプリケーションがバックグラウンドで実行されている場合でも動作する
- [o] 仮想環境で実行されているものも含めて、すべてのアプリケーションで動作する
- [-] 高速である

Q) The main advantage of the OCR method is:
- [-] It works even if the application is running in the background.
- [o] It works on every application even if it’s running in a virtual environment.
- [-] It’s fast.

---
### 5.5
 
Q) [ウィンドウにアタッチ (AttachWindow)] は何に使用しますか？(該当するものをすべて選択してください)
- [-] バックグラウンドで自動化しようとすることを示す
- [-] ブラウザで作業していることを示す
- [-] Java ウィンドウで作業していることを示す
- [o] 現在作業しているウィンドウを識別する

Q) What is the Attach Window activity used for? 
- [-] Specifies that you want to automate in background.
- [-] Specifies that you are working with a browser.
- [-] Specifies that you are working with a Java window.
- [o] Identifying the window you are working with.

---
### 5.6
 
Q) ウェブデータスクレイピングウィザードは、何に使用しますか？(該当するものをすべて選択してください)
- [-] 1つのUI要素からのテキストの抽出
- [-] ウェブページの操作の自動化
- [o] ウェブまたは他のアプリケーションからのテーブル全体の抽出
- [o] ウェブまたは他のアプリケーションからの関連データの抽出

Q) What is the Data Scraping wizard for?(Select all that apply.)
- [-] Extracting text from one UI element
- [-] Automating interactions with web pages
- [o] Extracting whole tables from the web or other applications
- [o] Extracting correlated data from the web or other applications

---
### 5.7
 
Q) テキストの位置を保持できるテキスト抽出メソッドを選択してください
- [o] [ネイティブ (Native)]
- [o] [OCR]
- [-] [フルテキスト (FullText)]

Q) Which of the following text scraping methods preserve the text position?
- [o] Native
- [o] OCR
- [-] FullText

---
### 5.8
 
Q) ウェブページからの抽出に最適なアクティビティはどれですか？ (該当するものをすべて選択してください)
- [o] [DataScrapingWizard (データスクレイピングウィザード)]
- [-] [OCRでテキストを取得 (GetOCRText)]
- [-] [表示中のテキストを取得 (GetVisibleText)]

Q) Which is the best option for scraping tables from a web page?
- [o] Data scraping wizard
- [-] Get OCR Text
- [-] Get Visible Text

---
### 5.9
 
Q) テキストの位置を取得するために使用できるテキスト抽出方法は何ですか？(該当するものをすべて選択してください)
- [-] [フルテキスト (FullText)]
- [-] 共有クリップボード
- [o] [ネイティブ (Native)]
- [o] [OCR]

Q) Which text extraction method can you use to get text position? (Select all that apply.)
- [-] FullText
- [-] Shared Clipboard
- [o] Native
- [o] OCR

---
### 5.10
 
Q) Google の複数のページから結果を取得する場合、どの方法が最適ですか？
- [o] [DataScraping (データスクレイピング)] (構造化されたデータで動作し、データテーブルを返すことができるため)
- [-] [フルテキスト (FullText)] メソッドを使用するスクリーンスクレイピング (テキスト全体を取得するため)
- [-] [ネイティブ (Native)] メソッド (バックグラウンドで動作するため)

Q) What would be the best method to retrieve results from multiple Google pages?
- [o] Data Scraping, because it can operate with structured data and return a data table.
- [-] Screen scraping by using the FullText method because it retrieves the entire text.
- [-] Native, because it works in the background.

---
### 5.11
 
Q) 最も低速なテキストの読み取り方法はどれですか？(該当するものをすべて選択してください)
- [-] [ネイティブ (Native)]
- [-] [フルテキスト (FullText)]
- [o] [OCR]
- [-] 上記のどれでもない

Q) What is the slowest method of reading text?
- [-] Native
- [-] FullText
- [o] OCR
- [-] None of the options

---
### 5.12
 
Q) [フルテキスト (FullText)] メソッドを使用してロボットができることは？
- [o] 編集可能なテキストを取得する
- [-] フォント情報 (サイズ、色) を取得する
- [o] 表示されるテキスト全体を取得する
- [o] 非表示情報を取得する

Q) By using the Full Text scraping method, the robot is able to:
- [o] Get hidden information.
- [-] Get font information (size, colour).
- [o] Get the entire visible text.
- [o] Get editable text.

---
### 5.13
 
Q) [デフォルト(Default)] の入力(Input)メソッドを使用する場合のデメリットは？
- [o] アプリケーションがアクティブでなければならない
- [-] アプリケーションがバックグラウンドで実行されていなければならない
- [o] 低速である

Q) The downsides of using the Default input method are: 
- [o] The condition that the application must be active.
- [-] The condition that the application must be running in background.
- [o] Low speed.

---
### 5.14
 
Q) [フルテキスト (FullText)] メソッドの最も重要な利点を選択してください
- [o] 正確である
- [o] バックグラウンドで動作する
- [-] Citrix 環境で動作する
- [o] 高速である

Q) The most important advantages of the FullText method are:
- [o] It’s accurate.
- [o] It works in the background.
- [-] It works in Citrix environments.
- [o] It’s fast.

---

## Lesson-6

セレクター

---
### 6.1
 
Q) 「*」は何文字で置き換えられますか？
- [-] 2文字以上
- [o] 0文字以上
- [-] 0文字

Q) How many characters does “*” replace?
- [-] Zero or more
- [o] More than one
- [-] Zero

---
### 6.2
 
Q) UiPath Studioのセレクターでサポートされているワイルドカード文字は何ですか？
- [-] $
- [-] &
- [o] ?
- [o] *

Q) What are the supported wildcard characters for selectors in UiPath Studio? 
- [-] $
- [-] &
- [o] ?
- [o] *

---
### 6.3
 
Q) 次のうち、有効な完全セレクターはどれですか？
- [o] <wnd app='explorer.exe' cls='Shell_TrayWnd' /> <br><wnd cls='Start' title='Start' >
- [-] <wnd app=’*' />
- [o] <html app='chrome.exe' title='Yahoo Finance' > <br><webctrl idx='1' parentid='data-util-col' tag='TABLE' > <br><webctrl isleaf='1' tableRow='3' tag='TD' >
- [-] <webctrl isleaf='1' tableRow='3' tag='TD' /><wnd cls='Start' title='Start' /><wnd app=’*' />

Q) 
Which of the following is a valid full selector?
- [o] <wnd app='explorer.exe' cls='Shell_TrayWnd' /> <wnd cls='Start' title='Start' />
tag='TABLE' />
- [-] <wnd app=’*' />
- [o] <html app='chrome.exe' title='Yahoo Finance' > <br><webctrl idx='1' parentid='data-util-col' tag='TABLE' > <br><webctrl isleaf='1' tableRow='3' tag='TD' >
- [-] <wnd cls='Start' title='Start' />

---
### 6.4
 
Q) 2017年の日付でのみ動作するようにするには、次のカレンダーページセレクターをどのように修正すればよいですか？
- [-] "\<html app='chrome.exe' title='UiPath - Calendar - Week of ?????, 2017' />”
- [-] “\<html app='chrome.exe' title='UiPath - Calendar -* 201?'/> “
- [-] “\<html app='chrome.exe' title='UiPath - Calendar - * />”
- [o] “\<html app='chrome.exe' title='UiPath - Calendar - * 2017' />”

Q) How can you improve the following calendar page selector to work only for dates in 2017? “<html app='chrome.exe' title='UiPath - Calendar - Week of May 1, 2017' />”
- [-] "\<html app='chrome.exe' title='UiPath - Calendar - Week of ?????, 2017' />”
- [-] "\<html app='chrome.exe' title='UiPath - Calendar -* 201?' /> “
- [-] "\<html app='chrome.exe' title='UiPath - Calendar - * />”
- [o] "\<html app='chrome.exe' title='UiPath - Calendar - * 2017' />

---
### 6.5
 
Q) これは、動的ページ「webctrl idx='144' tag='IMG'/」の信頼性の高いセレクターです
- [-] 正しい
- [o] 正しくない

Q) This is a reliable selector for a dynamic page: "webctrl idx='144' tag='IMG'/"
- [-] True
- [o] False

---
### 6.6
 
Q) 完全セレクターは [ウィンドウにアタッチ (AttachWindow)] または [アプリケーションを開く (OpenApplication)] のコンテナー内で使用できますか？
- [o] はい
- [-] いいえ

Q) Can full selectors be used inside a container (Attach Window or Open Application activities)?
- [o] Yes
- [-] No

---
### 6.7
 
Q) 部分セレクターは [ウィンドウにアタッチ (AttachWindow)] または [アプリケーションを開く (OpenApplication)] のコンテナー内で使用できますか？
- [o] はい
- [-] いいえ

Q) Can partial selectors be used inside a container (Attach Window or Open Application activities)?
- [o] Yes
- [-] No

---
### 6.8
 
Q) 動的セレクターを構築するために変数を使用できますか？
- [o] はい
- [-] いいえ

Q) Can variables be used to build dynamic selectors?
- [o] Yes
- [-] No

---
### 6.9
 
Q) 有効なセレクターで、画面上の異なる要素を同時に識別できますか？
- [-] はい
- [o] いいえ

Q) Can a valid selector identify different elements on the screen at the same time?
- [-] Yes
- [o] No

---
### 6.10
 
Q) これは、動的ページ「webctrl idx='144' tag='IMG'/」の信頼性の高いセレクターです
- [-] 正しい
- [o] 正しくない

Q) This is a reliable selector for a dynamic page: "webctrl idx='144' tag='IMG'/"
- [-] True
- [o] False

---
### 6.11
 
Q) UiExplorer の用途は何ですか？(該当するものをすべて選択してください)
- [o] セレクターを作成して微調整する
- [o] UI ツリーを調べる
- [-] UiExplorerはUiPathのコンポーネントではない
- [-] ワークフローツリーを調べる

Q) What is UiExplorer used for? (Select all that apply.)
- [o] To create and fine tune selectors
- [o] To explore the UI tree
- [-] UiExplorer is not a component of UiPath
- [-] To explore the workflow tree

---
### 6.12
 
Q) セレクターを改善するには、どうすればよいですか？(該当するものをすべて選択してください)
- [-] idx属性があることを確認する
- [-] 動的な値を持つ属性を追加する
- [o] 変数属性の部分を「*」に置き換える
- [o] 可能であれば、安定した属性のみを選択する

Q) How can you improve a selector?(Select all that apply.)

- [-] By making sure you have an idx attribute
- [-] By adding attributes with dynamic values
- [o] By replacing variable attribute parts with *
- [o] By picking only the stable attributes, if possible

---
### 6.13
 
Q) [アンカーベース (AnchorBase)] について、正しい説明は次のうちどれですか？
- [o] アンカーとターゲット要素の画面の位置を使用する
- [-] アプリケーションの構造を使用して、ターゲット要素を検索する
- [-] バックグラウンドで動作する

Q) Which of the following is true regarding the Anchor Base activity?
- [o] Use the screen position of the anchor and the target element.
- [-] Use the structure of the application to find the target element.
- [-] It works in background.

---
### 6.14
 
Q) “nav”タグの有効なオプションは、次のうちどれですか？
- [o] “Next”
- [o] “Prev”
- [o] “Up”

Q) Which of the following are valid options for the “nav” tag?

- [o] “Next”
- [o] “Prev”
- [o] “Up”

---
### 6.15
 
Q) [ハイライト (Highlight)] の用途は何ですか？(該当するものをすべて選択してください)
- [o] セレクターを確認したり、トラブルシューティングを行う際に使用する
- [-] セレクターを削除する
- [-] Studio でアクティビティを追加する

Q) What is the Highlight activity used for?
- [o] For troubleshooting and verifying selectors
- [-] For removing selectors
- [-] For adding activities in Studio

---
### 6.16
 
Q) UI要素の全属性のリストを表示するには、どうすればよいですか？
- [o] [UiExplorer] ツールを使用する
- [-] [UiAutomation] の画面ツールの選択機能を使用する
- [-] できません

Q) How can you see the full list of attributes of Ui elements?
- [o] By using the UiExplorer tool.
- [-] By using the select from screen tool in Ui Automation activities.
- [-] You cannot.

---
### 6.17
 
Q) セレクターとは何ですか？
- [-] UI要素の一意のID
- [o] ルートからターゲット要素までのUI要素の「パス」
- [-] UI要素のコンテナー

Q) What is a Selector?
- [-] The unique ID of an UI element.
- [o] The “path” to the UI element, starting from the root, all the way to target element.
- [-] A container for UI elements.

---
### 6.18
 
Q) [要素を探す (FindElement)] について、正しい説明はどれか？(該当するものをすべて選択してください)
- [o] 画面上の要素が見つからない場合に例外とする
- [o] 後で使用できるように、変数で見つかった要素を返す
- [-] 画面上に要素が見つかったかどうかを Boolean によって値 (True または False) を返す

Q) Which of the following statements are true regarding the Find Element activity?(Select all that apply.)
- [-] It return a boolean(True or False) specifying if the element was found on screen
- [o] It returns the found element in a variable for later use
- [o] It throws an exception if it doesn’t find the element on screen

---
### 6.19
 
Q) ロボットが、デスクトップで UiElement (利用できない場合) を検索するのに、どのくらいの時間がかかりますか？
- [-] ロボットは、要素が見つかるまで永久に待機します
- [o] アクティビティの TimeoutMS プロパティのミリ秒単位の値
- [-] 30秒
- [-] 10秒

Q) How long will the Robot try to find an UiElement (if it is not available) on the desktop?
- [-] The Robot will wait forever until it can find the element.
- [o] The value in milliseconds of the activity’s TimeoutMS property.
- [-] 10 seconds
- [-] 30 seconds

---
### 6.20
 
Q) セレクターを変数に格納できますか？(該当するものをすべて選択してください)
- [-] はい、UiElement型
- [o] はい、String型
- [-] はい、Int32型
- [-] いいえ

Q) Can you store a Selector in a variable?
- [-] Yes, of type UiElement
- [o] Yes, of type String
- [-] Yes, of type Int32
- [-] No

---

## Lesson-7

画像とテキストの自動化

---
### 7.1
 
Q) Scrape Relative シーケンスの最後に、Reset Clipping Region を実行することは必須ですか？
- [o] はい。クリッピングリージョンは共有リソースであるためです。
- [-] いいえ。次のアクションでは、他のクリッピングリージョンを使用できます。

Q) Is Reset Clipping Region mandatory to be executed at the end of a scrape relative sequence?
- [o] Yes, because Clipping Region is a shared resource.
- [-] No, for the next actions we can use other Clipping Regions.

---
### 7.2
 
Q) Citrixレコーダーを使用して、仮想環境で一連のアクションを自動的に記録することはできますか？
- [-] はい
- [o] いいえ

Q) By using Citrix Recorder, can you automatically record a set of actions in a virtual environment?
- [-] Yes
- [o] No

---
### 7.3
 
Q) ロボットは、Citrix環境でキー修飾子(hift、Ctrl など)を使用してクリックを実行することができますか？
- [o] はい
- [-] いいえ

Q) Can the robot perform clicks alongside key modifiers (shift, ctrl, etc) in a Citrix environment?
- [o] Yes
- [-] No

---
### 7.4
 
Q) Citrix 環境の外部で、画像／テキストのオートメーションを使用することができますか？
- [o] はい
- [-] いいえ

Q) You can use image/text automation outside of a Citrix environment. 
- [o] True
- [-] False

---
### 7.5
 
Q) Citrix環境で、アプリケーションの操作に使用できるアクティビティは？
- [o] Type Into
- [o] Click OCR Text
- [o] Click Image
- [-] Click Text

Q) What activities can be used to interact with applications in a Citrix environment?
- [o] Type into
- [o] Click OCR Text
- [o] Click Image
- [-] Click Text

---
### 7.6
 
Q) 数字のみを含む領域をOCRで読み取る場合、精度を向上させるにはどうすればよいですか？ (該当するものをすべて選択してください)

- [o] 「Numbers Only」を使用して Google OCR を使用する
- [-] Citrixウィンドウのフィールドには[Get Text]を使用する
- [-] 背景を暗い色にする

Q) How can you improve accuracy when scraping with OCR a region that contains only digits?
- [o] Use Google OCR with “Numbers Only”
- [-] Use Get Text for the field in the Citrix Window
- [-] Make sure the background is dark

---
### 7.7
 
Q) ターゲットが画面に表示されていない場合に、ClickImageアクティビティでボタンをクリックできますか？(該当するものをすべて選択してください)
- [-] はい。ただし、ボタンの画像ではなく、ボタンのテキストをクリックする必要があります
- [-] はい。ロボットは、画面に表示されていない場合でも画像をクリックすることができます
- [o] いいえ。表示されていないボタンは、セレクターを使用しないとクリックできません

Q) Is it possible to click a button with Click Image Activity if the target is not visible on the screen?
- [-] Yes, but you have to click the text from the button not the button image
- [-] Yes, the robot can click an image even if it's not visible on the screen
- [o] No, you could click a button which is not visible only using selectors

---
### 7.8
 
Q) Citrix環境で選択可能なテキストを抽出する最善の方法は、次のどれですか？ (該当するものをすべて選択してください)
- [-] Get Full Text アクティビティを使用する
- [-] Google OCR エンジンを使用する
- [-] Microsoft OCR エンジンを使用する
- [o] テキスト全体を選択し、コピーする

Q) What is the best way to scrape a selectable text in a Citrix environment?
- [-] Use “Get Full Text” activity
- [-] Use Google OCR engine
- [-] Use Microsoft OCR engine
- [o] Select the entire text and Copy

---
### 7.9
 
Q) Citrix環境で、トランザクションごとに値が変わるフィールドの値を抽出するには、どうすればよいですか？(該当するものをすべて選択してください)
- [-] 要素の位置を特定できないため、不可能
- [o] 近くの動かない要素を見つけて、ScrapeRelativeを使用する

Q) How can you scrape a field on a Citrix Environment when the value in that field changes each transaction?
- [-] It's impossible because you cannot locate the element
- [o] Find a static element nearby and use Scrape Relative

---
### 7.10
 
Q) Citrix環境でのオートメーションの作成が難しい理由を以下から選んでください。
- [o] アプリケーションの操作に、画像認識とOCRしか使用できないから。
- [-] 仮想環境用にセレクターを作成することが困難だから。
- [o] UI要素に直接アクセスできないから

Q) Creating automations in a Citrix environment is challenging because:
- [o] You don’t have direct access to UI elements.
- [o] You need to interact with the app using Image Recognition or OCR.

---
### 7.11
 
Q) Citrix 環境で実行しているアプリケーションで、特定のテキストラベルをクリックしたいが、そのフォントサイズがすぐに変わってしまう可能性がある場合に、より信頼性が高いのは、以下のどの方法ですか？
- [-] Click Image アクティビティを使用する。
- [o] Click OCR Text アクティビティを使用する。
- [-] サイズが変化する場合は、不可能です。

Q) What method would be more reliable when clicking on a specific text label in an application running in a Citrix environment, given the fact that its font size might be easily changed?
- [-] Using the Click Image activity.
- [o] Using the Click OCR Text activity.
- [-] It can’t be done if its size fluctuates.

---
### 7.12
 
Q) Citrix環境内のアプリケーションで、[Accept] という名前のボタンがあり、さらに、Accept という単語を含むラベルも別にあるとします。該当のボタンをクリックするには、Click Text をどのようにカスタマイズすればよいでしょうか？
- [-] 同じ単語の上をクリックしてしまうことを防げないため、これは不可能です。
- [o] [Occurrence] プロパティを使用します。
- [-] その要素の属性をチェックします。

Q) Consider having an application in Citrix Environment that has a button named ‘Accept’ and also a label that contains the Accept word. How can Click Text be customized in order to access the correct button?
- [-] By checking the element’s attributes.
- [o] By using the Occurrence property.
- [-] It can’t be done, having to click on a text that is duplicated can’t be controlled.

---
### 7.13
 
Q) Citrix環境では、Click Image と Click Text に100％の正確性は期待できません。より確実なアクションを実行するために、(可能な場合に)代わりに使用できる方法は、以下のどれですか？
- [-] Click Image アクティビティの [Accuracy] プロパティを 1 に設定する。
- [-] 完全セレクターを使用する。
- [o] 信頼性の高い要素にフォーカスを設定し、キーボード(上下、矢印、タブなどのキー)を使用してアプリケーション内を移動するか、またはキーボードショートカットを使用する。

Q) Click Image and Click OCR Text are not 100% reliable in Citrix environments. What method can be used instead (when applicable) to have safer actions?
- [-] Setting the Accuracy property of the Click Image activity to 1.
- [-] Using full selectors.
- [o] Setting focus on a reliable element and then navigating around the app using keyboard (up/down arrows, tab, etc) or using keyboard shortcuts.

---
### 7.14
 
Q) Citrix 環境で、サイズやスタイルが同じように見えるテキストボックスを複数持つアプリケーションがあります。入力するテキストボックスを特定するには、どうすればよいでしょうか？
- [-] テキストボックス要素の属性を利用する。
- [o] テキストボックスの近くに、ほかと区別できるもの(テキスト／画像)がない場合は、特定できません。
- [o] テキストボックスの近くにあり、ほかと区別できるテキスト／画像をクリックする。
- [-] 部分セレクターを使用する。

Q) Having an app in a Citrix environment with multiple text-boxes that look the same (size/style), how can you identify one of them to type into?
- [-] By using text-box element attributes.
- [o] You can’t identify it if it doesn’t have something unique next to it (text/image).
- [o] By clicking relative to an unique text/image next to the textbox.
- [-] By using partial selectors.

---

## Lesson-8

高度な Citrix の自動化

---
### 8.1
 
Q) ドロップダウンリストから項目を選択するために使用できるアクティビティは、次のうちどれですか？(該当するものをすべて選択してください)
- [o] Click Image
- [-] Click Text
- [o] Click OCR Text
- [-] Select Item

Q) Which of the following activities can be used to select an item in drop down list, in Citrix?(Select all that apply.)
- [o] Click Image
- [-] Click Text
- [o] Click OCR Text
- [-] Select Item

---
### 8.2
 
Q) Find Image アクティビティでは何が返されますか？
- [o] UI 要素オブジェクト
- [-] PNG 画像
- [-] Boolean 変数 (値は画像が見つかったかどうかによって異なる)

Q) What does the Find Image activity return?
- [o] An UI element object.
- [-] A PNG image.
- [-] A boolean variable, whose value depends on whether the image was found or not.

---
### 8.3
 
Q) Citrix環境で、アプリケーションが特定の状態であることを確認するには、どうすればよいですか？
- [-] WaitForReady プロパティを使用する。
- [-] UI要素の属性をチェックする。
- [o] 特定のUI要素が表示または非表示されるまで待機し、それに基づいて判別を行う。

Q) How can we make sure that an app is in a certain state in a Citrix environment?
- [-] By making use of the WaitForReady property.
- [-] By checking the UI element’s attributes.
- [o] By waiting for certain UI elements to appear or disappear and making decisions based on that.

---
### 8.4
 
Q) Citrix でアプリケーションを開くときに、ロボットは変数引数をどのように渡すことができますか(ブラウザのウェブアドレスなど)？(該当するものをすべて選択してください)
- [-] Open Application アクティビティを使用する
- [-] デスクトップ上のショートカットに引数を設定する
- [-] 実行できません
- [o] コマンドプロンプトで、アプリケーションと引数のパスを入力する

Q) How can the robot pass a variable argument when opening an application in Citrix (eg: a web address for a browser)?
- [-] With an Open Application activity
- [-] Setting the argument to the shortcut on the desktop
- [-] Cannot be done
- [o] In the command prompt, type in the path to the application and the argument

---
### 8.5
 
Q) 読み込みが遅い要素で Type Into アクティビティを使用する必要がある場合、Type Into を実行する前に、いつくかの delay を追加するのは適切ですか？
- [-] はい、要素が読み込まれるまでの時間ができるため、読み込まれてからロボットが入力できるようになります。
- [o] いいえ、読み込みの時間が遅延時間よりも長くなる場合があるため、この方法は確実ではありません。
- [o] [Use On image] が表示され、トリガー発生後のみに入力を開始します。

Q) Imagine you have to use a Type Into activity in an element that loads slowly. Will it be a good idea to add some delays before executing Type Into?
- [-] Yes, it’ll give the robot some time and when the element is loaded it can carry on typing.
- [o] No, this solution is not reliable because sometimes the loading time can take more than the delay time.
- [o] Use On image appear and start typing only after the trigger happens.

---
### 8.6
 
Q) Pick Branch アクティビティを単独で使用できますか？
- [-] はい、たとえば、If アクティビティの [Then/Else] セクション内で使用できます。
- [o] いいえ、Pick アクティビティ本体の内部にしか追加できません。

Q) Can a Pick Branch activity be used alone?
- [-] Yes, for example, inside a Then/Else section of an If activity.
- [o] No, it can only be added inside a Pick activity body.

---
### 8.7
 
Q) Citrix内から使用できる最も簡単なナビゲーション方法は何ですか？(該当するものをすべて選択してください)
- [o] キーボードコマンド／ホットキーを送信する方法
- [-] [Click relative to image] を使用する方法
- [-] [Click with fixed coordinates] を使用する方法

Q) What is the EASIEST navigation method to be used in a form within Citrix?
- [o] By sending keyboard commands/hotkeys
- [-] By using Click relative to image
- [-] By using Click with fixed coordinates

---
### 8.8
 
Q) クリッピングリージョンをリセットするには、どうすればよいですか？(該当するものをすべて選択してください)
- [-] リセットする必要はありません
- [o] Set Clipping Region アクティビティを使用する
- [-] Find Image アクティビティを使用する
- [-] Break アクティビティを使用する

Q) How do you reset a clipping region?
- [-] It doesn't need to be reset
- [o] With a Set Clipping Region activity
- [-] With a Find Image activity
- [-] With a Break activity

---
### 8.9
 
Q) Click Image アクティビティがアイコンの画像で作成され、そのアイコンが強調表示される場合、アクティビティはまだ機能しますか？
- [-] はい、ロボットが常に検索します。
- [-] はい。クリッピングリージョンでアイコンの背景を回避する場合に機能します。
- [o] いいえ、精度が高すぎる場合は機能しません。

Q) If a Click Image activity was created with an image of an icon, and meanwhile that icon becomes highlighted, will the activity still work?
- [-] Yes, the robot will always find it.
- [-] Yes, if the clipping region avoids the background of the icon.
- [o] No, if the accuracy is too high.

---
### 8.10
 
Q) 必要な画像が Find Image で実際に見つからない場合は、どうなりますか？
- [-] アクションの出力が null オブジェクトになり、フローが実行される。
- [o] 例外がスローされる。

Q) What happens if Find Image doesn’t actually find the desired image?
- [-] An exception is thrown.
- [o] The output of the action will be a null object and the flow will carry on.

---
### 8.11
 
Q) Windowsリモート接続でホットキーを送信できない場合は、どうすればよいですか？
- [-] 何もできません。
- [-] リモートデスクトップウィンドウでクリック操作を実行して、ホットキーを送信する。
- [o] Windowsリモート接続が「全画面」モードになっている場合に、実行する必要がある。

Q) What can be done when the Windows Remote Connection doesn’t allow sending hotkeys?
- [-] There’s nothing that can be done.
- [-] Send hotkeys after performing a click on the remote desktop window.
- [o] It should work if the Windows Remote Connection is in ‘full-screen’ mode.

---
### 8.12

Q) How can you start an application within a Citrix environment?(Select all that apply.)
- [-] With an Open Application activity
- [o] Define a shortcut key and then trigger the app with a Send Hotkey activity
- [o] Double clicking its icon on the desktop
- [-] With a Start Process activity

---

## Lesson-9

Excel とデータテーブル

---
### 9.1
 
Q) Excelシートからデータを読み取る必要があるがその範囲がわからない場合、[範囲を読み込む (ReadRange)] の [範囲 (Range)] プロパティには、どのように入力しますか？(該当するものをすべて選択してください)
- [-] 範囲を指定しないと操作できません
- [o] 空白の文字列を入力します
- [-] 最後のセルだけを入力します
- [-] 何か任意の範囲を入力します

Q) You need to read from an Excel sheet and you don’t know the range. What do you write in the “Range” property of the Read Range Activity?
- [-] It’s impossible, you have to specify the range
- [o] Write an empty string
- [-] Write just the end cell
- [-] Write some random range

---
### 9.2
 
Q) [範囲を読み込む (Read Range)] で、すでにデータを持っているExcelファイルにデータテーブルを書き込むために [範囲 (Range)] を “” に設定すると、どうなりますか？
- [-] エラーがスローされる
- [o] 既存のデータは上書きされ、新しいデータのみが保持される
- [-] 新しいデータが既存のデータに追加される

Q) What happens if you use the Write Range activity with the Range property set to “” to write a datatable to an excel file that already contains data?
- [-] It will throw an error.
- [-] It will append the new data to the existing data.
- [o] It will overwrite the existing data.

---
### 9.3
 
Q) データテーブルのすべての行をループするには、どのアクティビティを使用すればよいですか？
- [-] [繰り返し(後判定) (DoWhile)]
- [o] [繰り返し(各行) (ForEachRow)]
- [-] [繰り返し(コレクションの各要素) (ForEach)]
- [-] [繰り返し(前判定) (While)]

Q) In order to loop through all the rows of a data table, which activity should be used?
- [-] Do While
- [o] For Each Row
- [-] For Each
- [-] While

---
### 9.4
 
Q) [セルを読み込む (Read Cell)] で、読み取るExcelファイルを指定するには、どのようにしますか？(該当するものをすべて選択してください)
- [o] ワークブックがプロジェクトフォルダー内にある場合は、そのブックの相対パスを入力します
- [o] [ワークブックのパス (WorkbookPath)] プロパティで、そのワークブックの完全なパスを入力します
- [-] そのワークブックを手動で開く必要があります

Q) How do you specify the Excel file to read from, in a Read Cell activity? (Select all that apply.)
- [o] In the WorkbookPath property, provide a relative path, if the workbook is in the project’s folder
- [o] In the WorkbookPath property, provide the full path of the workbook,
- [-] You have to open manually the workbook

---
### 9.5
 
Q) Excelファイルのシート全体を読み取るのに使用できるアクティビティはどれですか？(該当するものをすべて選択してください)
- [-] [テーブル範囲を取得 (GetTableRange)]
- [-] [セルを読み込む (Read Cell)]
- [o] [範囲を読み込む (Read Range)]
- [-] [CSVに書き込む (WriteCSV)]

Q) What activity can be used to read an entire sheet from a excel file? 
- [-] Get Table Range
- [-] Read Cell
- [o] Read Range
- [-] Write CSV

---
### 9.6
 
Q) 存在しない .xlsx ファイルに対して [範囲に書き込む (WriteRange)] を使用しようとした場合、どうなりますか？
- [-] エラーがスローされる
- [o] 指定した名前で新しい .xlsx ファイルが作成され、そのファイルにデータが書き込まれる
- [-] データを書き込まずに実行を継続する

Q) What happens if you try to use a Write Range activity to a .xlsx file that does not exist?
- [-] It will throw an error.
- [o] It will create that file for you and write the data in it.
- [-] It will continue the execution without writing the data.

---
### 9.7
 
Q) ある条件に基づいてデータテーブルのデータをフィルターするには、どの方法が最も適切ですか？(該当するものをすべて選択してください)
- [o] [Select] メソッドを使用する
- [-] [Clone] メソッドを使用する
- [-] [値を書式化 (FormatValue)] を使用する
- [-] [データテーブルをクリア (ClearDataTable)] を使用する

Q) What is the best approach to filter data from a data table based on a condition? 
- [o] Using the 'Select' method
- [-] Using the 'Clone' method
- [-] Using Format Value activity
- [-] Using Clear Data Table activity

---
### 9.8
 
Q) [範囲を読み込む (Read Range)] で [ヘッダーの追加 (AddHeaders)] オプションにチェックマークが付いている場合は、どうなりますか？(該当するものをすべて選択してください)
- [-] 何も起こらない
- [-] 例外がスローされる
- [-] Excelシートに新しい行が追加される
- [o] 指定された範囲の最初の行が列名とみなされる

Q) What happens if the AddHeaders option is checked for Read Range Activity? 
- [-] Nothing happens
- [-] An exception is thrown
- [-] A new row is added to the excel sheet
- [o] The first row from the specified range is considered to be the column names

---
### 9.9
 
Q) 既存の .xlsx 文書にデータを追加する場合、どのアクティビティを使用しますか？
- [-] Excel [セルに書き込む (WriteCell)]
- [o] Excel [範囲を追加 (AppendRange)]
- [o] Workbook [範囲を追加 (AppendRange)]
- [-] Workbook [範囲に書き込む (WriteRange)]

Q) What activity should you use if you want to add data to an existing .xlsx document without overwrite existing data?
- [-] Excel Write Cell
- [o] Excel Append Range
- [o] Workbook Append Range
- [-] Workbook Write Range

---
### 9.10
 
Q) [データテーブルを出力 (OutputDataTable)] の用途は何ですか？
- [-] [出力 (Output)] パネルのデータテーブルを出力すること
- [o] データテーブルのすべてのデータを文字列変数として保存すること
- [-] データをデータテーブルに変換すること
- [-] 上記のいずれでもない

Q) What is the Output Data Table activity used for?
- [-] Printing the Data Table in the Output panel.
- [o] Saves all data from the Data Table to a string variable.
- [-] Converting data to a Data Table.
- [-] None of the options.

---
### 9.11
 
Q) Excelアプリケーションがインストールされていない状態で、Excel関連のアクティビティを使用できますか？(該当するものをすべて選択してください)
- [-] はい、すべての Excelファイルに関するものが使用できます
- [-] はい、ただし xls ファイルに関するもののみです
- [o] はい、ただし xlsx ファイルに関するもののみです
- [-] いいえ、MS Office パッケージが必要です

Q) Can Excel related activities be used without having the Excel Application installed? 
- [-] Yes and it works for every Excel file
- [-] Yes, but only for xls files
- [o] Yes, but only for xlsx files
- [-] No, UiPath Studio requires MS Office package

---
### 9.12

Q) You have an Excel table with two columns named "PersonName" and "Age". What happens if you use the activity Insert Column with the Column Name property set to "Age"? 
- [-] A new column with the name "Age" is added at the end of the table
- [o] An exception is thrown
- [-] A new column with the name "Age" is added at the beginning of the table
- [-] The Column "Age" is overwritten.

---
### 9.13

Q) What should you use if you want to get the value of a specific cell from a row in a datatable?
- [o] Lookup data table
- [-] Get Data Row
- [-] Output Data Table
- [-] Add Data Row

---
### 9.14

What activity can you use to create a DataTable from an input string?
- [o] Output Data Table
- [-] Generate Data Table
- [-] Build Data Table

---

## Lesson-10

PDFの自動化

---
### 10.1
 
Q) 構造が類似する一連のPDFファイルから特定の情報を抽出したいが、ワークフローがその中の1つのファイルでしか機能しない場合、何を調査する必要がありますか？
- [-] ContinueOnError プロパティ.
- [-] TimeoutMS プロパティ.
- [o] Selector プロパティ.
- [-] オプションなし

Q) If you want to extract specific information from a series of PDF files with a similar structure but the workflow only works for one file of the series, what should you investigate?
- [-] The ContinueOnError property.
- [-] The TimeoutMS property.
- [o] The Selector property.
- [-] None of the options.

---
### 10.2
 
Q) PDF請求書があり、ラベル [AMOUNT] の隣にある金額 (USD) を読み上げる必要があります。目的の値を取得するには、どのような方法を使用できますか？(該当するものをすべて選択してください)
- [o] Read PDF Text アクティビティを使用し、必要な文字列操作のメソッドを使用して、金額のみを取得する
- [o] 信頼できるセレクター(使用できる場合)で Get Text アクティビティを使用して、PDFファイルから金額のみを取得する
- [o] Acrobat Reader、もしくは、互換性のある他のPDFリーダーでファイルを開き、Anchor Base をラベルをアンカーとして使用する

Q) We have a native PDF invoice and we need to read the amount in USD next to the label AMOUNT. What methods can we apply to get the desired value? (Select all that apply.)
- [o] Use a Read PDF Text activity and then use the required String manipulation methods to retrieve only the amount
- [o] Use the Get Text activity with a reliable selector (if available) in order to only retrieve the amount from the PDF file.
- [o] Open the file in Acrobat Reader or any other compatible PDF reader and use Anchor Base with the label as an anchor

---
### 10.3
 
Q) PDFアクティビティを使用して、PDF ファイルの最初のページのみをロボットで読み上げるには、どうすればよいですか？(該当するものをすべて選択してください)
- [o] Range プロパティを “1” に設定する
- [-] Range プロパティを 1 に設定する
- [-] Range プロパティを “all” に設定する

Q) How can a robot read only the first page of a PDF file, using the PDF activities? 
- [o] Set the Range property to: “1”
- [-] Set the Range property to: 1
- [-] Set the Range property to: “all”

---
### 10.4
 
Q) PDFコンテナーに画像とテキストの両方が含まれている場合、すべてのテキストを読み取るには、どのアクティビティを使用する必要がありますか？
- [o] Read PDF with OCR
- [-] Read PDF Text
- [-] Read Image
- [-] Get Text

Q) If the PDF contains both images and native text, what activity should you use to read all the text from it?
- [o] Read PDF with OCR
- [-] Read PDF Text
- [-] Read Image
- [-] Get Text

---
### 10.5
 
Q) PDFアクティビティがアクティビティパネルに表示されていない場合は、どのように取得できますか？
- [o] パッケージの管理 機能を使用してインストールする。
- [-] 出力パネルに移動する。
- [-] ライブラリ タブで検索する。

Q) If the PDF activities are not listed in your Activities Panel, how can you get them?
- [o] By installing them using the Manage Packages feature.
- [-] By going to the Output panel.
- [-] By finding them in the Library tab.

---
### 10.6
 
Q) PDFファイルからすべてのテキストを抽出するには、どのアクティビティを使用する必要がありますか？
- [o] Read PDF Text
- [o] Read PDF with OCR
- [-] Read Image
- [-] Get Text

Q) What activity should you use to extract all the text from the PDF file?
- [o] Read PDF Text
- [o] Read PDF with OCR
- [-] Read Image
- [-] Get Text

---
### 10.7
 
Q) PDFファイルの場所を指定するには、どうすればよいですか？(該当するものをすべて選択してください)
- [-] ワークフローへのパスとして指定する
- [o] PDFへの完全パスとして指定する
- [o] 相対パスとして指定する

Q) How can you specify the location of an PDF file? (Select all that apply.)
- [-] As a path to the workflow
- [o] As a full path to the PDF
- [o] As a relative path

---
### 10.8
 
Q) PDFファイルから請求書番号を取得する最も簡単な方法は何ですか？
- [o] Adobe Acrobat Reader でPDFファイルを開き、関連する情報のみをスクレイピングする。
- [-] Read PDF Text アクティビティ使用し、文字列操作を使用して値を取得する。
- [-] Read PDF with OCR アクティビティを使用し、文字列操作を使用した値を取得する。

Q) What is the easiest way to get the invoice number from a native PDF file? 
- [o] Open the PDF file with Adobe Acrobat Reader and scrape only the relevant information.
- [-] Use the Read PDF with OCR activity and get the value by using string manipulation.
- [-] Use the Read PDF Text activity and get the value by using string manipulation.

---
### 10.9
 
Q) .pdf ドキュメントからテキストを読み上げるために使用できる方法は次のうちどれですか？((該当するものをすべて選択してください)
- [o] Read PDF Text アクティビティ
- [o] UI自動化(Adobe Acrobat Reader でPDFドキュメントを開き、Get Text)
- [o] Read PDF with OCR アクティビティ

Q) Which of the following methods can be used for reading text from a native .pdf document? ((Select all that apply.)
- [o] Read PDF Text activity
- [o] Ui Automation (open pdf document in Adobe Acrobat Reader, then Get Text)
- [o] Read PDF with OCR activity

---
### 10.10
 
Q) 同じ構造で、複数のPDFファイルから特定の情報を抽出したい場合は、どのアクティビティを使用する必要がありますか？
- [-] これに対応するアクティビティはない
- [-] Read PDF with OCR
- [-] Get Text with OCR
- [o] Get Text

Q) If you want to extract specific information from multiple native PDF files with the same structure, what activity should you use?
- [-] There is no activity for this
- [-] Read PDF with OCR
- [-] Get Text with OCR
- [o] Get Text

---
### 10.11
 
Q) Read PDF with OCR では、ドキュメントを読み取るために、画面上でPDFドキュメントを開きますか？
- [-] はい
- [o] いいえ

Q) Will the Read PDF with OCR activity open the PDF document on the screen in order to read it?
- [-] Yes
- [o] No

---
### 10.12
 
Q) PDFファイルを読み上げるために、Acrobat Reader を使用して開くPDFファイルで必要なアクティビティは、次のうちどれですか？
- [-] Read PDF Text
- [-] Read Image
- [o] Get Text
- [-] Read PDF with OCR

Q) What activity should you use to extract all the text from the PDF file?
- [-] Read PDF Text
- [-] Read Image
- [o] Get Text
- [-] Read PDF with OCR

---
### 10.13
 
Q) Read PDF with OCR アクティビティでエラーがスローされるのは、次のどの条件が指定されていない場合ですか？
- [o] 使われるOCRエンジン
- [o] FileName プロパティ.
- [-] Password プロパティ.
- [-] Text プロパティ.

Q) The Read PDF with OCR activity will throw an error if the following is not specified: 
- [o] The OCR Engine that is to be used.
- [o] The FileName property.
- [-] The Password property.
- [-] The Text property.

---
### 10.14
 
Q) Read PDF with OCR アクティビティについて、正しい説明は次のうちどれですか？(該当するものをすべて選択してください)
- [o] PDFファイルと連動する
- [o] 読み上げるページの範囲を指定できる
- [o] 異なるOCRエンジン(Microsoft、Google)を使用できる
- [-] オプションなし

Q) Which of the following statements regarding Read PDF with OCR activity are true? (Select all that apply.)
- [o] Works with native PDF files
- [o] It allows you to specify the range of pages to be read
- [o] Can use different OCR engines (Microsoft, Google
- [-] None of the options

---

## Lesson-11

メールの自動化

---
### 11.1
 
Q) 未読のメッセージだけを取得するためのアクティビティは、次のうちどれですか？(該当するものをすべて選択してください)
- [o] Get Outlook Mail Messages
- [o] Get IMAP Mail Messages
- [-] Get POP3 Mail Messages
- [-] Save Mail Message

Q) Which of the following activities will allow you to only retrieve only unread messages?  (Select all that apply.)
- [o] Get OUTLOOK Mail Message
- [o] Get IMAP Mail Messages
- [-] Get POP3 Mail Messages
- [-] Save Mail Message

---
### 11.2
 
Q) メールアカウントにユーザー名とパスワードを入力せずにメールを送信する場合に使用するアクティビティを答えてください。
- [o] Send Outlook Mail Message
- [-] Send SMTP Mail Message
- [-] Send Exchange Mail Message

Q) What activity can you use to send an email without entering the username and password of the email account?
- [o] Send Outlook Mail Message
- [-] Send SMTP Mail Message
- [-] Send Exchange Mail Message

---
### 11.3
 
Q) メールメッセージの送信に使用できるアクティビティを答えてください。
- [-] Send IMAP Mail Message.
- [o] Send SMTP Mail Message.
- [o] Send Outlook Mail Message.

---
### 11.4
 
Q) MailMessage内に画像を送信するには、どうすればよいですか？
- [o] Attachmentsプロパティで、画像への相対パスを追加する
- [-] MailMessage内に画像を添付することはできない
- [-] MailMessageオブジェクトのAttachmentsコレクションへのパスを追加できる Invoke Method を使用する
- [o] 添付ファイルへのパスを、sendアクティビティ内で直接追加する

Q) How can you send an image inside a MailMessage?
- [o] You can specify the relative path of the image in the Attachments property.
- [-] You cannot send an image attachment inside a MailMessage.
- [-] Using an Invoke Method which allows you to Add the path to the Attachments collection of a MailMessage object
- [o] You can add the path to the attachment directly in the send activity.

---
### 11.5
 
Q) Send Outlook Mail Message アクティビティは、Microsoft Outlook をインストールせずに使用できる」これは正しいですか？
- [-] 正しい
- [o] 正しくない

Q) The Send Outlook Mail Message activity will work without having Microsoft Outlook installed:
- [-] True
- [o] False

---
### 11.6
 
Q) Get Outlook Mail Messages アクティビティ内にあるプロパティは、次のうちどれですか？(該当するものをすべて選択してください)
- [-] Password
- [o] MailFolder
- [-] Server
- [-] Port

Q) Which of the following properties are found in the Get Outlook Mail Messages activity? 
- [-] Password
- [o] MailFolder
- [-] Server
- [-] Port

---
### 11.7
 
Q) Save Attachments アクティビティは、すべての添付ファイルを以下のどれに保存できますか？
- [o] 絶対パス
- [o] 相対パス
- [-] 変数内 (添付ファイルオブジェクトのコレクションとして)

Q) The Save Attachments activity can save all the attachments of an email to:
- [o] A relative path.
- [o] An absolute path.
- [-] In a variable, as a collection of attachment objects.

---
### 11.8
 
Q) MailMessage変数のリストをループ処理するために For Each アクティビティを使用している場合、TypeArgumentプロパティを何に設定するべきですか？
- [o] System.Net.Mail.MailMessage
- [-] System.Web.Mail.MailMessage

Q) If you are using the For Each activity to loop through a list of MailMessage variables, what should you set the TypeArgument property to?
- [o] System.Net.Mail.MailMessage
- [-] System.Web.Mail.MailMessage

---
### 11.9
 
Q) すべての Get Mail アクティビティ(POP3、IMAP、Outlook、Exchange)の　Output プロパティフィールドでサポートされている変数の型はどれですか？(該当するものをすべて選択してください)
- [-] ジェネリック
- [o] リスト(MailMessage)
- [-] リスト(ジェネリック)
- [-] MailMessage

Q) What is the supported variable type in the Output property field of all Get Mail activities (POP3, IMAP, Outlook, Exchange)?
- [-] Generic
- [o] List (MailMessage)
- [-] List (Generic)
- [-] MailMessage

---
### 11.10
 
Q) フィルタリング済みのMailMessage変数のみを取得したい場合に使用するアクティビティを答えてください。
- [-] Get IMAP mail messages
- [o] Get Outlook mail messages
- [-] Get Exchange Mail Messages
- [-] Get POP3 Mail Messages

Q) If you want to get only filtered MailMessage variables, what activity should you use?
- [-] Get IMAP mail messages
- [o] Get Outlook mail messages
- [-] Get Exchange Mail Messages
- [-] Get POP3 Mail Messages

---
### 11.11
 
Q) メールの日付を取得するには、MailMessageクラス内でどの Visual Basic プロパティを使用すればよいですか？(該当するものをすべて選択してください)
- [-] Attachments
- [-] 日付は取得できない
- [-] Date
- [o] Headers(“Date”)

Q) Which Visual Basic property within the MailMessage class will you use to get the Date of an email? 
- [-] Attachments
- [-] the Date cannot be retrieved
- [-] Date
- [o] Headers(“Date”)

---

## Lesson-12

デバッグと例外処理

---
### 12.1
 
Q) UI要素が表示されているかどうかをチェックするために、Citrix環境で使用できるアクティビティは何ですか？(該当するものをすべて選択してください)
- [-] Element Exists
- [o] Image Exists
- [-] Wait Element Vanish
- [-] Find Element

Q) What activity can be used in a Citrix environment to check whether a UI element is displayed or not?
- [-] Element Exists
- [o] Image Exists
- [-] Wait Element Vanish
- [-] Find Element

---
### 12.2
 
Q) UI要素が画面に表示されるまで待機する必要がある場合は、どのアクティビティを使用すべきですか？
- [o] Find Element
- [-] Element Exists
- [-] Wait Element Vanish

Q) If you want to wait until a UI Element becomes available on the screen, what activity should you use?
- [o] Find Element
- [-] Element Exists
- [-] Wait Element Vanish

---
### 12.3
 
Q) Try／catchブロックには、いくつのキャッチを格納できますか？
- [-] 1
- [o] キャッチの数に制限はありません
- [-] 2
- [-] 5

Q) How many Catches can you have in a Try/Catch block?
- [-] 1
- [o] There is no limit on the number of catches.
- [-] 2
- [-] 5
---
### 12.4
 
Q) ワークフローの実行中に、ワークフローが実行しているステップを確認するには、どうすればよいですか？(該当するものをすべて選択してください)
- [o] [デバッグ] を使用して出力パネルを確認する
- [-] [実行] を使用してプロパティパネルを確認する 
- [o] [デバッグ] と[アクティビティのハイライト] オプションを使用する

Q) When running a workflow how can you see the steps the workflow is executing?
- [o] Using Debug and inspecting the Output panel
- [-] Using Run and inspecting the Properties panel
- [o] Using Debug with Highlight Activities option

---
### 12.5
 
Q) アクティビティが失敗した場合でも、実行を続行するには、何を使用すればよいですか？(該当するものをすべて選択してください)
- [-] TimeoutMS プロパティ
- [-] DelayAfter プロパティ
- [o] Try/Catch アクティビティ
- [-] Throw アクティビティ

Q) What can you use to make sure that the execution continues even if an activity fails?
- [-] TimeoutMS property
- [-] DelayAfter property
- [o] Try/Catch activity
- [-] Throw activity

---
### 12.6
 
Q) UI要素が画面に表示されなくなるまでワークフローを停止する必要がある場合は、どのアクティビティを使用する必要がありますか？
- [-] Element Exists
- [-] Find Element
- [-] Find Relative Element
- [o] Wait Element Vanish

Q) If you need to stop the workflow until a UI Element has disappeared from the screen, what activity should you use?
- [-] Element Exists
- [-] Find Element
- [-] Find Relative Element
- [o] Wait Element Vanish

---
### 12.7
 
Q) ワークフローを読み込むときに表示される「Activity could not be loaded because of errors in the XAML」エラーの詳細について、どこで確認できますか？(該当するものをすべて選択してください)
- [-] Properties ペイン
- [-] Library
- [o] Output ペイン
- [-] Outline ペイン

Q) Where can you find more details about the following error that appears when loading a workflow: “Activity could not be loaded because of errors in the XAML”?
- [-] In Properties pane
- [-] In the Library
- [o] In Output pane
- [-] In Outline pane

---
### 12.8
 
Q) Clickアクティビティにブレークポイントを設定し、デバッグモードでワークフローを開始した場合、どうなりますか？
- [-] ワークフローは、ブレークポイントを設定したClickアクティビティに到達したときにエラーをスローします
- [-] ワークフローは、ブレークポイントを設定したClickアクティビティに到達したときに5秒間一時停止します
- [-] Breakアクティビティには、ブレークポイントしか設定できません
- [o] ワークフローは、ブレークポイントを設定したClickアクティビティに到達したときに [続行] ボタンをクリックするまで一時停止します

Q) What happens if you put a Breakpoint on a Click activity and start the workflow in Debug mode?
- [-] The workflow will throw an error when it reaches that activity.
- [-] The workflow will be paused for 5 seconds when it reaches that activity.
- [-] You can only put a Breakpoint on a Break activity.
- [o] The workflow will be paused until you click the Continue button when it reaches that activity.

---
### 12.9
 
Q) ワークフローの実行中、変数の値はどこで確認できますか？(該当するものをすべて選択してください)
- [-] Library ペイン
- [-] Variables ペイン
- [o] Locals ペイン
- [-] Outline ペイン

Q) Where can you see the variables’ values during workflow execution?
- [-] In the Library pane
- [-] In the Variables pane
- [o] In the Locals pane
- [-] In the Outline pane

---
### 12.10
 
Q) 特定の条件でロボットの動作を分析するために、ロボットを手動で1ステップづつ実行できますか？

- [o] はい、ブレークポイントを使用して、デバッグモードでワークフローを実行します。
- [o] はい、ステップインとステップオーバーを使用します。
- [-] はい、デバッグモードでワークフローを実行します。
- [-] いいえ、できません。

Can you run the robot manually, step by step, in order to analyze the robot behavior in certain conditions?
- [o] Yes, by using Breakpoints and running the workflow normally
- [o] Yes, by using Step Into and Step Over.
- [-] Yes, by using Breakpoints and running the workflow in Debug mode.
- [-] No, you cannot do it.

---
### 12.11
 
Q) Catchブロックには、何を推奨しますか？(該当するものをすべて選択してください)
- [o] 失敗したアプローチの代替方法
- [o] LogMessage アクティビティ
- [-] Input Dialog アクティビティ
- [-] なし

Q) What is recommended to have in a Catch block?
- [o] An alternative to the approach that fails
- [o] A LogMessage activity
- [-] An Input Dialog activity
- [-] Nothing

---
### 12.12
 
Q) Try／catchアクティビティの Finally ブロックは、次の場合に実行されます。
- [-] Try ブロックのアクティビティは、エラーなしで実行された場合
- [-] Catch ブロックのアクティビティが実行され、エラーが発生した場合
- [-] Try ブロックのアクティビティが実行され、エラーが発生した場合
- [o] 例外が発生したかどうかにかかわらず、毎回

Q) The Finally block of a Try/Catch activity is executed when:
- [-] The activities in the Try block are executed with no error.
- [-] The activities in the Catch block are executed and had errors.
- [-] The activities in the Try block are executed and had errors.
- [o] Every time, regardless if an exception occurred or not.

---
### 12.13
 
Q) Catchブロックで定義されている例外タイプが複数ある場合、どのブロックが実行されますか？(該当するものをすべて選択してください)
- [-] 定義されている最初のブロック
- [-] 最も一般的な例外タイプに一致しているブロック
- [-] 一致しているすべてのブロックが定義されている順に実行される
- [o] 特定の例外タイプに一致しているブロック

Q) When you have more than one exception type defined in the Catch block, which block is executed?
- [-] The first match defined
- [-] The block with most generic match
- [-] All matching blocks in the order they are defined
- [o] The block with most specific match

---
### 12.14
 
Q) 特定の条件でロボットの動作を分析するために、プロセスを遅く実行するには、どうすればよいですか？
- [-] 低速ステップを使用して、ワークフローを通常どおりに開始する。
- [-] 検証を使用する。
- [-] ブレークポイントを設定して、デバッグモードでワークフローを実行する。
- [o] 低速ステップを使用して、デバッグモードでワークフローを実行する。

Q) How can you run the process slower in order to analyze the robot’s behavior in certain conditions?

- [-] By using Slow Step and starting the workflow normally.
- [-] By using Validate.
- [-] By setting up Breakpoints and running the workflow in Debug mode.
- [o] By using Slow Step and running the workflow in Debug mode.

---
### 12.15
 
Q) 特定のアクティビティの前に実行を一時停止するには、どうすればよいですか？(該当するものをすべて選択してください)
- [o] MessageBoxアクティビティを使用する
- [o] デバッグモードでブレークポイントを使用する
- [-] Pauseアクティビティを使用する
- [-] Breakアクティビティを使用する

Q) How can execution be paused before a particular activity?
- [o] By using a MessageBox activity
- [o] By using a breakpoint in Debug mode
- [-] By using a Pause activity
- [-] By using a Break activity

---
### 12.16
 
Q) デバッグモードで作業しているときに、ローカルパネルに表示されるものは何ですか？
- [-] ワークフロー内のすべてのアクティビティ
- [-] ワークフローのログ
- [-] ローカルパネルには表示されません
- [o] 変数の現在の値

---
### 12.17
 
Q) What does the Locals panel display when you are working in Debug mode?
- [-] All the activities inside the workflow.
- [-] The logs of the workflow.
- [-] There is no Locals panel.
- [o] The current values of your variables.

---
### 12.18
 
Q) If you need to know if a UI Element is available on the screen or not, what activity should you use?
- [-] Find Element
- [o] Element Exists
- [-] Wait Element Vanish

---

## Lesson-13

プロジェクト構成

---
### 13.1
 
Q) シーケンシャルアクティビティに推奨されるレイアウトは、次のどれですか？(該当するものをすべて選択してください)
- [-] フローチャート
- [-] Decision
- [o] シーケンス
- [-] For each

Q) What is the recommended layout for sequential activities?
- [-] Flowchart
- [-] Decision
- [o] Sequence
- [-] For each

---
### 13.2
 
Q) ワークフローの実行の進捗を追跡する手段として、メッセージボックスのアクティビティを使用してユーザーに通知することは、良い方法ですか？
- [-] はい
- [o] いいえ

Q) Is notifying the user via a Message Box activity a good way to keep track of a workflow’s execution progress ?
- [-] Yes
- [o] No

---
### 13.3
 
Q) ワークフローの名前の例として良いものは、次のどれですか？(該当するものをすべて選択してください)
- [-] Workflow1.xaml
- [-] SAP_Process_Screen7.xaml
- [-] Workflow That Gets The Customer Number.xaml
- [o] GetCustomerNumber.xaml

Q) Which of the following is a good example of a workflow name?
- [-] Workflow1.xaml
- [-] SAP_Process_Screen7.xaml
- [-] Workflow That Gets The Customer Number.xaml
- [o] GetCustomerNumber.xaml

---
### 13.4
 
Q) “Workflow2.xaml”は、再利用可能なワークフローにふさわしい名前ですか？
- [-] はい
- [o] いいえ

Q) Is “Workflow2.xaml” a good name for a reusable workflow?
- [-] Yes
- [o] No

---
### 13.5
 
Q) 呼び出されたワークフローからデータを抽出するには、どうしますか？
- [o] Out引数を使用します
- [-] Invoke Workflow File アクティビティの Output プロパティを使用します
- [-] 引数を使用します
- [o] In/Out引数を使用します

Q) How can you extract data from an invoked workflow?
- [o] By using Out arguments.
- [-] By using the Output property of the Invoke Workflow File activity.
- [-] By using In arguments
- [o] By using In/Out arguments.

---
### 13.6
 
Q) ワークフロー内では、どのような型の引数を使用できますか？
- [o] In
- [o] Out
- [o] In/Out
- [-] Global

Q) What type of arguments can you use in a workflow?
- [o] In
- [o] Out
- [o] In/Out
- [-] Global

---
### 13.7
 
Q) 現在のワークフローから別のワークフローをトリガーするには、どうすればよいですか？
- [-] 別のワークフローをトリガーすることはできません
- [-] Open Application アクティビティを使用します
- [-] Invoke Method アクティビティを使用します
- [o] Invoke Workflow アクティビティを使用します

Q) How can you trigger another workflow from within your current one?
- [-] You cannot trigger another workflow.
- [-] By using the Open Application activity.
- [-] By using the Invoke Method activity.
- [o] By using the Invoke Workflow File activity.

---
### 13.8
 
Q) 複雑なプロセス自動化でビジネスロジックを定義する場合、推奨されるレイアウトは、次のどれですか？(該当するものをすべて選択してください)
- [-] Decision
- [-] シーケンス
- [-] For each
- [o] フローチャート

Q) What is the recommended layout to define business logic in a complex process automation?
- [-] Decision
- [-] Sequence
- [-] For each
- [o] Flowchart

---
### 13.9
 
Q) RPA開発者は、ワークフローにおけるランタイム例外に、どのように対処するべきですか？
- [o] Catchブロック内の自動リカバリシーケンスを使用します
- [o] 例外イベントのすべてをログに記録します
- [o] 外部ワークフローファイルを呼び出す際に、Try／Catch ブロックを使用します

Q) How should an RPA developer address runtime exceptions in the workflows?
- [o] By using automatic recovery sequences inside the Catch blocks.
- [o] By logging any exception events
- [o] By using Try/Catch blocks when invoking external workflow files

---
### 13.10
 
Q) 大規模なプロジェクトでは、どのようなことがベストプラクティスと見なされますか？
- [o] 変数とワークフローにわかりやすい名前を付けるすること
- [-] 最もよく使用されるアクティビティを、他のワークフローから呼び出すことのできる、単一のアクティビティを持つワークフロー内にカプセル化すること
- [o] ワークフローを個別にテストすること
- [o] 大きなプロセスを小さなワークフローに分割すること

Q) What is considered a best practice in large projects?
- [o] Giving descriptive names to variables and workflows
- [-] Encapsulating most used activities in single-activity workflows that can be invoked from other workflows.
- [o] Testing workflows independently
- [o] Breaking a large process in smaller workflows

---
### 13.11
 
Q) ワークフロー内で入れ子状のIfアクティビティを使用することが推奨されるのは、どのような場合ですか？
- [o] 入れ子状のIfアクティビティの使用は避けるべきです
- [-] Switchアクティビティを置き換える場合
- [-] 一連の判別を使用する必要がある場合に毎回

Q) When is it recommended to use nested If activities inside workflows?
- [o] You should avoid using nested If activities.
- [-] To replace Switch activities.
- [-] Each time you must use a series of decisions.

---
### 13.12
 
Q) ワークフロー内で、プロセスの詳細を追加するために使用できるのは、次のどれですか？(該当するものをすべて選択してください)
- [o] アクティビティの注釈を追加すること
- [o] Comment アクティビティ
- [-] Use Flowchart アクティビティ
- [-] Comment Out アクティビティ

Q) What can you use to add more details about the process in the workflow itself?
- [o] Adding activity annotations
- [o] The Comment activity
- [-] The Use Flowchart activity
- [-] The Comment Out activity

---
### 13.13

Q) How can you find all anchor elements in a web page?
- [o] Using the Find Children activity
- [-] Using the Find element activity
- [-] Using the Find Relative Element activity

---
### 13.14

Q) What kind of actions can be performed in the Variables panel?
- [o] Adding new variables
- [o] Changing variable types
- [o] Setting default values for variables