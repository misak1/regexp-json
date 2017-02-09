# Excelのセル内改行文字列の正規化

## Before
```
/directory/A.html
/directory/B.html
/directory/C.html
```

## After

```
php .px_execute.php "/nothing/to/publish/?PX=publish.run&paths_region[]=/directory/A.html&paths_region[]=/directory/B.html
&paths_region[]=/directory/C.html"
```