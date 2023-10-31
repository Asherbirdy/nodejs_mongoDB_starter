### 匯入這些資料 :

1. Postman Export : 在 starter 資料夾，可以在 Postman 測試

### Postman Environment 設定：

```jsx
Variable:URL
Initail value: http://localhost:1500/api/v1
Current value: http://localhost:1500/api/v1

```

### .env

新增 env 檔案來連接資料庫和設定 JWT

```jsx
# 資料庫 設定自己的帳號密碼：
MONGO_URL=mongodb+srv://<帳號>:<密碼>@nodecourse.iv1m0nn.mongodb.net/<資料庫名稱>?retryWrites=true&w=majority
JWT_SECRET=<設定自己的參數>
# 可以參考這網站的 Encryption key 256:https://acte.ltd/utils/randomkeygen
JWT_LIFETIME=30d
PORT=1500
```
# nodejs_mongoDB
