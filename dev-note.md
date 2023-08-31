### 1. run backend
```
cd server;
go run main.go
```

### 2. run web
```
cd web;

npm config set registry http://registry.npm.taobao.org/
npm install
npm run serve
```

### 3. run swagger
```
cd serve;
go install github.com/swaggo/swag/cmd/swag@latest
swag init

```
http://localhost:8888/swagger/index.html

