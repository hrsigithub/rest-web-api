# 疑問点
　

npm i --save
とは何か？

--save オプションとは？
パッケージのインストール時、package.json の dependencies に追加してくれる機能。
v5以降デフォルトで付与なので不要
------------------------------

dependenciesとdevDependenciesの違い
パッケージとして公開し、開発者以外の人がnpm installで
インストールされない。
------------------------------

npm i -D json-server


## Methods
### GET
`curl -X GET "http://localhost:3000/episodes" -v`

### POST
`curl -X POST -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の団欒"}' "http://localhost:3000/episodes" -v`

### PUT 
`curl -X PUT -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の争乱"}' "http://localhost:3000/episodes/4" -v`

### DELETE
`curl -X DELETE "http://localhost:3000/episodes/4" -v`

### HEAD
`curl -X HEAD "http://localhost:3000/episodes" -v`

### OPTIONS 
`curl -X OPTIONS "http://localhost:3000/episodes" -v`
