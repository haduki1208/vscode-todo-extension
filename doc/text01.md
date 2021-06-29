# Visual Studio Code Extension API 開発

業務で3ヶ月間、Visual Studio Code Extension APIを使った開発を行ったので、知見を書き残します。
以下、Visual Studio Codeはvscodeと略します。

# 目標

TODOアプリを作成します

-   デバッグ時に開くディレクトリを指定する
-   編集中のファイルの内容を取得する機能
-   ファイルを開いた時
-   ファイルを閉じた時
-   ソースコードに色を塗る機能
-   問題パネル(Problems)に診断情報(Diagnostic)を表示する機能
-   コマンドの作成・実行
-   クイックフィックスの作成・実行
-   パッケージ化(VSIXファイルの作成)

# やらないこと

-   LSP(Language Server Protocol)
-   拡張機能の公開
