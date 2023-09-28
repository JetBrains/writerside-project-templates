# Reuse content

You can reuse any element with an explicit `id` attribute.

For example, add `{id="my-para"}` after the previous paragraph
and then use the `<include>` element to reuse the paragraph elsewhere.

Here is an example:

```
You can reuse any element with an explicit `id` attribute.
{id="my-para"}

<include from="Reuse-content.md" element-id="my-para"/>
```

To reuse multiple elements, wrap them with the `<snippet>` element and include that:

```
<snippet id="two-para">
You can reuse any element with an explicit `id` attribute.

For example, add `{id="my-para"}` after the previous paragraph
and then use the `<include>` element to reuse the paragraph elsewhere.
</snippet>
```

It is recommended to keep all reusable snippets in dedicated library files.
They are similar to regular topics, but should have `is-library="true"` set at the root `<topic>` element.
Do not include library topics in any help instances directly.
There is no local preview for them.
Include snippets from library files in any of your regular topics.

If you add `lib` to the name of library files,
you can find them using <control>Go to File</control>:
press <shortcut key="GotoFile"/> and start typing `lib`.

![](find_files_lib.png)

Try including the `instance` snippet from <path>snippets-library.topic</path>
or look at an example in <path>second-instance.md</path>
and <path>Add-semantic-elements-to-Markdown.md</path>.
