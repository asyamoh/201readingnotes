# Is it hard to Learn?

"Understanding HTML and CSS
can help anyone who works
with the web; designers can
create more attractive and
usable sites, website editors can
create better content, marketers
can communicate with their
audience more effectively, and
managers can commission
better sites and get the best out
of their teams.
I've focussed on the code you
need to use 90% of the time
and omitted the code that you
would rarely see even if writing
websites is your full time job. By
the end of the book, if you come
across the other 10% you will be
able to Google it to find out what
it means quickly and easily.
I have also added practical
information on topics I am
commonly asked about, such as
how to prepare images, audio
and video for the web, how to
approach the design and build
of a new site, how to improve
your rankings in search engines
(SEO), and how to use Google
Analytics to learn about visitors
to your site."


# HTML first chapter ....
## How Pages Use Structure?
 *HTML Describes the Structure of Pages*  
 # how ?

In the browser window you can see a web page that features exactly
the same content as the Word document you met on the page 18. To
describe the structure of a web page, we add code to the words we want
to appear on the page.
You can see the HTML code for this page below. Don't worry about what
the code means yet. We start to look at it in more detail on the next
page. Note that the HTML code is in blue, and the text you see on screen
is in black.
<html> 
<body>
 <h1>This is the Main Heading</h1>
 <p>This text might be an introduction to the rest of
 the page. And if the page is a long one it might
 be split up into several sub-headings.<p>
 <h2>This is a Sub-Heading</h2>
 <p>Many long articles have sub-headings so to help
 you follow the structure of what is being written.
 There may even be sub-sub-headings (or lower-level
 headings).</p>
 <h2>Another Sub-Heading</h2>
 <p>Here you can see another sub-heading.</p>
</body>
</html>
The HTML code (in blue) is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.

# **HTML Uses Elements to Describe the Structure of Pages.**

*Attributes Tell Us More About Elements*
"Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign."

# **HTML5**

* ID Attribute

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).
As you will see when you
come to look at CSS in the next
section, giving an element a
unique identity allows you to
style it differently than any other
instance of the same element
on the page. For example,
you might want to assign one
paragraph within the page
(perhaps a paragraph containing
a pull quote) a different style
than all of the other paragraphs.
In the example on the right, the
paragraph with the id attribute
whose value is pullquote is
made uppercase using CSS.
If you go on to learn about
JavaScript (a language that
allows you to add interactivity to
your pages), id attributes can be
used to allow the script to work
with that particular element.
The id attribute is known as a
global attribute because it can
be used on any element.

* class Attribute
* Block Elements
Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements. 
Examples of block elements are
<h1>, <p>, <ul>, and <li>.

* Inline Elements: 

Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.

## Summary IMAGES
x You can specify the dimensions of images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.
X Images can be aligned both horizontally and vertically
using CSS.
X You can use a background image behind the box
created by any element on a page.
X Background images can appear just once or be
repeated across the background of the box.
X You can create image rollover effects by moving the
background position of an image.
X To reduce the number of images your browser has to
load, you can create image sprites

## HTML5 Layout
For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page. 

*New Html5 Layout Elements*:
HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.

