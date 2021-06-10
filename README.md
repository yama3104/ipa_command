# ipa_command

## 追加手順
### 1. ipaファイルを作成
これからの説明は`~/command`に作ることを想定しています。

### 2. 権限を変更
```
$ chmod 777 ~/command/ipa
```

### 3. パスを通す
* .bash_profileを開く
```
$ cd ~
$ vi .bash_profile
```
* .bash_profileに以下を追加
```
export PATH=$HOME/command:$PATH
```
