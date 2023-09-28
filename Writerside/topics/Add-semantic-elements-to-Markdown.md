# Add semantic elements to Markdown

Some elements are not available in Markdown.
You can add them only as XML.

## Tabs

Use tabs to switch between content for different frameworks, languages, and operating systems.

Start typing `tabs` and press <shortcut key="EditorTab"/>.

<tabs>
<tab title="Java">

```
class Bicycle {

    // state or field
    private int gear = 5;

    // behavior or method
    public void brake() {
        System.out.println("This is how brakes work");
    }
}
```
</tab>
<tab title="Kotlin">

```
    class Bicycle {

   // state or field
    private val gear = 5

   // behavior or method
    fun brake(): Unit {
    println("This is how brakes work")
    }
}
```
</tab>
</tabs>

## Definition list

Start typing `deflist` and press <shortcut key="EditorTab"/>.

<deflist>
    <def title="Instance">
         <include from="snippets-library.topic" element-id="instance"></include>
    </def>
</deflist>
