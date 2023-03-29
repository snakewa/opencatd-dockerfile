

# 一鍵Deploy [OpenCat](https://opencat.app/) for Team到Railway.app
### Railway.app 是一個比較方便的雲端平台，可以用來部署 opencat for team (opencatd) 應用程序到 Railway 上
⚠️ ⚠️ ⚠️ ⚠️ 免費不加信用卡现在有一個月500小時的限制了，一个月只能跑24天⚠️ ⚠️ ⚠️ ⚠️ ⚠️ 

⚠️ ⚠️ ⚠️ ⚠️ 目前Railway每一次deploy就係重設db，所以這個都是尝鮮性質，長久用還是用fly.io搞個可以掛出/opt/db的 ⚠️ ⚠️ ⚠️ ⚠️ ⚠️ 

## 方法一: 一鍵Deploy 
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/-egb9z)
1. 點一下上面的一鍵Deploy 
2. 輸入自己的repo名，公開和私人的都可以，使用自己的repo, repo更新會觸發更新，如果opencatd有更新的話可以更新一下repo
3. Deploy完成之後，點一下 "Add a Domain" 可以取得一個域名

## 方法二: 手動的具體步驟如下：
1. Clone這個repo 到你自己的github的帳號下
2. 你需要有一個 Railway 帳號，如果還沒有帳號可以到官網 https://railway.app/ 上註冊一個。
3. 在創建一個新的應用程序，點擊「Deploy New App」。
4. 選擇「Deploy From Github Repo」，並輸入你的 Github repository 鏈接，然後點擊「Next」。 
5. 你需要先將你的 Github 帳號與 Railway App 進行授權。
6. Railway 會自動檢測你的 Dockerfile，然後點擊 「Create App」。
8. 部署成功後，點一下 "Add a Domain" 可以取得一個域名，你的應用程序就可以從 Railways 的域名上訪問了。

如果您在任何時候遇到困難或問題，您可以在 Railway 上的控制台中查看詳細的日誌和錯誤信息。
