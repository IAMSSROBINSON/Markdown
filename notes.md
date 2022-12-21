# Markdown

<br>
<br>

### Headings & Paragraphs

# H1
## H2
### H3
#### H4
##### H5
###### H6  

<br>

One full line space for a new paragraph. Two full line spaces will not produce an extra line break.

one

two

three

<br>
<br>

### Text Decoration

_This line is italic_

**This line is bold**

~~This is a strikethrough~~

<br>
<br>

### Links

<http://www.fullLinkUrlWrappedInAngleBrackets.com>

Within this sentence [this text is a clickable link.](http://www.clickingOnTextLinkLeadsToThisUrl.com) This text comes after.

Within this sentence [this text is a clickable link.](http://www.clickingOnTextLinkLeadsToThisUrl.com "This add an optional hover title tag") This text comes after.

This is a [link][1] using a key referenced at the bottom of the [page][1].

You can also link using a word as a [key][key] instead of numbers just this.

[1]: http://www.numberLinkKey.com
[key]: http://www.wordLinkKey.com

<br>
<br>

### Images
syntax: `![]()`
<br>

! => states that this will be an image

[] => alt text for screen readers & search engines

() => link to the image

<br>

Example: 
!["Amazing rganic lemons"](https://images.unsplash.com/photo-1605185189315-fc269c231e41?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80)

Example with hover tool tip:
![Amazing limesd](https://images.unsplash.com/photo-1583777731160-5abdc2fd7ab3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1974&q=80 "Great limes")

Example with key to image:
![This is linked using a key][image_1]

[image_1]: https://images.unsplash.com/photo-1597714026720-8f74c62310ba?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80 "hover"

Size images with html \<img src="" alt="altText" width="auto" height="200"> tag and add width and height properties or add a \<style> tag and style using css:

<img src="https://images.unsplash.com/photo-1598048150218-53ab5609ef31?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" width="" height="200px" class="image">

<style>
  .image{
    width: auto;
  }
</style>

<br>
<br>

### Lists

##### ul:

* Item1
* Item2
  * Item2a


##### ol:

1. The computer 
1. Will order the list items
   * Intended 
  
<br>
<br>

### Line Breaks, Horizontal Rules & Blockquotes

<hr>

Use a \<hr> tag for a horizontal rule.

Use a \<br> tag for intentional or multi-line breaks.

> This is a blockquote.

<br>
<br>

### Code block

You can write text and then indent code below to create a code block:

    #include <stdio.h>

    int main(){
        return 0;
    }

<br>

Create a code block and tell the editor what language the code is in to include syntax highlighting:

```C
  #include <stdio.h>

    int main(){
        return 0;
    }
```

This is an example of inline code using backticks: `let firstName = "name";`

<br>

Indicate differences in code using the diff keyword and plus & minus symbols:

```diff
+ let numberAdded = 100;
- let numberDeleted = 10;
```

<br>
<br>

### Tables

|Table Header 1|Table Header 2|Table Header 3|Table Header 4|
|:-------------|:-------------|:-------------|:-------------|
|R1|C2|C3|R1C4
|R2|C2 ||C4
|R3|R3C2|

<br>
<br>

### Checkboxes

* [x] Item 1
* [ ] Item 2
