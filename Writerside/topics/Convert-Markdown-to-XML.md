# Convert Markdown to XML

Create a table: press <shortcut key="Generate"/>, select
<ui-path>Table</ui-path> and choose the number of columns and rows. 

| Item | Description | Example |
|------|-------------|---------|
|      |             |         |
|      |             |         |


If you want to make the table more complex and split or merge cells,
you can convert it into XML.
Place the caret anywhere in the table, press <shortcut key="ShowIntentionActions"/> and
choose <ui-path>Convert Markdown table to XML format</ui-path>:



```xml
<table>
<tr><td>Item</td><td>Description</td><td>Example</td></tr>
<tr><td> </td><td> </td><td> </td></tr>
<tr><td> </td><td> </td><td> </td></tr>
</table>
```