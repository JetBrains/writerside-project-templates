# Play with semantic attributes

### Headings

Add `{collapsible="true"}`under the heading above to make content collapsible.
Add the `default-state` attribute and set its value to `expanded` to make
content expanded by default.

### Admonition blocks

> Note highlighting some important information
>

Add `{style="warning"}` on the next line: the admonition block will appear against the
red background.

### Code blocks

```
class Bicycle {

    // state or field
    private int gear = 5;

    // behavior or method
    public void braking() {
        System.out.println("Working of Braking");
    }
}
```

Specify the language for the code sample: add `Java` after the opening backticks - code highlighting will be applied.
