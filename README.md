# sam-hello-py

AWS SAMの動作チェック用のミニマムパッケージ。

中身は"Hello world"を出すだけです。


# デプロイ

```sh
sam build
sam deploy --guided  # --guidedは最初の1回
```

`sam deploy --guided` は

```
HelloWorldFunction may not have authorization defined, Is this okay? [y/N]: y
```

以外はデフォルトでいいです。


# スタックの削除

```sh
sam delete
```
で消えます。
