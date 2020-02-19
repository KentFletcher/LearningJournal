# Understanding HTML
## Chapter 18 Process and Design
  * Who is the site for?-  Need to have a target audience.  - Need to understand who that is. Are you targeting individuals of companies?-
  * Why peole will visit your website.  What aer their key **motivations** and specific **goals**.
  * What are the visitors to your site trying to achieve?  The key tasks and motivations, you wont be able to address every reason.
  * What information do visitors need?  You want them to be able to find the information quickly and effectively.  Are they familiar with your subject area/ brand, products/ services/ info?  What are your most important features that you offer?  Why are you special or what differentiates you?  FAQ are effective.
  * How often are people visiting your site?  How often peole are visiting your site lets you know how often your site should be updated.  Focus on certain sections of your site where there is more traffic and keep that up to date.
  * **Site Maps**- A way of organizing your site to optimize flow for the users.  Seperate information into sections or pages.
    * **Card Sorting**- involve sputting each peice of info on a card and then grouping like info together.  Each group will relate to a page.
  Once the info is grouped into different sections you can the turn it into a diagram, which is your **site map**.  It is important to reflect the customers understanding of the subject.
  * **Wireframes**-  is a simple scetch of key info that need to go on each page of a site. This includes key elements such as : logo, prim. navigation, headings, main bodies of text, user logins, etc.  Ensures key info is not left out.  focuses just on content, creating a visual hierarchy to indicate the most important details.  Good to do before builing a site to get the custoers approval that all needs are met.  See page 463 for sources to do sketch on comp.
  * Getting the message across with the use of design.
    * Content
    * Prioritizing- visual hierarchy * see below for desription.
    * Organizing- grouping into blocks or chuncks.  With similarity or consistency, very effective from a visual scence.  Headings, Proximity, Closure, Continuance, White Space, Color, Borders are ways this can be achieved.
* **Visual hierarchy**- The order to which eyes percieve what they see.  Most web users do not read entire pages.  Achieved through visual contrast.  Images offer a very attractive draw.
  * Size
  * Color 
  * Style
* Designing of Navigation- tells people where to go, but also what your site is about and how it is organized.
  * Concise
  * Clear
  * Selective
  * Context
  * Interactive
  * Consistent

# Chapter 17- Note how these elements are common to most wepages
HTML5 allows you set up your web page easier, by eliminating the need for so may <div>.  Structure is as follows:
![Example of HTML](https://lh3.googleusercontent.com/proxy/EV7jlGdSLrRk6imDE4QpUFzMCdar_V3Zic6n41QsbIaPH5s8z9QFxj6QXjhGS6fDql1UjzlbglnxuVPIBB37PxkksCfxUSuh2Z6LEu0Rc6I)
* **Headers and Footers** <header><footer>-  Header can be used various ways, but commonly it is used to hold the title, some navigation, and possibly a logo.  The footer often share info about the site (author, :copyright: date, privacy policies, etc.), it may also contain contact info or the sites connected social media, and also may have links to move around the page.
* **Navigation** <nav>- This allows you to block together common themed links to improtant information.  Generally you will see it as a unordered list <ul>, with <a href=""> with in the list items <li>
* **Articles** <article>-  a container for info within a site that can stand alone as an independent piece of content.  Ideal for things like articles and blogs, which would sit within thier own <article>.  Can nest articles within articles.
* **Asides** <aside>- If used within an article, can contain info that is related to or supports that article.  If it is outside of an <article>, it is a container for content of that entire page.
* **Sections** <section>- groups relaed content together.  has a class attribute.
* **Heading Group** <hgroup>-  is used to group together a set of 1 or more <h1> elements.
* **Figures** <figure> <figcaption>- used to contain any content that is referenced from the main flow of an article.  Can be used for images, videos, graphs, diagrams, code samples, or just text that supports the main body.  The <figcaption> should be a description of the content of the <figure>.
* **Sectioning Elements** <div>-  use when there is not specific sectioning element.
* **Linking around block-level elements** <a>- this allows you block together child elements, and turn the entire content into a link.

# Chapter 8- Extra Markup
* Doctypes
* Comments in HTML
* ID Attributes
* Class Attributes
* Block Elements
* Inline Elements
* Grouping Text and Elements in a Box
* Grouping Text and Elements inlline
* Iframes
* Information About Your Pages
* Escape Characters
