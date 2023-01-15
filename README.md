# Laravel 9 路由酷炫視覺化

引入 garygreen 的 pretty-routes 套件來擴增視覺化所有路由清單，路由建議把它想像成是應用程式的大門管理員，每一個請求都要通過管理員，符合正確的條件才可以送到後方應用程式做處理，而管理員的放行原則，就是依照應用程式設定的路由規則來驗證，簡單來說，路由就是應用程式的門禁規則。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __Artisan__ 指令的 __migrate__ 來執行所有未完成的遷移。
```sh
$ php artisan migrate
```
- 執行安裝 Vite 和 Laravel 擴充套件引用的依賴項目。
```sh
$ npm install
```
- 執行正式環境版本化資源管道並編譯。
```sh
$ npm run build
```
- 在瀏覽器中輸入已定義的路由 URL 來訪問，例如：http://127.0.0.1:8000。
- 你可以經由 `/routes` 來瀏覽路由清單。

----

## 畫面截圖
![](https://i.imgur.com/OGzsTWR.png)
> 應用程式內所有可使用的路徑就一目了然，增加團隊合作時的效率
