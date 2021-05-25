## Links 
Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing.

You will commonly come across the following types of links:
* Links from one website to another
* Links from one page to another on the same website
* Links from one part of a web page to another part of the
same page
* Links that open in a new browser window
* Links that start up your email program and address a new
email to someon

## Writing Links:
Links are created using the < a> element. Users can click on anything
between the opening < a> tag and the closing < /a> tag. You specify
which page you want to link to using the href attribute.

# Directory Structure
On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories.

## Relative URLs

Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.

## what is Email Links?
mailto: 
To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the < a>
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.
On the right you can see that
an email link looks just like any
other link but, when it is clicked
on, the user's email program
will open a new email message
and address it to the person
specified in the link.

# Summary
LINKS
* Links are created using the < a> element.
* The < a> element uses the href attribute to indicate
the page you are linking to.
* If you are linking to a page within your own site, it is
best to use relative links rather than qualified URLs.
* You can create links to open email programs with an
email address in the "to" field.
* You can use the id attribute to target elements within
a page that can be linked to.

# Layout ;
Key Concepts in Positioning Elements
# Building Blocks:
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.

# Containing Elements:
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The <div> element that contains this group of
elements is then referred to as the containing element

# Screen Sizes :
Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.