# What is markdown?

Markdown is a lightweight markup language. Unlike other markup languages like HTML or XML (see "What is markup?" for more), Markdown was designed for **readability**.

## Designed for easy authoring

For example, compare the syntax for these common formatting tasks:

**Desired Output**

!!! Note ""

    **Bold**
    
    *Italics*

    Unordered list:

    * Internet access
    * Computer
    * Coffee

    Ordered list:

    1. wake up
    2. drink coffee
    3. whistle while you work
    
**Required syntax**

=== "HTML" 
    ```HTML linenums="1"

    <strong>Bold</strong>

    <em>Italics</em>

    <p>Unordered list:</p>
    <ul>
    <li>Internet access</li>
    <li>Computer</li>
    <li>Coffee</li>
    </ul>

    
    <p>Ordered list:</p>
    <ol>
    <li>wake up</li>
    <li>drink coffee</li>
    <li>whistle while you work</li>
    </ol>
   
    ```


=== "Markdown" 
    ```Markdown linenums="1"
    
    **Bold**

    *Italics*

    Unordered list:
    
    * Internet access
    * Computer
    * Coffee

    Numbered list:

    1. wake up
    2. drink coffee
    3. whistle while you work

    ```


Although Markdown is arguably much easier to write, read, and edit than HTML, it doesn't replace HTML. Instead, Markdown is usually computationally converted to another format (often HTML) before it reaches its end reader, just as we might convert a word document to PDF. In fact, this web page was written in markdown before I used a static site generator called [MkDocs](https://www.mkdocs.org/) to convert it to the HTML your browser is currently rendering.

> "HTML is a *publishing* format, Markdown is a *writing* format"   
>
> -- <cite>John Gruber</cite>, Markdown co-creator

As a result, the exact appearance of the resulting HTML is determined by CSS, not the Markdown itself.

## Comes in many flavors

Since the release of the first iteration in 2004, many variations of Markdown have been developed for a variety of different use cases. Notable examples include [Reddit-flavored Markdown](https://www.reddit.com/wiki/markdown) and [Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) (GFM), each with unique conventions or additional features that are useful when writing content on Reddit and Github respectively.

## Tools for trying Markdown

Markdown files are simply plain text, so you can create them in any text editor, but some editors have additional features that make writing in Markdown more enjoyable. A quick google will produce plenty of lists like this one: [4 open source Markdown editors](https://opensource.com/article/18/11/markdown-editors).

Or, if you want to try out the syntax right now without leaving your browser, here are some in-browser Markdown editors:

* [Dillinger - Online Markdown Editor](https://stackedit.io/app#)
* [Markdown Live Preview](https://markdownlivepreview.com/)
* [StackEdit - In-browser Markdown editor](https://stackedit.io/app#)

Finally, if you want to a quick, interactive tutorial on the basic syntax, I like [this one on markdowntutorial.com](https://www.markdowntutorial.com/).


## Learn more about Markdown

Here are but a few fantastics resources, many by scholars and practioners in technical communication!

### History/Background

* [Markdown co-creator John Gruber's discussion of the philosophy behind markdown](https://daringfireball.net/projects/markdown/syntax)
* [The Markdown Movement | Aaron Beveridge](http://aaronbeveridge.com/markdown/history.html)

### Applications in technical communication

* [Exploring Markdown Authoring to Publishing Workflows | Tom Johnson, *I'd Rather Be Writing*](https://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/)
* [Why you should and should not use markdown | Peter Conrad via *Medium*](https://medium.com/@stymied/why-you-should-and-should-not-use-markdown-1b9d70987792)

### Syntax Guides

* [Markdown Cheat Sheet | markdownguide.org](https://www.markdownguide.org/cheat-sheet/)
* [Mastering Markdown | *Github Guides*](https://guides.github.com/features/mastering-markdown/#intro)



