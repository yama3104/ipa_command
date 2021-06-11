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

## 使い方
* オプションなしでも使用できます。
```
$ ipa
100％|🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺| 473ml 94ml/s
```

* オプションはメモリの個数を指定する`-n`と、メモリが増える速度を指定する`-t`の2つです。
```
$ ipa -n 20 -t 0.5
100％|🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺🍺| 473ml 115ml/s
```
