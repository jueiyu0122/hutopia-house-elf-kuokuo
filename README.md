# NFC Photo Site 使用方式

## 這個網站可以做什麼
NFC 貼紙只需要寫入同一個網站網址。
之後你要換照片，只要更新網站裡的照片或 photos.json，不需要重新寫 NFC。

## 檔案說明
- index.html：網站主頁
- photos.json：照片清單與文字
- photos/：放照片的資料夾

## 換照片方式
1. 把你的照片放到 photos 資料夾，例如 photo-1.jpg
2. 打開 photos.json
3. 修改 image / title / caption

範例：
{
  "id": "1",
  "image": "photos/photo-1.jpg",
  "title": "給你的今日照片",
  "caption": "今天也要順利！"
}

## NFC 要寫什麼
部署上線後，把網站網址寫進 NFC，例如：
https://你的帳號.github.io/nfc-photo-site/

若你想指定某一張照片，也可以寫：
https://你的帳號.github.io/nfc-photo-site/?photo=2

## 建議部署方式
最簡單：
- GitHub Pages
- Netlify
- Vercel

如果你不想寫程式，可以用 GitHub Pages，把整個資料夾上傳後開啟 Pages。
