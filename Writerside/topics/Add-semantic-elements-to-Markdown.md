# Add semantic elements to Markdown

## Tabs

You can use tabs to tailor content for different frameworks, languages,
operating systems, etc.

To add tabs to markdown, start typing `tabs` and press <shortcut>Tab</shortcut>.

<tabs>
<tab title="Java">

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
</tab>
<tab title="Kotlin">

```
    class Bicycle {

   // state or field
    private val gear = 5

   // behavior or method
    fun braking(): Unit {
    println("Working of Braking")
    }
}
```
</tab>
</tabs>

## Definition list

Start typing `deflist` and press <shortcut>Tab</shortcut>.

<deflist>
    <def title="Instance">
         <include from="snippets-library.topic" element-id="instance"></include>
    </def>
</deflist>
