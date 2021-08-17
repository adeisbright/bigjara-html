# HEADING 

Well written documents are hierarchical. The main point or points in the document are abstracted in to concise and easy to understand group of words.
To create headings for different sections of our document, HTML offers six heading elements.
They are:
*	h1 
*	h2 
*	h3
*	h4
*	h5
*	h6 
The main heading in a page should be structured using h1.
Subsequent headings can use any sub-level headings but ensure tags with lower sub-level headings do not precede those with higher level-heading.
The example below will be used in explaining our point.
We are offering two examples to hit the point straight
Example 1
<h1> About Bigjara </h1>
<p> Bigjara makes learning fun , and programming easy </p>
<h2> Bigjara Services </h2> 
<p> Bigjara offers unique services of which includes the following : </p> 
<ul>
    <li> Coding Training </li>
    <li> Business Automation </li>
</ul>

The example below is a wrong use of heading
Example 1
<h2> About Bigjara </h2>
<p> Bigjara makes learning fun , and programming easy </p>
<h1> Bigjara Services </h1> 
<p> Bigjara offers unique services of which includes the following : </p> 
<ul>
    <li> Coding Training </li>
    <li> Business Automation </li>
</ul>

If you observe the contents in the browser, you will notice some appear to fill the entire width of the browser.
Elements like paragraph and heading are known as block elements.
By default, they will occupy the entire width wherever they occur in a document
