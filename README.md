# React Starter Kit in TypeScript

## Nodeのinstall

本アプリケーションはNode v12.14.1を前提としています。macOSの場合だと以下の手順で導入できます。

    $ wget https://nodejs.org/download/release/v12.14.1/node-v12.14.1.pkg
    $ sudo installer -pkg ~/Desktop/node-v12.14.1.pkg -target /
    installer: Package name is Node.js
    installer: Upgrading at base path /
    installer: The upgrade was successful.
    $ node -v
    v12.14.1

## アプリケーションの起動方法

本プロジェクトは、create-react-app により作成したアプリケーションから React の学習に必須の機能のみを厳選し、軽量化したものです。
以下の手順で誰でもアプリケーションを動作させることができます。

    $ git clone git@github.com:DiveIntoHacking/react-starter-kit-in-typescript.git
    $ cd react-starter-kit-in-typescript
    $ yarn install
    $ yarn start
