# Introduction to HTML 
This is the first course we will be offering in our front end or full stack path. 
At the end of the course , you should be able to do the following : 
* Understand how the web works 
* Understand how to use and create HTML tags 
* Tell the difference between elements , tags , and attributes 
* Properly create a web page  
* Be able to build a that conforms to web standard 

## TABLE OF CONTENTS 
1.	Understanding the Internet 
i.	Understanding Internet Fundamentals
ii.	Internet Protocols: HTTP, FTP, and SMTP 
iii.	Client – Server Architecture and Distributed Systems 
2.	Introduction to HTML5 (Elements, Tags, and Attributes)
3.	Structure of a web document
4.	Paragraph 
5.	Headings 
6.	Anchors 
7.	Images
8.	Audio, and Video 
9.	List 
10.	 Forms 
11.	Table 
12.	Semantic HTML 
14.	Projects
i.	Portfolio
ii.	News Paper Markup 
iii. Cryptocurrency Price Table 
15.	 Assignment and Test

### Understanding HTML 
HTML is an acronym for Hyper Text Markup Language.

It is a language that describes how documents meant for the web should be structured.
When we use the word “Language”:  we mean it is a formalized and generally acceptable way of doing something.
It helps in creating contents that are linked (hyper-linked)
The markup language (first version) was designed by Tim Berners Lee in the early 90's to be used 
with the budding Internet.
HTML uses the concept of elements which are composed of tags and attributes to describe and structure contents.
**Elements**
An element in HTML , is a unit of content that will be rendered within the page.
It consist of an opening tag , ccontent , and sometimes a closing tag.
The format for element is  :
<elementSymbol> {content} </elementSymbol>

An element can be nested meaning it can contain other elements. 
You will see this type of arrangement alot in your work.
It could take this simple form or a nesting with more inner or sub-inner elements :
<elementSymbol> 
    <child1>
    {content} 
    </child1>
    <childN>
    {content} 
    </childN>
</elementSymbol>

Some HTML element have no closing tag , we call such element a void element. An example is <img> 

Some HTML element have no content , we call such element an empty element . An example is <br/> or <hr/>

**Tags** 
Tags are created using an enclosure of left and right angled brackets with a symbol inside.
They are used to delimit the start and end of an element.
Tags are not elements. The p tag is not an element
Opening tag : <symbol> 
Closing tag : </symbol>
**Attributes**
An attribute provides additional information to an element. 
It is a name value pair that follows this syntax : 
attributeName="value" 

An attribute can be a standard attribute which is predefined with already existing intent while you as the page builder can attach your own attribute to an element in your page.
The format for attribute is as follows :
<p class="attribute-value" id="para-1" data-course-code="23456"> Application Security Analysis </p>

HTML elements symbol are not case-sensitive .
<P> Hello </P> will output same as <p>Hello </p> but try to be consistent and in most cases stick with lower lettered 
symbols.

Whenever you open a tag , always endeavor to end it .
<p> Hello 

The above element is a wrong markup since it is missing a closing tag. 

In our basic writing, we do well to structure contents. We use paragraphs to contain a stand-alone thought, we bolden text to convey importance, we create list using bullet points or numbering pattern, etc.
HTML helps us to do all those for documents that are to be shared on the World Wide Web.
Crafting an accessible web document entails learning the syntax of HTML and then using them efficiently.
This book contains helpful examples to make HTML easier to understand.
I will use the example below of a word written on paper and one meant for the web to make HTML revealing.
#### Example 1.1 
**Word on Paper**
Peter will be going to meet Hassan tomorrow 

**Word on Web using HTML**
<p class=”font-2”> Peter will be going to meet Hassan tomorrow </p>

**Explanation** 

In the example above, you will notice we used some characters while crafting our word for the web using HTML.
Those characters are part of what makes up HTML.
An HTML element is used to describe how a character or word should be rendered on the web.
They are created using opening and closing tags.
If an element can be described fully with only the opening tag, then there is no need for the closing tag.
Such element that can describe its content wholly using the opening tag are called void elements e.g., img, etc.

Learning HTML entails learning each of the elements symbol, and how to properly use them in relation to other elements.
The next chapter will begin with the structure of a web document 

