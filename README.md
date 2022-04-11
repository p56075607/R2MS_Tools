# R2MS_Tools
簡單說明

### 使用前準備
+ 安裝MATLAB2014A Runtime環境。
+ 把主程式放到根目錄下的R2MS_Tools，可依照需求改名為R2MS_Tools2、R2MS_Tools3等等。底下要有Programs與Projects資料夾。
+ 資料放在Projects資料夾中。
+ 執行主程式會有防火牆提醒，暫時不同意。

### 資料準備步驟
+ 準備ERT專案資料夾，放在Projects資料夾中，命名方式範例為:[20220125A]Taiwan-Taichung-WufengE1(WF1)  
  > [20220125A]Taiwan-Taichung-WufengE1(WF1)中，20220125為YYYYMMDD，大寫A代表監測資料，小寫a代表一次性資料。ABC順序代表當天第幾次施測。A=第一次，B=第二次...。  
  > [20220125A]Taiwan-Taichung-WufengE1(WF1)中，Taiwan為國家名，Taichung為都市名，WufengE1為地點全名，WF1為簡稱(通常三到四碼，在小括號中)。  
+ 再下一層建立「AutoRepeatInversion」資料夾。名稱固定不可改變。
+ 再下一層建立測線名稱，例如:「2022012701_E1」。可以依照需要改變名稱。
+ 再下一層建立「Urf」、「Trn」、「Inversion_ini」資料夾。
  + 其中「Urf」資料夾內要放置:以測線名稱+「_Level1.urf」的urf檔案。一定要與測站名稱資料夾同名。例如:「2022012701_E1_Level1.urf」。並且放置「AutoRepeatInversion.ini」、「AutoRepeatInversionPlot.ini」、「Urf_RandomReduce_Groups.ini」
  + 其中「Trn」資料夾內要放置:任意名稱的*.trn檔案，只能有一個。沒有地形可以不放任何檔案。
  + 其中「Inversion_ini」資料夾下一層建立「00」資料夾，裡面放任意名稱的逆推參數檔案(*.ini)，只能有一個。若有需要同時測試多種逆推參數，必須依序命名資料夾為「01」、「02」...。

### 操作介面步驟
+ 依照「更新」>「檢查進度1」>「自動分析1」>「檢查進度2」>「自動分析2」，完成後去資料夾中找成果檔案。
