# React Starter Kit in TypeScript

## Nodeのインストール方法

本アプリケーションはNode を前提としています。macOSの場合だと以下の手順で導入できます。Nodeのバージョンは`.node-version`を参照してください。

    $ wget -P /tmp https://nodejs.org/download/release/v12.14.1/node-v12.14.1.pkg
    $ sudo installer -pkg /tmp/node-v12.14.1.pkg -target /
    installer: Package name is Node.js
    installer: Upgrading at base path /
    installer: The upgrade was successful.
    $ node -v
    v12.14.1

## アプリケーションの起動方法

本プロジェクトは、create-react-app により作成したアプリケーションから React の学習に必須の機能のみを厳選し、軽量化したものです。
以下の手順でアプリケーションを起動できます。

    $ wget https://github.com/DiveIntoHacking/react-starter-kit-in-typescript/archive/v1.0.tar.gz
    $ tar zxvf v1.0.tar.gz
    $ cd react-starter-kit-in-typescript-1.0
    $ yarn install
    $ yarn start
