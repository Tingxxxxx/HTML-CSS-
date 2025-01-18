
## 文檔聲明,指定html版本，默認html5
<!DOCTYPE html>  

## `<html>` 標籤

    <html> ---> 告訴瀏覽器html文檔從這開始


## `<head>` 標籤: 網頁標題設置、引入外部資源css.js.音訊.網址...

    <head>   

        <meta charset="UTF-8">  ---> 設置頁面字符編碼為 UTF-8，這樣能正確顯示各種語言的字符

        <title>我的網站標題</title> ---> 設置頁面的標題，這會顯示在瀏覽器的標籤頁中 

        <link rel="stylesheet" href="styles.css">   ---> 引入外部 CSS 樣式表，控制頁面的樣式
        
        <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet"> ---> 引入外部字體（這裡是 Roboto 字體），這樣可以應用到頁面中的文本
        
        <audio src="background-music.mp3" controls></audio>   ---> 引入音訊文件，並提供播放控制按鈕

    </head> ---> <head>標籤到此結束

## `<body>` 標籤: 使用者在瀏覽器中看到的文本、圖像、表單、按鈕等都應該放在籤內。

    <body> 

        <h1>我的網站標題</h1>  ---> 顯示大標題 
        <p>這是網站的介紹內容。</p>   --->  顯示一段文字
        <img src="image.jpg" alt="一張圖片">    ---> 顯示圖片

    </body>

          
    </html> ---> / 代表結束，就是html文檔到這結束



結構解釋:

# 第一行是文檔聲明， 用來指定頁面所使用的html的版本， 這裡聲明的是一個html5的文件。<!DOCTYPE html>

# <html>...</html>標籤是開發人員在告訴瀏覽器，整個網頁是從這裡開始的，到結束，也就是html文檔的開始和結束標籤。<html><html>

# <head>...</head>標籤用於定義文檔的頭部，是負責對網頁進行設置標題、編碼格式以及引入css和js檔的。

# <body>...</body>標籤是編寫網頁上顯示的內容。

快捷鍵
!+enter 
ctrl+/ 