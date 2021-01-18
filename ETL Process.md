# ETL Process Example

Example is from https://docs.microsoft.com/zh-tw/sql/integration-services/ssis-how-to-create-an-etl-package?view=sql-server-ver15

Before beginn the case you should install SSIS and SQL Server 開始之前你需要先安裝SSIS 和 SQL Server

the example DB https://docs.microsoft.com/zh-tw/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms
I back up the Data Warehouse/AdventureWorksDW2019.bak In the link you can find how to back up the DB in SQL Server

將資料庫還原，使用 Data Warehouse/AdventureWorksDW2019.bak，連結中你可以找到如何還原備份的資料庫

Step1 Create a Project and Basic Package with SSIS 使用 SSIS 建立專案和基本套件

Beofre build the project look the orignal 建立專案之前先分析來源資料與目的地資料 

1.建立新的 Integration Services 專案 Create a new Integration Services project






![](/stepsphoto/MS_SSIS/Lession1/0116-01.PNG)
