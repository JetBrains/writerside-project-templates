# Convert Markdown to XML

To create a table, press <shortcut key="Generate"/>, select
<control>Table</control> and choose the number of columns and rows. 

| Item | Description | Example |
|------|-------------|---------|
|      |             |         |
|      |             |         |


If you want to make the table more complex, split or merge cells, you can convert it to XML.
Place the caret anywhere in the table, press <shortcut key="ShowIntentionActions"/>,
and select <control>Convert Markdown table to XML format</ui-path>.

```xml
<table>
<tr><td>Item</td><td>Description</td><td>Example</td></tr>
<tr><td> </td><td> </td><td> </td></tr>
<tr><td> </td><td> </td><td> </td></tr>
</table>
```