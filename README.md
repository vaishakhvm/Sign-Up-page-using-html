# Sign-Up-page-using-html
An example for signup page using HTML
Visit links
1.https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_signup_form_modal
2.http://talkerscode.com/webtricks/facebook-style-homepage-design-using-html-and-css.php


What is HTML?

Firstly, HTML is short for "HyperText Markup Language". That may sound scary, but it simply means it is a language for describing web-pages using ordinary text. HTML is not a complex programming language.
HTML Files

Every web page is actually a HTML file. Each HTML file is just a plain-text file, but with a .html file extension instead of .txt, and is made up of many HTML tags as well as the content for a web page.

A web site will often contain many html files that link to each other. You can edit HTML files with your favourite editor.
HTML Tags

HTML tags are the hidden keywords within a web page that define how your web browser must format and display the content.

Most tags must have two parts, an opening and a closing part. For example, <html> is the opening tag and </html> is the closing tag. Note that the closing tag has the same text as the opening tag, but has an additional forward-slash ( / ) character. I tend to interperet this as the "end" or "close" character.

There are some tags that are an exception to this rule, and where a closing tag is not required. The <img> tag for showing images is one example of this.

Each HTML file must have the essential tags for it to be valid, so that web browsers can understand it and display it correctly.

The rest of the HTML file can contain as little or as many tags as you want to display your content.
Tag Attributes

Attributes allow you to customise a tag, and are defined within the opening tag, for example:
<img src="image1.jpg"> or <p align="center"> ... </p>

Attributes are often assigned a value using the equals sign, such as border="0" or width="50%", but there are some that only need to be declared in the tag like this: <hr noshade>.

Most attributes are optional for most tags, and are only used when you want to change something about the default way a tag is displayed by the browser. However, some tags such as the <img> tag has required attributes such as src and alt which are needed in order for the browser to display the web page properly.
Example:

Below is a basic html document, containing all the essential tags. You can copy the code below, paste it into your editor, and save as "mypage.html" to start your own web page.

<html>
 <head>
  <title>My Page Title</title>
 </head>
 <body>

  This is where all my web page content goes!

 </body>
</html>
