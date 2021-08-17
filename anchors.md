# ANCHOR ELEMENT 
The anchor element, enables us to create hyper-link our document to another document on the web.
This document can be a web page , files , email addresses , locations in the same , etc.
To create an anchor element, you need to be clear about the following:
*	The word that needs to be clicked before leaving  to another page 
*	The address of the document you want to link to
*	What should happen to the current window? Replace the content with content of the hyperlinked document or open another window?
The general format for anchor element is given below:
<a href=” address-of-document” target=”value-of-how-you-want-to-deal-with-current-window”> Clickable Text </a> 
The attributes are as explained below : 
href = Horizontal Reference 
The reference location of the requested resources.
This location(path or url) can be relative or absolute.

Path can be absolute or relative .
An absolute path or url is a URL that contains the entire address of the page.
It contains the protocol , and the server for the page e.g https://women.bigjara.com/sign-up
It is mostly used when you are linking to a page that is not on the same server as your current page. 

A relative url assumes the the document uses same protocol , and  is on the same server (and domain) like the current page ; so you only add the path to that page.

Assuming we are at the root of your project directory , and we have the following file structure : 
people 
    about.html 
    africans 
        register.html 
index.html 

If you want to link to about.html in people directory , you will use this path format : 
<a href="/people/about.html">
If you want to link to register.html in africans directory that is inside people directory , then the format will be :
<a href="/people/aafricans/register.html">

What if we want to move from a inside a directory to a path that is outside.
Assuming we have a link in about.html that is pointing to index.html , the link will look like :
<a href="../index.html">
Assuming we have a link in register.html that is pointing to index.html , the link will look like :
<a href="../../index.html">
target : This specifies how the target should be opened when in the current window or in entirely a new tab.
Open the target in a new tab if it is external to your page. 
For example , if you are on your page and there is link on facebook , kindly open facebook in another browser tab.

The values include but not limited to :
_self : the current browsing tab and it is the default behavior 
_blank :  This is usually a new tab 


The clickable text should indicate the location of document that you are linking to. 

By default, an anchored text will be underline and the color of the text will be blue.
We can override this default behaviour using CSS (This is a discussion for another time)
Anchored text will appear on the same line if they follow each other sequentially not minding how they were created.
