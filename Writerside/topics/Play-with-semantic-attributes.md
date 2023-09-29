# Use semantic attributes in Markdown

Semantic attributes let you adjust the behavior and appearance of various elements.

## Headings

Add `{collapsible="true"}` after the heading above to make the whole chapter collapsible.
Add the `default-state` attribute and set its value to `expanded`
to render the chapter as expanded by default.

```
## Headings {collapsible="true" default-state="expanded"}
```

## Admonition blocks

Markdown blockquotes render as tips with a grey background by default:

> Some important information
>

Add `{style="note"}` after the blockquote to render it as a note against a green background.
Or add `{style="warning"}` to render a warning against a red background.

```
> Some important information
>
{style="warning"}
```

## Code blocks

By default, code blocks render with no highlighting, as plain text.

```
<deflist>
    <def title="Instance">
        <include from="snippets-library.topic" element-id="instance"/>
    </def>
</deflist>
```

Specify a language for the code sample to render it with proper highlighting.
In this case, add `xml` after the opening backticks.

```
    ```xml
    <deflist>
        <def title="Instance">
            <include from="snippets-library.topic" element-id="instance"/>
        </def>
    </deflist>
    ```
```

> Highlighting support in the local preview depends on the language support.
If you need Java, Kotlin, or Python highlighting,
install and enable the corresponding IntelliJ plugin.
> 
{style="note"}