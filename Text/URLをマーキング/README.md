# URLをマーキング

## Before
```
http://sample.co.jp
http://www.sample.co.jp
https://sample.co.jp/shop/
http://www.google.co.jp/search?hl=ja&q=%U&lr=a
http://192.168.0.1
http://192.168.0.1/
http://192.168.0.1:2017
http://192.168.0.1:2017/

-- NG
https//sample.co.jp/shop/
ttp://sample.co.jp/shop/
ftp://sample.co.jp/shop/
afp://sample.co.jp/shop/
```

## After

```
[URL] http://sample.co.jp
[URL] http://www.sample.co.jp
[URL] https://sample.co.jp/shop/
[URL] http://www.google.co.jp/search?hl=ja&q=%U&lr=a
[URL] http://192.168.0.1
[URL] http://192.168.0.1/
[URL] http://192.168.0.1:2017
[URL] http://192.168.0.1:2017/

-- NG
https//sample.co.jp/shop/
ttp://sample.co.jp/shop/
ftp://sample.co.jp/shop/
afp://sample.co.jp/shop/
```