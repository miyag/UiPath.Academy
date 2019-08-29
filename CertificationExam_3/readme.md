Uipath認定試験のSecondStageで出題されるPractical Exam

# 試験概要

- TransactionItemのdatatypeは「DataRow」（RefのデフォルトはQueueItem）
- Vendor検索結果の一覧で表示された結果をDatatableに退避
- 各Datarowごとに処理を実施
  - TaxIDで検索し、検索結果の「Vendor, City, Country」が上述のDatatableと一致するかチェック（不一致なら業務例外）
  - Cityが指定グループに一致するかチェック（不一致なら業務例外）
  - 上記チェックで問題なければ、Excelに記録

# 試験詳細

Exercise
In this exercise, you will create a UiPath automation that performs the steps below.
To achieve this, you will use the REFrameWork as the starting template and follow the UiPath development best practices.

Here are the steps performed by the Robot:
1. Log in to https://www.acme-test.com.
2. On the landing page, Dashboard, click or hover over the Vendors menu item and then click on Search for Vendor. 
   Click on Display All Vendors. Scrape the data from the whole table displayed. 
   The resulting datatable will be used as the input data for the process. Navigate back to the dashboard.
   Note: Navigation can be achieved in multiple ways by the robot - choose whichever you find best.
3. For each Tax ID:
- Navigate to Vendors - Search page (click or hover over the Vendors menu item and then click on Search for Vendor);
- Type the Tax ID into the Vendor Tax ID field;
- Click on Search;
- Extract the values for the Vendor, City and Country and compare them with the values from the previously extracted table from the Display All Vendors page (check for EXACT match for all fields!);
- If the values are not matching, this should be categorized as a Business Rule Exception;
- If the City does NOT belong to the group {""Paris"", ""Bucuresti"", ""Moscow"", ""Stuttgart"", ""Koln""}, this should be categorized as the second Business Rule Exception. We can only process requests from these cities. Check the City value extracted after the individual Tax ID search;
- If no Business Rule Exception, Append the resulting datatable from each page into an Excel worksheet; you shouldn't worry about the headers and format of the output file.

Constraints to follow in the development, using the REFrameWork:
1. TransactionItem datatype should be a DataRow. 
   The process should recover and retry 2 times in case of errors in navigation between the Vendor Search and Vendor Search Results pages. 
   One transaction is the action of navigating to the Vendor Search page, searching for the TaxID and scraping the values from the resulting one row table. (Similar to ACME Process 5 from the UiPath Academy). 
2. Create a separate workflow file for the Login to ACME. File input arguments: URL ; Username ; Password .
3. Create a separate workflow file for closing ACME. 
4. Add the ACME_URL and ACME_Credential to the Excel Config file.
5. Populate InitAllApplications.xaml from the Framework folder with Invoking the Login to ACME and navigation to the Work Items.
6. Populate CloseAllApplications.xaml from the Framework folder with Invoking the Close ACME.
7. Populate KillAllProcesses.xaml from the Framework folder with killing the process used.
8. Populate the Process.xaml file with the following actions: Navigation, Searching for TaxID, Scraping, Checking if the values match, Checking for the correct City, Appending to Excel.

Important Note: Don't use external file references outside of the project folder (including Orchestrator Assets). Place all the used files within the project folder, zip that folder and upload it to the UiPath Certification Platform.

Zip ALL the used workflow files AND the output Excel file. Then upload the .zip file to the UiPath Certification Platform.

Good luck!
