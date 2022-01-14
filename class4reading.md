# HTML 
HTML is a markup language used to structure websites.
* HTML is made up of elements. 
* Elements are used to enclose pieces of content on the site so that it appears or acts a certain way.
* If we wanted to take a statement and display it in plain text, we could enclose the text wth the paragraph tags ``<p>``. For example, I could put the statement "I like chicken" on a site with the line ``<p>I like chicken</p>``.
* In the previous example, the element is the entire string of characters, whereas the content is the phrase. 

## HTML Elements
* Example: ``<p>I like chicken</p>``
* The opening tag is ``<p>``. This is the name of the element, in this case "p". This is where the element will start. For "p" that means where the paragraph will begin. 
* Closing tag: ``</p>``. This is like the opening tag, but includes a forward slash before the element name. This indicates where the element ends. 
* ``I like chicken`` is the content. 
* These pieces together represent the entire element. 
> **Attributes** include information about the element that isn't part of the text. For example, we could add in a ``class`` attribute, which is an identifier we can use to target the element and any other with the same attribute. Attributes are added in elements like this: ``<p> class="editor-note">I like chicken</p>``. The attribute name is ``class`` and the attribute value is ``"editor-note"``
* **Nesting** is placing an element inside another. To emphasize a word in an element, we might use the strong element to emphasize it: ``<p>I <strong>really<strong> like chicken</p>``
* **Empty elements**: Some elements have no content. For example, and image element might look like ``<img src="images/company-logo.png" alt="Company logo"``. In this example, there is no closing tag or inner context. This is because the purpose of the image tag is to input an image, not enclose text.

## Marking up text
* Headings range in levels from 1-6. They are specified with the letter "h" and the desired heading number enclosing your text ``<h1>My heading</h1>``
* Paragraphs are done using a <p> before the content and a </p> after the content.
* Lists are started with ``<ul>`` for unordered lists and ``<ol>`` for ordered lists. The list items themselves are enclosed in ``<li>``

## Links
1. Choose your title, and wrap it in an ``<a>`` element. ``<a>Link name</a>``
2. Add an ``href`` attribute to the element, where the attribute value is the link: ``<a> href="linktopicture.com">Link Name</a>``.


## Wireframing before HTML
Wireframing is a common User Experience excercise where a designer maps out what the site layout will look like (buttons, menus, etc) and how how users will interact with it
* There isn't one *right* way to create a wireframe. Some like to use a specific software such as Invision or Balsamiq, while others prefer a traditional pen and paper. 
* Generally, pen and paper wireframes are easier to edit but don't carry the detailed experience that a software might.
* A detailed wireframe might not always be necessary. Simple websites that only serve one purpose don't need long, drawn out processes. Instead, it might make sense to go straight from sketch to code. 
* If the website serves a high value purpose then it might be better to spend more time with a fully interactive prototype. 

## Steps to Wireframing
1. **Research**: Understand who your audience is, define the use case for your website, and become familiar with how others are creating great user experiences. 
2. **Prepare your research**: You'll want to regularly glance at your research once you start building. Make sure to have it in an easily digestible format for quick reference. 
3. **Map your user flow**: Make sure to draw an end to end view of how users will progress through your website. The easier and more intuitive it is for your user to interact with your site, the better.
4. **Draft and Sketch**: Make sure not to spend endless time making your wireframe look perfect. The idea is to have a rough and well thought out picture of what your site should look like. Save your best efforts for when it comes to building the actual thing. 
5. **Be detail oriented**: Think about what it takes to build trust with your customer. Where should this go? How should you word your call-to-actions, and where should they go? Include common navigation elements, like search box and navigation buttons.
6. **Wireframe to prototype**: Once you've built a solid framework for what your site will look like, it is time to build a prototype. This isn't always necessary but could be valuable depending on the situation. 
> ### Tips:
> ***Clarity is key***. Your wireframe should make it clear to users what your site does and if it suits their needs.
> ***Simple is better***. Try to avoid distractions and include only what is effective in getting your message across. You know what the outcome should be so don't waste users time by having them read too much. 
