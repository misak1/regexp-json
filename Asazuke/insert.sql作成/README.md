# Excelのセル内改行文字列の正規化

## Before
```
/
/en/
/sitemap/
```

## After

```
-- 元データ削除
DELETE FROM t_asazukeSS;
commit;

-- データ投入
INSERT INTO table_name VALUES('/');
INSERT INTO table_name VALUES('/en/');
INSERT INTO table_name VALUES('/sitemap/');

-- 適当な値を補完する
UPDATE t_asazukeSS SET checkCount = 1, status='HTTP/1.1 200 OK', statusCode=200;

-- 忘れずに
commit;
```
