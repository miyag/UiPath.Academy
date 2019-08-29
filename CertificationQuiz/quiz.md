### Q) Consider three GenericValue variables, var1 with the default value of “3 apples”, var2 with the default value of “5 mangos”, and the result, which is the output of an Assign Activity with the var1 + var2 expression. What is the value of the resulting vari

- [-] Null
- [-] “8 fruits”
- [-] 8
- [-] Error: “Input string was not in a correct format”
- [o] “3 apples5 mangos”

---
### Q) Which activity provides the easiest way to loop through all the rows in a DataTable?

- [-] While
- [-] For Each
- [-] Do While
- [o] For Each Row
- [-] Repeat Until

---

### Q) What type of argument can you define to pass data and retrieve the modified value from an invoked workflow?

- [-] In
- [o] In/Out.
- [-] Out.

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
### Q）Can you store a Selector in a variable?

- [-] No
- [-] Yes, in a UiElement variable.
- [o] Yes, in a String variable.

---
### Q）Is it possible to retrieve the color of a specific Excel cell?

- [o] Yes, by using Get Cell Color
- [-] No. The color cannot be retrieved from a workbook.
- [-] Only with an OCR Engine.

---
### Q) Is it possible to write to a text file without using the Write Text File activity?

- [-] No
- [o] Yes, using the Invoke Method activity
- [o] Yes, with the Invoke Power Shell activity

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
### Q) What status does a job have when a schedule is triggered in Orchestrator, but there are no available robots to execute it?

- [-] In progress
- [o] Pending
- [-] New

---
### Q) One of the actions below is not required when starting processes with UiPath Orchestrator.

- [-] Registering robots to Orchestrator
- [-] Publishing projects from UiPath Studio
- [-] Creating an environment containing the robot
- [o] Creating a queue in Orchestrator
- [-] Creating a process with the published package and environment
- [-] Starting a job, which is the execution of the process

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

### Q) Which of the following types of variables can be defined in UiPath Studio?

- [o] GenericValue.
- [o] DataTable
- [-] Number.

---

### Q) At the end of the execution of Workflow1, which retrieves some items from a database, is the database connection closed automatically?

- [-] Yes, the connection is closed after 30 seconds.
- [o] The connection has to be closed using a Disconnect activity.
- [-] Only the database admin can decide this aspect.


---
### Q) What is the robot able to do when the Full Text scraping method is used?

- [-] Get font information (size, colour).
- [o] Get hidden information.
- [o] Get editable text.
- [o] Get the entire visible text.

---

### Q) How can a robot start an application in Citrix?

- [o] By using a command line.
- [o] By double clicking on a Desktop icon.
- [-] By using an Open Application activity.
- [o] By defining a shortcut key for the application and then triggering the app with a Send Hotkey activity.

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
### Q) What happens when a new version of a package is published?

- [-] The processes using the package are automatically updated to the latest version
- [o] The processes have to be updated in order for the robots to run the latest version of the package
- [-] The old version of the package is overwritten

---
### Q) What is Orchestrator used for?

- [-] Running Windows processes on the local machine.
- [o] Remotely controlling any number of robots and performing workflow management.
- [-] Designing workflows to be run by robots in a supervised mode.
- [-] Designing workflows to be run by robots in an unsupervised mode.

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
### Q) In a Try Catch activity, how many times is the Finally section executed if no error occurs in the Try section?

- [o] Once
- [-] The Finally section is executed only when the Catch section is executed.
- [-] Zero

---
### Q) What happens if the result of a transaction is not set?

- [-] It is automatically set to Successful after 24 hours
- [-] It is automatically set to Failed after 24 hours
- [o] The status is “In Progress” for 24 hours, and then it switches to Abandoned

---
### Q) What is the best way of restricting the access of a person to a limited number of pages in Orchestrator?

- [-] That option does not exist. Everyone is able to see everything
- [-] By changing the rights of the Administrator to the desired state.
- [o] By creating a different account and role for that person. When creating a new role, restrictions can be applied.

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
### Q) Which is the best way to navigate to a specific page in a web browser?

- [o] Use the Navigate To activity inside an Attach Browser container
- [-] Use the Type Into activity inside an Attach Browser container
- [-] Use a Type Into activity with a full selector

---
### Q) Which of the following are considered best practices?

- [o] Removing unreferenced variables.
- [o] Deleting disabled code.
- [-] ULeaving target applications opened.

---
### Q) Which of the following are considered best practices? Select all the options that apply.

- [-] Keeping environment settings hard coded inside workflows.
- [o] Breaking the process into smaller workflows.
- [o] Reusing workflows across different projects.



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
### Q) How can you pass data between workflows?

- [o] By using arguments.
- [-] By using variables.
- [-] By using a pipe.

---
### Q) What layout should be used for UI navigation and data processing?

- [-] Flowchart
- [o] Sequence
- [-] State Machine

---
### Q) What is the best way to select a row with a certain value from a column in Excel?

- [-] Use a Read Range activity to retrieve the contents of the Excel file, and then use a For Each activity loop to iterate through the data and identify the element.
- [o] Use a Read Range Activity to retrieve the contents of the Excel file, and then use a Select method to identify the desired row.
- [-] Use the Find functionality from Excel.

---
### Q) After adding an Invoke Workflow File activity and selecting the workflow to invoke, you need to:

- [o] Click Import Arguments, and then bind the arguments to the local variables or to some default values
- [-] Click Edit Arguments, and then bind the arguments to the local variables or to some default values

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
### Q) When should the Simulate Type/Click property be used?

- [o] Whenever supported by the target application
- [-] Only when background automation is required
- [-] Only for testing purposes

---
### Q) What is the difference between a Click activity whose SimulateClick property is checked and another one with the same property unchecked?

- [-] The activity with an enabled SimulateClick flag does not click the target element, it just simulates the action.
- [o] The activity with the SimulateClick flag unchecked moves the mouse cursor over the target element, while the one with the flag set does not move the mouse cursor.
- [-] There is no difference - both can be used in same scenarios.

---
### Q) In the UiPath Robotic Enterprise Framework template, in the Get Transaction Data state of the Main workflow, what happens before the next transaction item is retrieved?

- [-] We check if the previous transaction has been completed
- [-] We check if a kill signal was sent from Orchestrator
- [o] We check if a stop signal was sent from Orchestrator

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
### Q) In the UiPath Robotic Enterprise Framework template, to enable the retry mechanism without using Queues, what should the value of MaxRetryNumber be set to?

- [-] 0
- [o] Any value greater than 0
- [-] Any value greater than 2

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
### Q) What is the best way of scraping a large, selectable text in a Citrix environment?

- [-] Use a Get Full Text activity.
- [-] Use the Microsoft OCR engine.
- [-] Use the Google OCR engine.
- [o] Select the entire text and copy it with the Copy Selected Text activity.

---
### Q) While automating an installation wizard, a pop-up window may or may not appear. What can you use to close the window without stopping the workflow?

- [o] Use a Click activity inside a Try Catch activity.
- [o] Use a Click activity with the ContinueOnError property set to True.
- [-] Use a Click activity and set its TimeoutMS property to 30.

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

---
### Q) This is a reliable selector for a dynamic web page: webctrl idx='144' tag='IMG'/

- [-] True
- [o] False

---
### Q) Where should you store the environment settings that are prone to changes?

- [o] In Orchestrator, as assets
- [o] Inside config files (.xml, .json, .xlsx, etc.)
- [-] Directly inside the workflows, as hard coded values

---
### Q) How can you improve a selector?

- [o] By replacing the dynamic parts of an attribute with wildcards.
- [-] By adding the absolute position of the elements to the selector.
- [o] By using intermediate containers for a better matching of the UI element.

---
### Q) What are the functions of the Outline panel?

- [o] It shows the structure of the workflow
- [-] It shows the execution result of the workflow
- [o] If the Activities are properly named, it can be used to search and select specific Activities used inside the workflow
