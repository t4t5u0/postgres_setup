# postgres_setup

```
git clone git@github.com:t4t5u0/postgres_setup.git
cd postgres_setup
docker compose up -d
```

VSCode 拡張、SQLTools を用いた DB 接続

- [SQLTools - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
- [SQLTools PostgreSQL/Redshift Driver - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg)

をインストールする。

1. VSCode のサイドバーの SQLTools をクリック
1. SQL サーバーを起動する
1. Add New Connection をクリックし、設定を作る。もしくは、pgTest に接続する
1. SQL ファイルを開き、実行する(Run Acctive Connection)
