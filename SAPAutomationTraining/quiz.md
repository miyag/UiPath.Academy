# SAP Automation Training

https://www.uipath.com/ja/academy/training#t6

## Quiz

Lesson SAP - Quiz

### 1) Which is the easiest method in order to extract a table from SAP that has the scripting enabled on both sides?
- [-] Using the Screen Scraping wizard with Google OCR Engine
- [o] Using the Data Scraping wizard
- [-] Creating a dynamic selector and extracting each element from the table
- [-] Using Get Text activity

```
Q) スクリプトが両方の側で有効なSAPから表を抽出するのに最も簡単な方法はどれでしょうか？
- [-] Google OCR EngineでScreen Scraping wizardを使用する
- [o] Data Scraping wizardを使用する
- [-] ダイナミックなセレクタを作成し、表から各要素を抽出する
- [-] Get Textアクティビティを使用する
```

---
### 2) How can the robot identify if a checkbox is checked or not?
- [-] By using the Get Text activity with the FullText method, and getting hidden information.
- [o] By using the Get Attribute activity.
- [-] By using the Image Exists activity.

```
Q)チェックボックスがオンかどうかをロボットが認識できるようにするにはどのようにすればよいでしょうか？
- [-] Image Existsアクティビティを使用する
- [-] FullTextメソッドでGet Textアクティビティを使用して隠れた情報を取得する
- [o] Get Attributeアクティビティを使用する
```

---
### 3) Can SAP client be automated if it is web hosted?
- [o] Yes, on all the browsers supported by UiPath
- [-] No, only SAP desktop client can be automated
- [-] Yes, but only on Microsoft Edge
- [-] It's a trap. SAP is not available on web

---
### 4) Some UI Elements are not selectable in SAP client, but some of them are. Which might be the problem?
- [-] It might be a problem with the screen resolution
- [o] The scripting is enabled only on the client side
- [-] There is a third party application that causes the issue

---
### 5) In a situation where a data table cannot be scraped by using Data Scraping but each cell is accessible by selectors, how can the robot extract all the cells from a column with a large number of rows?
- [-] The robot can only get the text that is visible, not all the cells.
- [o] By generating a selector for the first cell and configuringits TableRow property to iterate through all the rows
- [-] By using screen scraping.

```
Q) Data Scrapingを使用してデータテーブルがスクレイピングできない状況があるとします。ロボットが大量の行がある列から全てのセルを抽出できるようにするにはどのようにするのが良いでしょうか？
- [-] screen scrapingを使用する
- [o] 最初のセルのセレクタを生成し、プロパティのTableRow を全ての行で反復処理をするように設定します。
- [-] できません、ロボットは全てのセルではなく、表示されているテキストのみを取得します
```

---
### 6) In a SAP application, you would like the robot to click on a specific folder in a folder hierarchy. The panel containing the hierarchy doesn’t allow more granular selectors inside of it, thus no selector can be created for a specific folder. What can be used?
- [o] A Click Image activity.
- [-] You can’t solve this situation.
- [o] A Click Text activity with Native as scraping method.
- [-] A Click Text activity with FullText as scraping method.

```
Q) SAPアプリケーションで、ロボットがあるフォルダ階層内の特定のフォルダをクリックするようにしたいとします。その階層を含むパネルはそれよりも細かいセレクタを使用できないため、特定のフォルダに対してセレクタを作成することはできません。では、どうすればよいでしょうか？
- [o] Click Imageアクティビティを使用する
- [-] この状況を解決することはできない
- [o] スクレイピング方法をNativeにしてClick Textアクティビティを使用する
- [-] スクレイピング方法をFullTextにしてClick Textアクティビティを使用する
```

---
### 7) If you want to record a Click activity on an ephemeral element that appears only after focusing on a text-box relative to it, can that be done?
- [o] Yes, press F2 and in the 3 second pause put the focus on the text-box.
- [-] No, you can’t create a selector on an element that is not visible at all times.

```
Q) テキストボックスにフォーカスした後にのみ表示される一時的な要素にClickアクティビティをレコードしたいとします。これは可能でしょうか？
- [o] できます、F2キーを押して、3秒後にテキストボックスにフォーカスします。
- [-] できません、常に表示されない要素に対してセレクタは作成できません。
```

---
### 8) Consider having to click a button which cannot be accessed by using a selector. What other options can be used?
- [o] Click relative to an element that can be identified by a selector.
- [o] Use a Click Image activity set to click the image of that button.
- [o] See if clicking the button can be replaced with sending a combination of keys.

```
Q) セレクタを使用してアクセスができないボタンをクリックしなければならない場合を考えます。どのような方法が使用できるでしょうか？
- [o] ボタンのクリック動作がキーの組み合わせの送信に置き換えられるかどうか確認する
- [o] Click Imageアクティビティを使用してそのボタンのイメージをクリックします。
- [o] セレクタで識別できる要素に関連する箇所をクリックする
```