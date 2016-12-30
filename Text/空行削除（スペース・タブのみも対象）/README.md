# 空行削除（スペース・タブのみも対象）

## Before
```
<p>#A1#</p>
<p>date#B1#</p>
<p>date#C1#</p>
```

## After

```
="<p>"&A1&"</p>
<p>"&TEXT(B1, "yyyy年m月d日")&"</p>
<p>"&TEXT(C1, "[$-409]mmmm d, yyyy;@")&"</p>"
```