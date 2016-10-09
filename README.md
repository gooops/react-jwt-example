React-jwt example
---

[JWT 在前后端分离中的应用与实践](http://blog.rainy.im/2015/06/10/react-jwt-pretty-good-practice/)

### Usage

```
git clone https://github.com/rainyear/react-jwt.git
npm install gulp
npm install gulp-notify gulp-util gulp-streamify gulp-uglify gulp-webserver browserify reactify vinyl-source-stream watchify
```

#### client

```js
npm install
gulp
```

#### server

```go
go get github.com/dgrijalva/jwt-go
go get github.com/gin-gonic/gin
go run server.go
```

#### jwt-go 3.0 的兼容性修改
```
http://stackoverflow.com/questions/36236109/go-and-jwt-simple-authentication
https://github.com/dgrijalva/jwt-go/issues/143
https://github.com/dgrijalva/jwt-go/blob/master/VERSION_HISTORY.md
```