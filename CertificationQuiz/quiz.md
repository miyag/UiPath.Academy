### Q) Which activity provides the easiest way to loop through all the rows in a DataTable?

- [-] While
- [-] For Each
- [-] Do While
- [o] For Each Row
- [-] Repeat Until

---

### Q) How can you dynamically change parts of a selector?

- [-] You cannot have dynamic components in a selector.
- [o] By using variables to replace the dynamic parts
- [-] By adding parameters from the Properties tab.

---

### Q) What happens if the ClickBeforeTyping property in a Type Into activity is selected?

- [o] Before typing, a click is performed at the center of the UiElement.
- [-] Before typing, a click is performed on the top left corner of the UiElement.
- [-] Before typing, a click is performed at the current mouse position.

### Q）Which activity is used to call another piece of automation?

- [-] Open Application
- [o] Invoke Workflow File
- [-] Flowchart.

---
### Q）What is the purpose of the WaitForReady property in any UiAutomation activity?

- [-] Specifies the amount of time (in milliseconds) to wait for the activity to run before an error is thrown.
- [-] Specifies to continue executing the remaining activities even if the current activity failed.
- [o] Before performing the actions, waits for the target to become ready.

---
### Q) How can you identify a column in a DataTable?

- [o] By using the column name.
- [-] By using the row index.
- [-] By using the column default value.
- [o] By using the column index.

---
### Q）Is it possible to retrieve the color of a specific Excel cell?

- [o] Yes, by using Get Cell Color
- [-] No. The color cannot be retrieved from a workbook.
- [-] Only with an OCR Engine.

---
### Q) What type of Output variable do all Get Mail activities return? (POP3, IMAP, Outlook, Exchange)

- [-] MailMessage
- [o] List <MailMessage>
- [-] List <GenericValue>

---
### Q) Which of the statuses below can a transaction have? Select all the options that apply.

- [o] New
- [-] Pending
- [o] In progress
- [o] Successful
- [o] Abandoned
- [o] Failed
- [o] Retried
- [o] Deleted

---
### Q) What types of assets can be stored in Orchestrator?

- [-] Array, Datatable, Bool, String
- [o] Bool, String, Integer, Credential
- [-] Integer, Password, GenericValue, String

---
### Q) Which is the best way to delete unreferenced variables?

- [-] Delete them one by one from the Variables panel. UiPath Studio performs the workflow validation in real time, therefore you can see which variable is being used.
- [o] You can manage your variables from the Design panel > Manage Variables > Remove Unreferenced.
- [-] The unreferenced variables do not utilise memory, therefore you do not have to delete them.

---
### Q) You need to collect employees data and send it by email as an Excel file. What type of workflow is the most suitable for the final part, which adds the file attachment, formats the email, and sends it?

- [-] Flowchart
- [-] Directed Acyclic Graph (DAG)
- [-] State Machine
- [o] Sequence

---
### Q) What is the robot able to do when the Full Text scraping method is used?

- [-] Get font information (size, colour).
- [o] Get hidden information.
- [o] Get editable text.
- [o] Get the entire visible text.

---

### Q) When should the “Add Log Fields” activity be used?

- [o] When the standard log message has to be customized by adding new fields to it
- [-] When logs need to be enabled
- [-] When a log message with a maximum number of five visible fields needs to be generated

---

### Q) The String.Format(“Input = {0} and Output = {0}”, “1”,”2”) expression returns the following:

- [-] Input = {0} and Output = {0}.
- [-] Input = 1 and Output = 2.
- [o] Input = 1 and Output = 1.
- [-] Input = {1} and Output = {2}.
- [-] An error.

---
### Q) Which of the following statements are true? Select all the options that apply.

- [-] You cannot use a recorder in a Citrix environment
- [o] The recorder is used to create a skeleton for the UI automation
- [o] The Desktop recorder generates partial selectors

---
### Q) What happens if you try to end the execution of a job by clicking the Stop/Cancel button in UiPath Orchestrator?

- [-] The execution process is killed.
- [o] The execution is not impacted if no Should Stop activity has been included in the workflow in Studio.
- [-] The job state is changed to Canceled/Stopped, even if no Should Stop activity was used.

---
### Q) Which of the following statements related to Orchestrator are true?

- [o] Robots can be assigned to multiple environments.
- [-] A robot can execute many different jobs at the same time.
- [o] A robot can execute many different jobs one after the other.

---
### Q) What robot state is displayed on the Robots page while a job is being executed?

- [o] Busy
- [-] Runnning
- [-] Pending

---
### Q) What is the relation between environments and provisioned robots?

- [o] One robot can be assigned to multiple environments.
- [-] One robot can be assigned to a single environment only.
- [o] An environment can contain multiple robots.
- [-] An environment can contain a single robot only.

---
### Q) What is the best practice to stop an ongoing job in Orchestrator?

- [-] The process can only stop on its own.
- [o] By cancelling it and using a Should Stop activity inside the workflow.
- [-] By terminating it.

---
### Q) Which is considered to be one of the best practices regarding the process finalization?

- [-] Leave the used applications open, so that a person can inspect the result
- [o] Leave the application in its initial state, so that we can execute the process again
- [-] Restart the machine, so that any potential problem can be fixed

---
### Q) How can you retrieve the value stored in a Queue Item variable?

- [-] Use the Deserialize Json activity
- [-] Use the Deserialize Xml activity
- [o] Use the SpecificContent property

---
### Q) In which workflow in the UiPath Robotic Enterprise Framework template is the retry mechanism implemented?

- [o] The SetTransactionStatus workflow
- [-] The Main workflow
- [-] The GetTransactionData workflow

---
### Q) Downloading a report from a web application takes a variable amount of time, but a pop-up window is shown when the download is finished. What should you do to check whether the file has been fully downloaded before continuing the process?

- [o] Use the On Element Appear activity and indicate the download pop-up window
- [-] Use the Element Exist activity and indicate the download pop-up window
- [-] Set the WaitForReady property to Complete

---
### Q) In the UiPath Robotic Enterprise Framework template, in the Main workflow, the State Machine includes the following states:

- [o] Init state
- [o] Get transaction data state
- [o] Process​ ​Transaction​ ​State
- [-] Set Transaction State
- [o] End​ ​Process​ ​State

---
### Q) What can the UiPath Robotic Enterprise Framework template be used as?

- [o] The starting point for every automation project
- [-] A complete library for front office robots
- [-] A consumer of a queue in Orchestrator

---
### Q) Which of the following are required to have efficient execution of automation projects?

- [o] Proper exception handling
- [o] Recovery abilities
- [o] Effective logging mechanisms

---
### Q) If a large item collection is processed using For Each, which activity enables you to efficiently exit the loop after a specific moment?

- [-] No activity can be used. Instead, you have to create a Boolean variable based on which the For Each loop is broken
- [o] The “Break” activity is the most suitable in For Each
- [-] A While loop should be used instead of For Each

---
### Q) Which of the following are considered best practices?

- [o] Start your new sequence with a short annotation meant to explain the purpose of the workflow.
- [-] Include a Should Stop activity at the end of the workflow.
- [o] Think about the exceptions that might occur during the execution of the process.

---

### Q) In the UiPath Robotic Enterprise Framework template, in the Main workflow, what is the default type of the TransactionItem variable?

- [-] String
- [o] QueueItem
- [-] Object

---
### Q) You want to build a Dispatcher process to populate an Orchestrator Queue for parallel processing on multiple robots. Which activity should you use to add a queue item for each work item?

- [o] Add Queue Item
- [-] Get Transaction Item
- [-] Add Transaction Item

---
### Q) In the UiPath Robotic Enterprise Framework template, if a System Error is encountered in the Init state of the Main workflow, which state is executed next?

- [-] Get Transaction Data
- [-] Init
- [o] End Process

---
### Q) Which statement about the UiPath Robotic Enterprise Framework template is false?

- [-] The​ ​framework​ ​is​ ​meant​ ​to​ ​be​ ​a​ ​template​ ​that​ ​helps​ ​the​ ​user​ ​design​ ​processes​.
- [o] The framework can be used only if you get the input data from the UiPath​ ​server​ ​queues.
- [-] The framework has ​a​ ​robust exception​ ​handling​ ​scheme​ ​and​ ​event​ ​logging.

---
### Q) Which Queue Item properties can be used to control the order in which the items are processed?

- [-] ItemInformation
- [o] Priority
- [o] Deadline
- [o] Postpone

---
### Q) In which workflow in the UiPath Robotic Enterprise Framework template is the TransactionNumber global variable incremented by default?

- [-] Process workflow
- [o] SetTransactionStatus workflow
- [-] GetTransactionData workflow

---

### Q) Which one of the statements below regarding the GetAppCredentials workflow included in UiPath Robotic Enterprise Framework is true?

- [-] It first requests the credential from user.
- [-] It​ ​first tries​ ​to​ ​fetch​ a ​credential ​from​ ​the Windows​ ​Credential​ ​Manager.
- [o] It​ ​first​ ​tries​ ​to​ ​fetch​ ​​a​ ​credential ​​from​ ​Orchestrator.

---
### Q) Where should credentials be stored? Select all the options that apply.

- [o] In Windows Credential Store.
- [o] In Orchestrator, as assets.
- [-] Directly inside the workflows, as variables.

---
### Q) The return value of the Get Transaction Item activity is of the following type:

- [-] Object
- [-] String
- [o] QueueItem
- [-] List<QueueItem>

---
### Q) One of the steps in your process is to authenticate on a web application. How can you check if the login succeeded or not?

- [-] Place the login activities inside a Try-Catch block. An exception is thrown in case a login problem occurs.
- [o] Use an Element Exist activity to check whether the login succeeded by searching for an element that is only displayed in that case.
- [-] Check the return value of the Login activity.

---
### Q) In the UiPath Robotic Enterprise Framework template, what should be the outcome of the Process Transaction state of the Main workflow when the application loops back to the Get Transaction Item state?

- [o] Success
- [o] Business rule exception
- [-] Application exception

---
### Q) How should a UiPath developer handle frequent changes in the project files?
- [-] By creating daily backups of the files
- [o] By using a source control solution, such as SVN, TFS, etc.
- [-] Old versions of the project files are not relevant
