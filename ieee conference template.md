# IEEE-conference-template
# IEEE文件筆記

***ORCID**：開放研究者與貢獻者識別碼 用來識別研究人員

***LATEX**:一種排版系統，研究論文、IEEE 論文、數學公式、科技文件、簡報等，都常用 LaTeX 撰寫

 ***IEEEtran 類別檔**指的是 LaTeX 的 **文件類別檔案**（副檔名通常是 `.cls`），專門用來幫助作者把論文排版成 **符合 IEEE 規範** 的格式。
 
只要在LATEX前寫\documentclass[conference]{IEEEtran}就會套用IEEEtran類別檔，文章排版就會符合IEEE論文標準

 ## 縮寫

在正文中第一次使用縮寫或首字母縮略詞時，請務必先給出完整名稱，即使它們已經在摘要中定義過。像 IEEE、SI、MKS、CGS、ac、dc 和 rms 這類常見縮寫則不需要定義。除非無法避免，否則請不要在標題或章節標頭中使用縮寫。

## 單位

1. 使用 **SI（MKS）單位** 或 **CGS 單位** 作為主要單位
2. 避免混用 SI 與 CGS 單位
3. 不要將單位的全寫與縮寫混用

## 公式

1. 公式依順序編號
2. 量和變數的 **羅馬字母**請使用斜體，但 **希臘字母**不用斜體。
3. **負號請使用 **長破折號（—）**，而不要用連字號（-）。
4. 如果公式是句子的一部分，請在公式後加上 **逗號或句號**，例如：

<img width="365" height="138" alt="image" src="https://github.com/user-attachments/assets/e875c956-6f37-451a-8ca8-409597df1bcd" />

## LATEX建議

1. 不要使用 `{eqnarray}` 環境排版公式，建議改用 `{align}` 或 `{IEEEeqnarray}`
2. 使用「軟引用」（例如 `\eqref{Eq}`）而非「硬引用」（例如直接括號 `(1)`）。這樣可以在合併章節、增加公式或調整圖表與引用順序時，不必逐行修改檔案。

# 常見錯誤

1. 句尾的括號內補充語或說明，其標點應置於括號外（例如：like this）（如果整個括號內的句子是完整的句子，標點則放在括號內。）。
2. 在論文標題中，如果 **“that uses”** 可以正確替換 **“using”**，請將 “u” 大寫；如果不行，則保持小寫。
3. 縮寫 **“i.e.”** 表示 “that is（也就是）”，縮寫 **“e.g.”** 表示 “for example（例如）”。
4. 圖中再嵌入的圖稱為 **“inset”**，而不是 “insert”。建議使用 **“alternatively”** 而非 “alternately”（除非你確實指交替發生的意思）。

## Task1 0916

## 圖表

1. 圖的標題應放在圖的下方；表格的標頭（table head）**應放在表的上方。
2. 圖與表應放在**首次被引用之後**
3. 圖與表應放在欄的上方或下方，避免放在欄的中間。

## 圖表標籤

1.圖表標籤字型：8 點 Times New Roman
2.軸標籤應使用完整文字，而非符號或縮寫，以避免讀者混淆。
例：寫 “Magnetization” 或 “Magnetization, M”，而不是單寫 “M”。
3.若標籤中包含單位，應將單位放在括號內。

## 參考文件
1. 引用文獻請按出現順序連續編號，並用方括號表示，例如 [1]
2. 正文中引用只需使用編號，如 [3]
3. 即使論文已提交出版，也應標註為 “unpublished” 引用，例如  K. Elissa, “Title of paper if known,” unpublished.
4. 已被接受出版的論文，應標註為 “in press” 引用，例如R. Nicole, “Title of paper with only first word capitalized,” J. Name Stand. Abbrev., in press.
   
## Task1 0917
