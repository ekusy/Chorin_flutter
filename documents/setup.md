# 環境構築の参考
[やるぜ！Flutter！　VSCodeで環境構築編](https://qiita.com/apricotcomic/items/7ff53950e10fcff212d2)
上記記事に従ってダウンロード～サンプルプロジェクト作成までを確認する
1. Flutter SDKのダウンロード
2. 環境変数PATHの設定
3. VS CodeへのFluuter拡張機能インストール
4. プロジェクト作成

# フォルダ構成
- documents → 本リポジトリに関するドキュメント類の格納
- chorin →Flutterプロジェクト
  - lib → ソースコード
  - test → 単体テストコード
  - ほかはあまり気にしなくて良い

# デバッグ開始
1. リポジトリのルートディレクトリでコンソールを開く
2. chorinへ移動する
```sh
cd chorin
```
3. 以下コマンドを実行する
```sh
flutter run
```
4. runコマンドを実行すると実行環境について聞かれるので、数字キーを入力して回答する
```cmd
[1]: Windows (windows)
[2]: Chrome (chrome)
[3]: Edge (edge)
Please choose one (or "q" to quit):
```
5. ビルドが開始され、少し待つとアプリが実行される

Flutterはホットリロードに対応しており、起動後にコードを修正すると再コンパイルせずとも反映される