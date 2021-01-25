#1-2.新增及設定一般檔案連線管理員 Add and configure a Flat File connection



>1.方案總管>連線管理員>"右鍵">新增連線管理員>選FLATFILE
>2.檔案名稱>瀏覽>SampleCurrencyData.txt
>3.[一般檔案連線管理員編輯器]選 [一般]，[地區設定] 設定為 [英文 (美國)]，將 [字碼頁] 設定為 [1252]

>Solution Explorer pane > right-click on Connection Managers> select New Connection Manager
>Add SSIS Connection Manager >  FLATFILE> Add
>locate the SampleCurrencyData.txt >  Column names in the first data row 
>Flat File Connection Manager Editor > set General
>Locale to English (United States) and Code page to 1252.

>4.在 [一般檔案連線管理員編輯器] 對話方塊中，選取 [進階]。

>將 [資料行 0] 名稱屬性變更為 AverageRate。
>將 [資料行 1] 名稱屬性變更為 CurrencyID。
>將 [資料行 2] 名稱屬性變更為 CurrencyDate。
>將 [資料行 3] 名稱屬性變更為 EndOfDayRate。

Change the Column 0 name property to AverageRate.

Change the Column 1 name property to CurrencyID.

Change the Column 2 name property to CurrencyDate.

Change the Column 3 name property to EndOfDayRate.


![](/stepsphoto/MS_SSIS/Lession1/ssism001.png)
![](/stepsphoto/MS_SSIS/Lession1/ssism002.png)
![](/stepsphoto/MS_SSIS/Lession1/datac006.png)
![](/stepsphoto/MS_SSIS/Lession1/datac007.png)
![](/stepsphoto/MS_SSIS/Lession1/datac008.png)
![](/stepsphoto/MS_SSIS/Lession1/datac009.png)
![](/stepsphoto/MS_SSIS/Lession1/datac010.png)
![](/stepsphoto/MS_SSIS/Lession1/datac011.png)
![](/stepsphoto/MS_SSIS/Lession1/datac012.png)
