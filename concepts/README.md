# 哈囉！學弟妹們～

## 這邊做一些補充, 還有[解決VS Code的debugger](#fix-vs-code-debbuger)問題

### PPT 遺漏事項  

#### 首先，ＰＰＴ網頁修好了，大家可以在[slides.csie.io/concepts](https://slides.csie.io/concepts)找到它

FIXME

## Fix VS Code debbuger
    問題發生的原因是：目前VS Code的內建debugger console沒辦法處理Java的input．  
  
  為了避免大家狀態不一致，我從頭開始．  

#### 首先，大家確認要有兩個擴充功能

    1. Debugger for Java  
    2. Java Extension Pack  

#### 其次，設定java jdk 路徑給VS Code

    step 1  
    打開 檔案 > 喜好 > 使用者設定  
    或使用 ctrl(command) + shift + P  輸入  'user setting'  
      
    step 2
    點選 右上角．．．按鈕（更多動作）> (打開setting.json)
      
    step 3  
    在右邊 user settings 大括弧內  加入最後一行
```json
    "java.home": "C:\\Program Files\\Java\\jdk-10.0.2\\",
```
    PS: mac OS  直接複製java jdk路徑就好
        windos  需要如上面，多加入一個反斜線(\)

#### 最後，更改偵錯的設定 launch.json  

確保有在一個資料夾中打開VS Code  

    點選左側欄內 偵錯圖示 > 點擊上方Debugg 旁的播放鍵
    或  更左邊一些的齒輪(設定launch.json)

這時會跳出launch.json檔案
PS: 這檔案是告訴VS Code 如何在“這個資料夾”內debug  

    檔案應該要長得像這樣．
    且更改兩處：
        1. console
        2. mainClass

![launch.json](./launch.jpg)