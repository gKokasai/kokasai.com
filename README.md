# kokasai.com

https://kokasai.com にアクセスした際に設定したページにリダイレクトさせる為のリポジトリです。

## リダイレクト先を変更する
- [docs/index.html](docs/index.html)
- [docs/404.html](docs/404.html)

の内容を以下のように書き換える。

```
---
redirect_to: "リダイレクトしたいURL"
---
```
