## mysql-nodejs-client
mysql-nodejs-clientは、node.jsで動作する(マイクロサービス)ランタイムにおいて、redis を使用する際に用いる、メタライブラリです。  
本ライブラリのインストールは、各システム環境やエッジコンピューティングデバイス内におけるランタイムの特性に応じて、必要に応じて行ってください。  

## 動作環境

* OS: Linux  
* CPU: ARM/AMD/Intel  
* Node.js Runtime  

## 導入方法
本リポジトリを npm、またはyarn でインストールしてください。
```
npm install git+ssh://github.com/latonaio/mysql-nodejs-client
```

本リポジトリに格納されている package.jsonで、ライブラリの構築を行ってください。

```json
{
  "name": "mysql-nodejs-client",
  "version": "1.0.0",
  "description": "This README would normally document whatever steps are necessary to get your application up and running.",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+ssh://git@bitbucket.org/latonaio/mysql-nodejs-client.git"
  },
  "author": "",
  "license": "MIT",
  "bugs": {
    "url": "https://bitbucket.org/latonaio/mysql-nodejs-client/issues"
  },
  "homepage": "https://bitbucket.org/latonaio/mysql-nodejs-client#readme",
  "dependencies": {
    "mysql2": "^2.2.5",         // この箇所に適切なバージョンに変更してください
    "promise-mysql": "^4.1.1"   // この箇所に適切なバージョンに変更してください
  }
}


```