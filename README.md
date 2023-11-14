使い方

・適当に GitHub 上にパブリックのリポジトリを作る
・リポジトリの master ブランチ上に db.json ファイルを作る
・返してほしいデータを json 形式で db.json に書く

[db.json サンプル]
----------------------------------------------
{
  "posts": [
    {
      "id": 1,
      "title": "Post 1"
    },
    {
      "id": 2,
      "title": "Post 2"
    },
    {
      "id": 3,
      "title": "Post 3"
    }
  ],
  "comments": [
    {
      "id": 1,
      "body": "some comment",
      "postId": 1
    },
    {
      "id": 2,
      "body": "some comment",
      "postId": 1
    }
  ],
  "profile": {
    "name": "typicode"
  }
}
-------------------------------------------------------

・https://my-json-server.typicode.com/(ユーザー名)/(リポジトリ名) にアクセスする。
  --> https://my-json-server.typicode.com/miya-dev/my-json-server

https://my-json-server.typicode.com/miya-dev/my-json-server/posts/
https://my-json-server.typicode.com/miya-dev/my-json-server/comments/
https://my-json-server.typicode.com/miya-dev/my-json-server/profile/

[末尾に「/id」を付加して検索も出来る]
https://my-json-server.typicode.com/miya-dev/my-json-server/posts/1
https://my-json-server.typicode.com/miya-dev/my-json-server/comments/2

[末尾に「Query (/?〇〇=☓☓☓)」をつけて絞り込みも出来る]
https://my-json-server.typicode.com/miya-dev/my-json-server/posts/?title=Post 2





 
