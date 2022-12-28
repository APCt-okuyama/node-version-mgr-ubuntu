# node-version-mgr-ubuntu

2022.12

## インストール 
```
https://learn.microsoft.com/ja-jp/windows/dev-environment/javascript/nodejs-on-wsl#install-nvm-nodejs-and-npm
```

## 使い方

nvm の確認と node のインストール
```
nvm --version
nvm ls
nvm install --lts # 最新のLTSをインストール
nvm install 16 # v16をインストール
nvm ls
```

利用したい node を選択
```
nvm use 16
nvm use --lts
```

## 確認
```
nvm ls
       v16.19.0
->     v18.12.1
default -> lts/* (-> v18.12.1)
iojs -> N/A (default)
unstable -> N/A (default)
node -> stable (-> v18.12.1) (default)
stable -> 18.12 (-> v18.12.1) (default)
lts/* -> lts/hydrogen (-> v18.12.1)
lts/argon -> v4.9.1 (-> N/A)
lts/boron -> v6.17.1 (-> N/A)
lts/carbon -> v8.17.0 (-> N/A)
lts/dubnium -> v10.24.1 (-> N/A)
lts/erbium -> v12.22.12 (-> N/A)
lts/fermium -> v14.21.2 (-> N/A)
lts/gallium -> v16.19.0
lts/hydrogen -> v18.12.1
```

```
node -v
```
