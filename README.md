# install node v16.8.0

`homebrew`を使用し、nodeのバージョン管理ツールである`nodenv`をインストールする

```bash
$ brew install nodenv
```

`nodenv`インストール確認
```bash
$ nodenv -v
```

`nodenv`でインストール可能なnode一覧を表示
```bash
$ nodenv install --list
```

`v16.8.0` インストール
```bash
$ nodenv install 16.8.0
```

nodeバージョン確認
```
$ node -v
=> v16.8.0
```

参考: https://zenn.dev/donchan922/articles/b08a66cf3cbbc5

