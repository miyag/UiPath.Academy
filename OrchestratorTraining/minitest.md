# Orchestrator Training

https://www.uipath.com/ja/academy/training#t2

## Level 2 - Orchestratorトレーニング 小テスト

[o] ＝ 正解

### 1) 

Q）Orchestrator の機能は次のうちどれですか？（単一選択）
- [-] ローカルマシンで Windows プロセスを実行します
- [-] 監査モードにてロボットが実行するワークフローを設計します
- [-] 監視モードにてロボットが実行するワークフローを設計します
- [o] 複数のロボットをリモート制御し、ワークフローの実行を管理します

Q）What is Orchestrator used for?
- [-] Running windows processes on the local machine
- [-] Designing workflows to be run by robots in an unsupervised mode
- [-] Designing workflows to be run by robots in a supervised mode
- [o] Remotely controlling any number of robots and performing workflow management

---
### 2) 

Q）Orchestrator を使用し、ジョブを実行する方法をすべて選択してください（複数選択）
- [o] [スケジュール (Schedules)] ページからスケジュールを作成して特定の時間にジョブを実行します
- [-] Orchestratorからジョブは実行できません
- [o] [ジョブ (Jobs)] ページからジョブを手動で実行します

Q）How can a job be initialized using Orchestrator?
- [o] At specific times, using Schedules
- [-] Jobs cannot be initialized in Orchestrator
- [o] Manually, from the Jobs page

---
### 3) 

Q）スケジュールのプロセスをロボットグループのロボットに割り当てる方法をすべて選択してください（複数選択）
- [o] プロセスを使用可能なロボットに動的に割り当てることができます
- [o] プロセスをロボットグループのすべてのロボットに割り当てることができます
- [-] スケジュールしたプロセスはロボットグループのロボットに割り当てることはできません
- [o] プロセスはユーザーの選択によりロボットグループの特定のロボットに割り当てることができます

Q）How can the processes in a schedule be assigned to the robots in a specific environment?
- [o] Processes can be selected to run on specific robots from the robot tray in Windows
- [o] Processes can run on all the robots in an environment
- [-] There is no way to assign scheduled processes to robots
- [o] Processes can run on specific robots in an environment, depending on the user's choice

---
### 4) 

Q）実行中のプロセスを終了する方法をすべて選択してください？（複数選択）
- [o] [停止 (Stop)]
- [-] [終了 (End)]
- [-] [完了 (Finish)]
- [o] [強制終了 (Kill)]

Q）Which options can be used to end the execution of a running process?
- [o] Stop
- [-] End
- [-] Finish
- [o] Kill

---
### 5) 

Q）新しいロボットグループの作成に必要な項目は次のうちどれですか？（複数選択）
- [-] [説明 (Description)]
- [-] [タイプ (Typ)]
- [-] [時間 (Time)]
- [o] [名前 (Name)]

Q）Which parameters are mandatory to be defined when creating a new environment?
- [-] Subtitle
- [-] Type
- [-] Time
- [o] Name

---
### 6) 

Q）実行中のジョブを即座に終了する方法は次のうちどれですか？（単一選択）
- [-] [完了 (Finish)]
- [o] [強制終了 (Kill)]
- [-] [停止 (Stop)]
- [-] [終了 (End)]

Q）Which command immediately terminates a running process?
- [-] Finish
- [o] Kill
- [-] Stop
- [-] End

---
### 7) 

Q）実行中のジョブを正常に停止する方法は次のうちどれですか？（単一選択）
- [-] [終了 (End)]
- [-] [完了 (Finish)]
- [o] [停止 (Stop)]
- [-] [強制終了 (Kill)]

Q）Which command instructs a robot to gracefully terminate the running process?
- [-] End
- [-] Finish
- [o] Stop
- [-] Kill

---
### 8)

Q）「ABC」ロボットグループには3台のロボットが割り当てられています。3台のロボットに1つのパッケージを割り当てる方法は次のうちどれですか？（単一選択）
- [-] 3台のロボットとパッケージを同じロボットグループに追加します
- [o] [プロセス (Processes)] ページにてパッケージをロボットグループにデプロイします。次に [ジョブ (Jobs)] ページに移動し、対象のプロセスを選択して [開始 (START)] をクリックします
- [-] パッケージを選択して各ロボットのジョブを個別に実行します
- [-] ロボットグループのすべてのロボットに同じパッケージを実行させることはできません

Q）There are 3 robots in the "ABC" environment. How can the execution of a package be assigned to all 3 of them? 
- [-] By adding all 3 robots and the package in the same environment
- [o] By navigating to the Processes page to pair the package with the intended environment, and then going to Jobs, selecting the intended/targeted process, and clicking Start
- [-] By running the job on each robot individually, using the package name
- [-] Packages cannot be run on all the robots in an environment

---
### 9) 

Q）新しいロボットグループを作成するときに設定が必要な項目は次のうちどれですか？（単一選択）
- [-] [ロボット (Robots)]
- [-] [タイプ (Type)]
- [-] [説明 (Description)]
- [o] [名前 (Name)]

Q）Which parameters need to be defined when creating a new environment?
- [-] Robots
- [-] Type
- [-] Description
- [o] Name

---
### 10) 

Q）プロセスのデプロイに必要な項目をすべて選択してください:（複数選択）
- [o] [ロボットグループ (Environment)]
- [-] [タイプ (Type)]
- [o] [パッケージのバージョン (Package Version)]
- [o] [パッケージ名 (Package Name)]

Q）Select only the specifications that are mandatory when deploying a process:
- [o] The environment
- [-] The robots on which the process is run
- [o] The package version
- [o] The package name

---
### 11)

Q）異なる 3 台のロボットに対するプロセスのデプロイ方法をすべて選択してください？（複数選択）

- [-] 自動的にプロセスを実行するロボットのロボットグループにプロセスをデプロイします
- [o] ジョブを作成し、3 台のロボットをすべて割り当てます
- [o] スケジュールを作成し、[実行ターゲット (Execution Target)] タブにて 3 台のロボットを割り当てます
- [-] 異なる 3 台のロボットに 1 つのプロセスを割り当てることはできません

Q）How can a process be allocated to three different robots?
- [-] By deploying the process in the environment of the robots, which run it automatically
- [o] By creating a job and selecting all three robots
- [o] By scheduling the process and adjusting the settings in the Execution Target tab accordingly
- [-] It is not possible to allocate a process to three different robots

---
### 12) 

Q）Orchestrator の[ダッシュボード (Dashboard)] ではコンポーネントの使用状況が表示されます。表示されるコンポーネントのチャートをすべて選択してください:（複数選択）
- [-] [ロボットグループ (Environments)]
- [o] [ロボット (Robots)]
- [o] [トランザクション (Transactions)]
- [o] [ジョブ (Jobs)]

Q）Select the charts included in the Orchestrator Dashboard:
- [-] Environments
- [o] Robots
- [o] Transactions
- [o] Job results

---
### 13) 

Q）Orchestratorとロボットを接続するために必要な手順をすべて選択してください（複数選択）
- [o] OrchestratorのURLとロボットキーを使用し、ローカルマシンのロボットと接続します
- [o] Orchestratorでロボットをプロビジョンします
- [-] ロボットが動作しているローカルマシンとOrchestratorが同じLANまたはVPN上に存在するかを確認します

Q）Which of the steps below are required in order to establish a connection between a robot and Orchestrator?
- [o] Configuring the Robot on the local machine using the Orchestrator URL and the Robot key
- [o] Provisioning the Robot in Orchestrator
- [-] Making sure that the local machine on which the robot is running and the Orchestrator are part of the same LAN or VPN

---
### 14) 

Q）ロボットキーの生成方法は次のうちどれですか？（単一選択）
- [-] ロボットキーにはライセンスが付属しています
- [o] [マシン (Machine)] ページにてマシンをプロビジョンすることでロボットキーを生成します
- [-] ロボットキーは各ロボットによって自動的に生成され、ロボットトレイに保存されます
- [-] ロボットキーは UiPath Studio によって生成されます

Q）How are Robot Keys generated?
- [-] Robot Keys come with the license
- [o] Orchestrator generates unique Robot Keys during the robot provisioning process
- [-] Robot Keys are automatically generated by each robot and can be found in the Robot Tray
- [-] Robot Keys are generated via UiPath Studio

---
### 15) 

Q）Orchestratorに接続されているロボットが利用可能かどうかをリアルタイムで確認できますか？（単一選択）
- [o] はい、 [ロボット (Robots)] ページの [ステータス (STATUS)] にて各ロボットの状態が確認できます
- [-] はい、ジョブの実行時に確認できます

Q）Is it possible to check whether a Robot that is connected to Orchestrator is available or not in real time?
- [o] Yes, this is possible through the Heartbeat mechanism; the status of each robot is updated on the Robots page
- [-] This is only possible when attempting to run a Job

---
### 16) 

Q）ロボットトレイでプロセスが利用可能になるのは次のうちどれですか？（単一選択）
- [-] ローカルマシンから発行されたすべてのプロセスはロボットトレイで利用可能です
- [-] ロボットにてジョブが作成されると利用可能です
- [-] Orchestratorでデプロイしたすべてのプロセスはロボットトレイで利用可能です
- [o] ロボットグループのロボットにパッケージがデプロイされている場合に利用可能です

Q）When does a process become available in the Robot Tray?
- [-] All the processes published from the local machine are available in the Robot Tray by default
- [-] When a job is created using the current Robot
- [-] All the processes deployed in Orchestrator are available in the Robot Tray by default
- [o] When a package is deployed in the same environment that the Robot is part of

---
### 17) 

Q）Orchestrator にパッケージをアップロードする方法は UiPath Studio にて [パブリッシュ (Publish)] を実行する方法のみですか？（単一選択）
- [o] いいえ、パッケージは Orchestrator の [パッケージ (Packages)] ページからもパプリッシュできます
- [-] はい、パッケージは UiPath Studio のみパブリッシュできます。

Q）Is using the ‘Publish’ button in Studio the only way to upload a package to Orchestrator?
- [o] No. Packages can also be published via the Packages page in Orchestrator
- [-] Yes, packages can only be published from Studio

---
### 18) 

Q）[パッケージ (Packages)] ページの機能をすべて選択してください（複数選択）
- [o] パブリッシュされたすべてのパッケージが表示されます
- [-] パッケージを任意のプロセスにリンクできます
- [o] パッケージのバージョンを削除できます
- [o] 新しいパッケージを手動で追加できます

Q）Which options and actions can be triggered on the Packages page?
- [o] View all published packages
- [-] Link a package to a process
- [o] Delete package versions
- [o] Add a new package manually

---
### 19) 

Q）Orchestrator のアクティブなパッケージバージョンが削除された場合はどうなりますか？（単一選択）
- [o] アクティブなパッケージは削除できません
- [-] 特定のパッケージバージョンとそれを使用しているすべてのプロセスがOrchestrator から削除されます
- [-] 特定のパッケージバージョンを Orchestrator から削除することで、すべてのプロセスは自動的に利用可能な最新のパッケージバージョンに更新されます

Q）What happens if an active package version in Orchestrator is deleted?
- [o] Active packages cannot be deleted
- [-] That specific package version and all the processes using it are removed from Orchestrator
- [-] That specific package version will be removed from Orchestrator; all the processes which have been using it will automatically switch to the latest package version available

---
### 20)

Q） [スケジュール (Schedule)] アクションの [指定時間が経過した後にジョブを停止 (Stop Job after)] 機能は次のうちどれですか？:（単一選択）

- [o] 指定した日時にスケジュールを停止することができます
- [-] 特定のスケジュールが期限切れになるまでの期間を表す
- [-] [指定時間が経過した後にジョブを停止 (Stop Job after)] の機能はありません

Q）The Schedule ‘stop after’ option refers to:
- [o] The amount of time until the scheduled process will be canceled/terminated
- [-] The amount of time until that specific Schedule becomes outdated
- [-] The Stop After option does not exist.


---
### 21) 

Q）ジョブがスケジュールまたは手動で開始されたかを確認する方法は次のうちどれですか？（単一選択）
- [-] ジョブの実行元は確認できません
- [-] ジョブの [詳細 (Details)] にて確認できます
- [o] [ジョブ (Jobs)] ページの [実行元 (Source)] にて確認できます

Q）Where can you check whether a job was scheduled or manually started?
- [-] This information is not available
- [-] From ‘Job Details’
- [o] Go to the Jobs page and check the Source column

---
### 22) 

Q）ロボットがプロセスを実行中に新しいジョブが起動した場合、ロボットの状態はどうなりますか？（単一選択）
- [o] ロボットがプロセスの実行を終了するまで、新しいジョブは [保留中 (Pending)] の状態となり、ロボットが利用可能になると新しいジョブが実行されます
- [-] 新しいジョブを開始するために利用可能なロボットのリストがポップアップで表示されます
- [-] 「このロボットは現在利用できません」というエラーメッセージが表示されます

Q）What happens if a new job is triggered while the robot it is assigned to is executing a different process?
- [o] The new job is left in a ‘Pending’ state until the robot finishes executing the process. The new job is executed as soon as the robot becomes available
- [-] The system generates the following error message: “This robot is not available at the moment”
- [-] A pop-up suggests a list of available Robots to start the new job

---
### 23) 

Q）UiPath Studio にて [ログフィールドを追加 (Add Log Fields)] を使用する必要があるのは次のうちどれですか？（単一選択）
- [-] 最大5つのフィールドをログメッセージに生成する必要がある場合に使用します
- [-] ログを有効にする必要がある場合に使用します
- [o] 標準のログメッセージに新しいフィールドを追加してカスタマイズする必要がある場合に使用します

Q）When should the Add Log Fields activity be used?
- [-] When logs need to be enabled
- [-] When a log message with a maximum number of five visible fields needs to be generated
- [o] When the standard log message has to be customized by adding new fields to it

---
### 24) 

Q）アセットの種類をすべて選択してください（複数選択）
- [-] [Decimal]
- [o] [String]
- [o] [Boolean]
- [o] [Integer]
- [o] [Credential]

Q）Which of the following data types can be stored as Assets?
- [-] Decimal
- [o] String
- [o] Boolean
- [o] Integer
- [o] Credential

---
### 25) 

Q）Orchestrator の [キュー(Queues)] の機能は次のうちどれですか？（単一選択）

- [o] 複数のロボットによって処理されるデータを保存します
- [-] 特定の順序で処理するロボットによってスケジュールされたジョブのリストを保存します
- [-] 複数のロボットによって実行されるプロセスのリストを保存します
- [-] 複数のロボットによって実行されるジョブのリストを保存します

Q）What is the purpose of the Queues section in Orchestrator?
- [o] To store data that is processed by multiple robots
- [-] To store lists of robots that process scheduled jobs in a certain order
- [-] To store lists of processes that are executed by multiple robots
- [-] To store lists of jobs that are executed by multiple robots

---
### 26) 

Q）トランザクションの概要は次のうちどれですか？（単一選択）
- [-] キューに追加したジョブのことです
- [-] キューに追加したプロセスのことです
- [o] キューに追加したロボットの一連の処理のことです
- [-] プロセスの実行のことです

Q）What is a transaction?
- [-] A job that was added to a Queue
- [-] A process that was added to a Queue
- [o] A set of arguments that was added to a Queue and has been processed by a robot
- [-] The execution of a process

---
### 27) 

Q）キュー内のトランザクションを、アプリケーションの例外による失敗後に再処理することはできますか？（複数選択）
- [-] いいえ、トランザクションは、失敗した場合再処理できません。
- [-] ビジネス例外のために失敗したトランザクションのみを再処理できます。
- [o] はい、キューの [自動再試行 (Auto-Retry)] プロパティが有効になっている場合、再処理できます。
- [o] はい、[トランザクション (Transactions)] ページで手動で再試行できます。

Q）Is it possible to reprocess a transaction in a Queue after its failure due to an application exception?
- [-] No, transactions cannot be processed again if they fail
- [-] Only transactions that failed due to a business exception can be reprocessed
- [o] Yes, if the Auto-Retry property of the Queue is enabled
- [o] Yes, it can be retried manually on the Transactions page

---
### 28) 

Q）アプリケーション例外により失敗したトランザクションを手動で設定できるステータスをすべて選択してください（複数選択）
- [o] [レビュー中 (In Review)]
- [-] 失敗したトランザクションのステータスを手動で設定することはできません
- [o] [リトライ (Retry Items)]
- [o] [検証済み (Mark as Verified)]

Q）What are the statuses that can be set manually for the transactions that failed due to an application exception?
- [o] In Review
- [-] It’s not possible to set the status of any failed transaction manually
- [o] Retry
- [o] Verified

---
### 29) 

Q）ロボットは、[Info] レベルの [ログメッセージ (Log Message)] アクティビティを使用するワークフローを実行しています。ロボットのログレベルが [Error] に設定されている場合、*Info*ログは Orchestrator の [ロボット (Robots)] ページ、[ジョブ (Jobs)] ページの [ログ (Logs)] ページに表示されますか？（単一選択）

- [-] はい、すべてのログメッセージはログレベルに関係なく、[ロボット (Robots)] ページの [ログを表示 (View Logs)] に表示されます
- [o] いいえ、[ロボット (Robots)] ページの [ログを表示 (View Logs)] には [Error] のログレベルから表示されます

Q）A Robot is executing a workflow that uses the “Log Message” activity with the ‘Info’ level. If the log level of the robot is set to ‘Error’, does the *Info* log appear on the Orchestrator Robots > Logs page?

- [-] Yes, all log messages are listed on the Orchestrator Robots > Logs page, regardless of their level.
- [o] No, only the log messages of type ‘Error’ and ‘Critical’ are displayed on the Orchestrator Robots > Logs page

---
### 30) 

Q）プロセスのパッケージバージョンを最新に更新する方法は次のうちどれですか？（単一選択）
- [-] 唯一の方法は目的のパッケージバージョンで新しいプロセスをデプロイすることです
- [o] [プロセス (Processes)] ページから [バージョンの表示 (View Versions)] をクリックして目的のオプションを選択します
- [-] パッケージをデプロイしたタイミングで最新のパッケージバージョンが自動的に更新されます

Q）How can a process that has more package versions be updated?
- [-] The only option is to deploy a new process with the desired package version.
- [o] By going to Processes, selecting the targeted process, clicking View Versions and selecting the desired option
- [-] Processes are updated automatically when new versions of the deployed packages are published.

---
### 31) 

Q）Orchestratorの [停止 (Stop)] 機能によって、Studio側で実行されるアクティビティは次のうちどれですか？（単一選択）
- [-] [キャンセルスコープ (Cancellation Scope)]
- [o] [停止すべきか確認 (Should Stop)]
- [-] [終了 (Is Over)]
- [-] [終了を押す (Press Terminate)]

Q）Which Studio activity is linked with the Stop command in Orchestrator ?
- [-] The Cancellation Scope activity
- [o] The Should Stop activity
- [-] The Is Over activity
- [-] The Press Terminate activity

---
### 32) 

Q）キューアイテムのステータスが[進行中 (In Progress)] のまま24時間、更新されない場合はどうなりますか？（単一選択）

- [o] ステータスは [放棄 (Abandoned)] に変更されます
- [-] ロボットが処理するまでトランザクションは [キュー (Queues)]に残ります
- [-] 自動的に[キュー (Queues)] から削除されます
- [-] 優先度が1段階上がります

Q）What happens if the status of a Transaction that is “In Progress” is not updated within 24 hours?
- [o] Its status is changed to Abandoned
- [-] The transaction remains in the *Queues* section until a Robot processes it
- [-] It is automatically removed from the *Queues* section
- [-] Its priority is increased by one level

---
### 33)

Q）[ジョブ (Jobs)] ページで使用できるフィルタをすべて選択してください（複数選択）
- [o] [インターべル (Interval)]
- [o] [状態 (State)]
- [-] [ロボット (Robot)]
- [o] [実行元 (Source)]

Q）What filter types are available for Jobs?
- [o] Interval
- [o] State
- [-] Robot
- [o] Source

---
### 34) 

Q）Attended Robots で実行したジョブの確認方法は次のうちどれですか？（単一選択）
- [o] [ジョブ (Jobs)] ページの [実行元 (Source)] フィルタから [エージェント (Agent)] を選択します
- [-] [ジョブ (Jobs)] ページの [ロボット (Robot)] フィルタから [Attended] を選択します
- [-] [ジョブ (Jobs)] ページの [ロボット (Robot)] フィルタから [Unattended] を選択します

Q）How can you see only the jobs that ran on attended robots?
- [o] By selecting “Agent” from the Source Filter in the Jobs menu.
- [-] By selecting “Attended“ from the Robot Filter in the Jobs menu.
- [-] By selecting “Unattended” jobs from the Robot Filter in the Jobs menu.

---
### 35) 

Q）失敗したトランザクションにレビュー担当者を設定できますか？（単一選択）
- [o] はい
- [-] いいえ

Q）Can we set up a reviewer for the Failed Transactions?
- [o] Yes
- [-] No

---
### 36) 

Q）レビュー用に割り当てられたアイテムを管理する最も簡単な方法は次のうちどれですか？（単一選択）
- [o] [キュー (Queues)] ページの [レビュー要求 (Review Requests)] タブを使用します
- [-] [トランザクション (Transactions)] ページに移動し、特定の [キュー (Queues)] をそれぞれ変更します
- [-] 失敗したトランザクションアイテムにレビュー担当者を割り当てることはできません

Q）What is the easiest way to manage the Items that were assigned to you for Review?
- [o] By using the Review Requests Menu
- [-] By going to the Transactions Menu and modifying each specific Queue.
- [-] You cannot assign reviewers to failed transaction items in UiPath.

---
### 37) 

Q）[レビュー要求 (Review Requests)] ページにて使用できるフィルタをすべて選択してください（複数選択）
- [o] [キュー (Queue)]
- [o] [ステータス (Status)]
- [o] [リビジョン (Revision)]
- [o] [優先 (Priority)]

Q）Which of the following Properties can be used as Filters for the Review Requests Menu?
- [o] Queue
- [o] Status
- [o] Revision
- [o] Priority

---
### 38) 

Q）Orchestrator からメインワークフローのパラメーターを挿入できますか？（単一選択）
- [o] はい
- [-] いいえ

Q）Can the parameters of the main workflow be inserted from the Orchestrator?
- [o] Yes
- [-] No

---
### 39) 

Q）Orchestratorにてパラメーターを変更する方法をすべて選択してください（複数選択）
- [o] [プロセス (Processes)] ページ -> [プロセスの表示 (View Process)] -> [パラメーター (PARAMETERS)] タブ
- [o] [ジョブ (Jobs)] ページ -> [ジョブを開始 (Start Job)] -> [パラメーター (Parameters)] タブ
- [-] [ロボット (Robots)] ページ -> [編集 (Edit)] -> [設定 (Settings)] タブ -> [パラメーター (Parameters)]
- [-] [ロボットグループ (Environments)] ページ -> [編集 (Edit)] -> [パラメーター (Parameters)]

Q）Where can the parameters be modified from in the Orchestrator?
- [o] Processes -> Parameters
- [o] Jobs -> Start Job -> Parameters
- [-] Robots -> Settings -> Parameters
- [-] Environments -> Parameters

---
### 40) 

Q）Orchestratorのパラメーターはプロセスのメインファイルにあるパラメータを上書きできますか？（単一選択）
- [-] いいえ
- [o] はい

Q）Can the parameters from the Orchestrator overwrite the ones existing in the Main file of the process?
- [-] No
- [o] Yes

---
### 41) 

Q）パラメーター変更の優先順位は次のうちどれですか？（単一選択）
- [-] パラメーターの変更に対する優先順位は特にありません
- [-] [プロセス (Processes)] -> UiPath Studio -> [ジョブ (Jobs)]
- [-] UiPath Studio -> [ジョブ (Jobs)] -> [プロセス (Processes)]
- [o] [ジョブ (Jobs)] -> [プロセス (Processes)] -> UiPath Studio
- [-] [プロセス (Processes)] -> [ジョブ (Jobs)] -> UiPath Studio

Q）What is the order of precedence for parameters modification?
- [-] The modifications have the same priority, regardless of the place in which they are executed
- [-] Processes,Studio,Jobs
- [-] Studio,Jobs,Processes
- [o] Jobs,Processes,Studio
- [-] Processes,Jobs,Studio

---
### 42) 

Q）マシンテンプレートを新規作成するときの必須項目は次のうちどれですか？（単一選択）
- [o] [テンプレート名 (Template Name)]
- [-] [ロボットグループ (Environment)]
- [-] [タイプ (Type)]
- [-] [名前 (Name)]

Q）What is the mandatory field required to complete when creating a new Machine Template?
- [o] Template Name
- [-] Environment
- [-] Type
- [-] Name

---
### 43) 

Q）マシンテンプレートの名前を変更できますか？（単一選択）
- [-] はい、ロボットに対する編集権限がある場合に変更できます
- [-] はい、編集権限に関係なく変更できます
- [-] いいえ、変更できません
- [o] はい、マシンに対する編集権限がある場合に変更できます

Q）Can a Machine Template name be changed?
- [-] Yes, only if there are Edit rights on Machines.
- [-] Yes, without any restriction.
- [-] No
- [o] Yes, only if there are Edit rights on Robots.

---
### 44) 

Q）標準ロボットをフローティングロボットに変換できますか？（単一選択）
- [-] はい、Unattended 標準ロボットのみ変換できます
- [-] はい、変換できます
- [-] いいえ、変換できません
- [o] はい、Attended 標準ロボットのみ変換できます

Q）Can a standard robot be changed into a Floating Robot?
- [-] Yes, but only for unattended standard robots
- [-] Yes
- [-] No
- [o] Yes, but only for attended standard robots

---
### 45) 

Q）マシンテンプレートが適用されるのは次のうちどれですか？（単一選択）
- [o] Active Directory ユーザーと Attended フローティングロボット
- [-] Orchestrator ユーザーと Unattended フローティングロボット
- [-] OrchestratorユーザーとAttendedフローティングロボット
- [-] Active Directory ユーザーとUnattendedフローティングロボット

Q）Machine Templates only work for:
- [o] Active Directory users and Attended Floating Robots
- [-] Orchestrator users and Unattended Floating Robots
- [-] Orchestrator users and Attended Floating Robots
- [-] Active Directory users and Unattended Floating Robots

---
### 46) 

Q）アセットから情報を取得するアクティビティをすべて選択してください（複数選択）
- [-] [テキストを取得 (Get Text)]
- [o] [資格情報を取得 (Get Credential)]
- [-] [トランザクションアイテムを取得 (Get Transaction Item)]
- [o] [アセットを取得 (Get Asset)]

Q）Which activities can be used to retrieve information from an asset?
- [-] Get Text
- [o] Get Credential
- [-] Get Transaction Item
- [o] Get Asset

---
### 47) 

Q）ロボットがアクセスできるアセット種類をすべて選択してください（複数選択）
- [-] [ロボットグループごとの値 (Environment Value)]
- [o] [ロボットごとの値 (Value Per Robot)]
- [-] [マシンごとの値 (Per Machine Value)]
- [o] [共通の値 (Single Value)]

Q）Assets can be:
- [-] Per Environment
- [o] Per Robot
- [-] Per Machine
- [o] Global
