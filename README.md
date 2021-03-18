# express-vscode
VSCodeのRemote-Containerを使用した、Expressの開発環境サンプル。

## 開発環境
* VSCode 1.54
* Docker

## 手順
* Remote-ContainersをVSCodeにインストール。
* コマンドパレットから、`Remote-Containers: Rebuild and Reopen in Container`を選択し、Dockerイメージのビルドと、コンテナの起動を行う。
* ターミナルにて、`npm install`を実行(初回と変更時以外は不要)。
* VSCodeの実行→デバッグの開始を選択。
* ブラウザの`http://localhost:8000`で確認可能。
