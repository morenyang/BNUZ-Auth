# BNUZ-TssAuth
Node.js - BNUZ教务辅助管理系统的模拟登陆

### 使用示例

```Javascript
var getAuth = require('./lib/getTssAuth');

// 设定学号和教务系统密码
var username = 1501030103, password = 'password';

getAuth(username, password, function (auth) {
  if (auth) {
    console.log('验证成功');
  } else{
    console.log('验证失败');
  }
}
```

### License
MIT
