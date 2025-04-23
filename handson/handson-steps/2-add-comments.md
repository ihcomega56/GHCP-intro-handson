## この章でやること

Visual Studio Code上で、ソースコードコメントを付与してみましょう！

## 手順

### コード補完とインラインチャットで `PostController.java` を編集

1. GitHub Codespaces（推奨）またはローカルのVisual Studio Codeで本リポジトリを開きます。
1. エディタで `src/main/java/com/example/handson/controller/PostController.java` を開きます。 :bulb: Win: Ctrl+p, Mac: Cmd+p でファイル名検索
1. クラス定義のすぐ上の行（12行目あたり）で `/**` と入力し、GitHub Copilotのコード補完によりソースコードコメントが入力されることを確認します。
1. GitHub Copilotとのインラインチャットで明確に指示を出し、クラスやメソッドにソースコードコメントを付与します。 :bulb: Win: Ctrl+i, Mac: Cmd+i でインラインチャット
    - JavaDocコメントを日本語で追加してください。
    - `/doc` 日本語で追加してください。 :bulb: `/` でよく使う操作を簡単に依頼できるコマンドが入力できます。

### Copilot Chat と Edits で `Post.java` を編集

1. エディタで `src/main/java/com/example/handson/model/Post.java` を開きます。
1. Copilot Chatのウィンドウでソースコードコメントについて相談しながら付与します。該当Javaファイルがコンテキストに含まれていることを確認してください。ファイルを開くか、チャットウィンドウへのドラッグアンドドロップで設定できます。
    - 初めてソースコードを見ても分かりやすいよう、このクラスにコメントを付与したいです。どのような内容が良いですか？
    - このクラスにJavaDocコメントを日本語で付与してください。
1. Copilot Chatの回答をファイルに反映させます。