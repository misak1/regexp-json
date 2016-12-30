# 全テーブルレコード数取得

## Before
```
tbl_user
tbl_passwd
tbl_address
tbl_mean
tbl_special
```

## After

```
SELECT count(*) FROM tbl_user;
SELECT count(*) FROM tbl_passwd;
SELECT count(*) FROM tbl_address;
SELECT count(*) FROM tbl_mean;
SELECT count(*) FROM tbl_special;
```