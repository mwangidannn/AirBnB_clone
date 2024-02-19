HTML in a nutshell
HTML is a markup language, which you are expected to be acquainted with from your level 2 project. If you feel like you need a mind-refresher, feel free to check out some tutorials, such as this one: http://learn.shayhowe.com/html-css/

The breadth of HTML is actually not very large, as it is not meant to include advanced features; getting acquainted on each relevant tag and attribute doesn’t take much time, because there aren’t that many. The part of HTML that is trickiest to go over is probably forms, because there are quite a few possible components (text fields, checkboxes, text areas, … even sliders and color pickers in the most recent HTML specifications!)

The promise of HTML is that you should keep your document as properly structured and semantic as you can; and if you do, it should remain easily accessible to the browsers that will exist in 20 years, while also making it easier to keep your code accessible, performant, and optimized for search engines through time. See: http://vanseodesign.com/web-design/semantic-html/

CSS in a nutshell
CSS (Cascading Style Sheets) were invented by Bert Bos and Håkon Wium Lie, because HTML was getting less and less semantic, and more and more about presentation, which would make it less future-proof and more verbose.

For instance, you could write that:
<center><p><font color="red">Hello to <b>all</b> of my visitors!</font></p></center>
The fact that a text should be centered, have a certain color, and be represented in bold is part of presentation, and shouldn’t be in the HTML. The fact that it’s a paragraph, however, is part of the structure, and therefore is semantic information.
Also, if you needed to make a whole page red, you needed to write <font color="red"> at every single line.

CSS enforces not only semantics in the HTML, but also mutualization of the presentation layer, and therefore less code.

Now, <center>, <font> and <b> are banned in HTML, and we got some more semantic tags, like <strong>, <em>, and more recently, <article>, <section>, <aside>, …

Wondering about the difference between <strong> and <b>? –> http://www.html-5-tutorial.com/strong-and-b-elements.htm
