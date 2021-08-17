# Semantic Element 
Semantic Elements are elements with meaning.
It clearly describes its meaning both to the developer and client agent.
Example of a semantic element is <table> 

When a developer sees <table>  , there is the understanding that it is for presenting data in tabular form.
Also  , <form> is a semantic element.

A non-semantic element does not have inherent meaning e.g <span> , <div> , <b> etc.

HTML5 provided newer semantic elements that could be used to make a web page more meaningful.
In this chapter , we will be looking at those elements and how we use them on pages.

Before the HTML5 addition , web developers used id and class as a way to make markups meaningful.
You would see a code that looks like :
<div id="header">
    <div id="nav">
    </div>
</div>
<div id="footer">
</div>

With our newer elements , we now have elements that we can use meaninfully.
They include :

## header 
The <header> reperesents a container for an introductory content or a set of links (for navigation) 
The header will typically wrap : 
* A logo 
* A heading element 
* Brand identity 

You cannot place header within <footer> or <address> 
You can have more than one header element within a page .
Although , we sometimes constrain ourselves to using header only within the top part of our page 
<header>
    <h1>
        <a  href="/">Bigjara</a>
    </h1> 
    <nav>
        <ul>
            <li><a href="/about" >About</a></li> 
            <li><a href="/contact">Contact</a></li> 
        </ul>
    </nav>
</header>


## footer 
We use the footer element to define a section for our page with secondary information. 
Information  that even if our page does not
show them will not greatly impact the essence of the document 
A <footer> typically contains :
* Copyright information 
* Contact information 
* Brand related identity 
* Legal information 

<footer> 
    <p> Copyright &copy; Bigjara Software 2021. All Rights Reserved </p> 
</footer>

## figure 
The <figure> tag is used to specify self-contained content such as diagrams , images , illustrations , code examples ,etc.
## figcaption 
A <figcaption> defines a caption for a content wrapped by <figure>

## nav 
<nav> is used to define a set of navigation links (links that takes you from one part of a page to another)
See how to use in the example for header above 

## address 
<address> is used to define geographical contents

## main 
<main> tag defines the main content for a document 

## section 
A section within a page is a grouping of contents usually with a heading .
The section element is used to define section within a document 

A web page can be split into sections for introduction , services/content , faq , contact , etc.

<section>
    <h2> Bigjara : Learn a Digital Skill </h2>
    <p> Bigjara makes learning digital skill fun and mastering how to use them fast.
    With reliance on open source tools , and collaboration softwares ; we are able to leverage on 
    the power of the Internet to connect with an exciting audience of young people and 
    people with excellent drive for participating in the global economy
    </p>
</section>
<section>
    <h2> Our Courses </h2>
    <p> Our training covers the following : </p>
    <ol>
        <li> Front End Development </li> 
        <li> Back End Development </li> 
        <li> Digital Marketing </li> 
        <li> Mobile App </li> 
        <li> Blockchain </li> 
        <li> Data Science </li> 
    </ul> 
</section> 

Our example above shows how you can add two sections to a page

## article 
An article is used for defining contents that are standalone and can make sense alone.
You should be able to share the contents of an article independently from the rest of the page/document.
A newspaper article can be shared independently , a blog post  , a forum discussion  , etc.

We create articles using <article> tag 
An example is given below : 
<article> 
    <h2> Bigjara Plans to Join Crypto Exchange Race </h2> 
    <p> Bigjara , the user centric and business automation software firm is planning on 
    participating in the fintech space by building an exchange platforms to rival existing systems
    <p>
    <p> This was made known by one of the company's official , Adeleke Bright on August 17th , 2021 </p> 
    <p> Adeleke in an interview with the news team from <em>Jara TV</em> said : </p>
    <blockquote>
        We have observed with keen interest the changing dynamics as regards finance and how 
        individuals react to these changes .
        It will be in our best interest to join the forces building a safer ecosystem that facilitates
        cross-border payment and faster transaction for all people especially the unbanked .
        For this reason , we are leveraging on our Blockchain experience to help us in participating in 
        the blooming fintech
    </blockquote>
</article> 

## aside 
<aside> defines some content that is aside or can be placed in a different position from the content it is placed in.
Nevertheless  , <aside> contents should be indirectly related to the sorrounding content.
You can use <aside> to markup a sidebar 

See example markup below : 

<section> 
    <main>
        <h2> Bigjara's Achievement in July </h2> 
        <p> We were able to carry out some task in July that were aimed at helping more people gain entry into the digital economy
        </p>
    </main> 
    <aside>
        <p> Bigjara Achievements in 2021 </p>
        <ol> 
            <li> Design and Development of Eventals : An on-demand event rental solution </li> 
            <li> Development of Celchin : An ecommerce solution for electronics and power equipement </li> 
            <li> Deployment of MessageSender : A system for delivering emails and SMS across the globe </li> 
            <li> System Design of Globance Health : A telemedicine inititiative for Sub-saharan Africa </li> 
        </ol>
    </aside>
</section>

## hgroup 
Use <hgroup> for combining or enclosing related headings

## time 
The <time> element defines a specific period in time . It may include a datetime attribute which translates dates into a format machine can understand so as to aid search or reminders.

<time datetime="2021-08-17"> August 17 , 2021 </time>

Valid values for datetime attribute includes the following : 
Year : 2021 
Month : 2021-08 
Date : 2021-08-17
Yearless Date : 08-25
A week  : 2021-W47 
Time : 14:40  , 14:40:35 , 14:40:35:290 

## strong 
Use <strong> to emphasize a content that should appear bold to screen readers
## em 
Use <em> to emphasize a content that should be italicized and also be pronouced with verbal stree by screen readers
## small 
<small> defines smaller text . You can use this for copyrights and comments.
Although you can use styling to make your text smaller thereby putting away need for small


