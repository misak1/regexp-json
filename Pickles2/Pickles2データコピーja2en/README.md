# Excelのセル内改行文字列の正規化

## Before
```
/investor/message/
/investor/message/coo.html
```

## After

```
#!/bin/sh
#Openをクリックして1〜3を順に行って下さい。
mkdir ./investor/message
mkdir ./investor/message

cp ./jp/investor/message/index.html ./investor/message/index.html
cp ./jp/investor/message/coo.html ./investor/message/coo.html

cp ./jp/investor/messageindex_files ./investor/messageindex_files
cp ./jp/investor/message/coo_files ./investor/message/coo_files
```