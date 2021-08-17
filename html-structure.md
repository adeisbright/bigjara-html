# STRUCTURE OF A WEB DOCUMENT 

A web document is structured similarly to how we structure print information.
A document must have a descriptive header that helps to clearly inform the reader, a body that explains, and a footer with summarizing information.

Same document model is used for web pages.
Let us stop with the talking and create our first page. After that, we will explain what is contained in the document.
What next to do?
*	Create a folder (name it html) in your working directory preferably desktop for easy access
*	Open the folder using a text editor (We are using VS code in this lesson)
*	Create a new file named index.html [see our github repo on html (https://github.com/bigjara/bigjara-html)]
*	Type the text below 
 
Figure 2.1 A simple HTML page 
	Open the document in your file explorer
  
Fig 2.2 File Explorer 

	Launch the document using a Web Browser (Google Chrome)
	You will have the same result as the one below
 
Fig 2.3 Result of index.html 

**Code Explanation** 
Fig 2.1 is an image of our code editor window containing codes for index.html, a simple web page.
What are all those contents doing? 
Now, let’s get started from line 1.

On line 1, we have <!doctype html> ;  that is called a doctype declaration.
It declares the type of document the web browser should render and the version associated with that type. 
It is a mandatory declaration that your html document should contain if you are intending to use HTML5 elements.
With this declaration  , the browser will properly render the newer elements (if supported) using the HTML5 specifications. 
This markup will specifically direct the browser to render the page as an HTML5 compatible page.
Therefore, every HTML5 tags that is supported by the browser should be rendered accordingly.
There are various versions of HTML. The latest version which is the one we are using is version 5 written as HTML5.

Line 2:  Our parent (root) element for our web page is the html element.
Although, if you do not include it on the page your page will still render but hesitate from doing that as its anti-standard.
The element uses the language attribute – lang. This value for this attribute specifies the locale for the web page.
An attribute is a piece of text that provides more information to an element.

It is a key value pair written generally as:
attribute-name=” attribute-value” 
e.g., class=”font-1” 
We use attributes for things like styling, scripting, informing screen readers, etc

Line 3: On line 3 we have the head element. This element is used to contain descriptive information that are necessary for web readers such as Search engines and other open services.

It must carry the title of the page.
Every element in the head will not be displayed in the browser viewport.

Line 4:  We have a meta element on this line. A meta element is used for providing more helpful and useful information about a page.
For example, you will need to use the meta tag for responsive design, and also for stating the character encoding your page is built with.
Meta element attributes are also useful for SEO (Search Engine Optimization) and Social Sharing . 
The name attribute of a meta element differentiates one from the other.
On this page , we have the following names for meta attributes : 
viewport  : use for responsive design 
description and also keyword are essential for search engine optimization.

Line 8: The title of the page is wrapped using the title element. This title will appear in the title bar of a web browser and also as the main heading when your page appears in a search result

Line 10: The body tag which wraps everything that will appear in the browser viewport.
The body element is used for wrapping content that are viewable at load time.
Other elements contained in Fig 2.1 are the subjects of subsequent chapters.
Our next topic will focus on how to create paragraphs.
Hope this lesson was helpful?
Leave useful comments in the forum.
Thank you
