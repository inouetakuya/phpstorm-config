phpstorm-config
===============

JetBrains 製の PHP IDE「PhpStorm」の設定ファイル
* http://www.jetbrains.com/phpstorm/

## Get started
```
$ cd ~/Library/Preferences/WebIde50
$ git init
$ git remote add origin git@github.com:inouetakuya/phpstorm-config.git
$ git pull origin master
```

下記のエラーとなる場合がある。というか、なる

```
error: Untracked working tree file 'foo/bar' would be overwritten by merge.
```

下記で対応する

```
$ git reset
$ git checkout .
```

