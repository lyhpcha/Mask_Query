# Mask_Query

因應2020年新冠肺炎（武漢肺炎、COVID-19），台灣限制口罩購買實名制，只能從健保特約藥局購買，且每人一星期只能購買兩片。

----------------
口罩數量查詢系統
----------------

資料來源：健康保險資料開放服務（健保特約機構口罩剩餘數量明細清單）
URL：https://data.nhi.gov.tw/Datasets/DatasetResource.aspx?rId=A21030000I-D50001-001

這次一併試用Firebase hosting的服務，Hosting只能存放靜態網頁，但是配合前端Ajax的功能，就可以動態呈現資料。

利用Firebase hosting，免自行架設主機、資料庫等複雜的設定，可以快速建置網頁。

因為使用免費方案，所以有流量的限制。

純前端技術，所以可以直接執行，但是會有跨網堿的問題，用https://cors-anywhere.herokuapp.com/來解決此問題

