# node-version-mgr-ubuntu

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
node -v
```
