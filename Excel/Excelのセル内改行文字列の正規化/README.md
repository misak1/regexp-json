# Excelのセル内改行文字列の正規化

## Before
```
"<tr>
<th class=""td1"">aa</th>
<td class=""td2"">
aa
</td>
<td class=""td3"">
aa
</td>
</tr>

"	"<tr>
<th class=""td1""><tr>
<th class=""td1"">aa</th>
<td class=""td2"">
aa
</td>
<td class=""td3"">
aa
</td>
</tr>
"
```

## After

```
<tr>
<th class="td1">aa</th>
<td class="td2">
aa
</td>
<td class="td3">
aa
</td>
</tr>

	<tr>
<th class="td1"><tr>
<th class="td1">aa</th>
<td class="td2">
aa
</td>
<td class="td3">
aa
</td>
</tr>

```