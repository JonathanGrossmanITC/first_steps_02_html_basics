# HTML Basics  

Welcome to the second lesson! In this lesson, you continue learning about HTML. You learn about HTML's tag syntax by examining different tag types. By examining tag syntax, you will become familiar with which tags to use in which situation, how to fill tags with content, and how to use the inspector to assist you with writing HTML. You also learn about HTML attributes, which are properties of HTML tags that can help you define and control HTML elements. Finally, you can participate in a live coding session in which you will see how to start a project from scratch and add to it several different types of HTML tags.  

The live coding session is intented to reinforce what you learn in the lesson and to help prepare you for making your personal portfolio site. The code from the session is included in this repository. You can use it however you like, but as with any code you get from someone else, make sure you understand it well enough to explain it to someone before putting it in your own projects.  

In this lesson, you learn:  

- Hour 1: [HMTL Tag Types](#html-tag-types)    
- Hour 2: [HTML Attributes](#html-attributes)   
- Hour 3: [HTML Live Coding](#html-live-coding)  

The topics below outline what you learn in the live session. After the live session, you can use this material as a resource for guided self-learning. This document will serve you as a roadmap for gaining repetition with the material that you learn during the live session.   

Also included in this material is the code from the live coding session.  

## [HMTL Tag Types](#html-tag-types)  
 - [Tag syntax](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)  
 - [Tag types](https://www.w3schools.com/tags/)  
 - Some HTML tags have specific use situations and the content-holding tags come with built-in styles; learn about them to know when to use which tag   
    -- [metadata](https://html.com/document/metadata/) don't appear on the screen but hold important information for your page   
    -- [`body`](https://www.w3schools.com/tags/tag_body.asp) tag holds all the page content and wraps the content-holding tags  
    -- [`div`](https://www.w3schools.com/tags/tag_div.asp) tags are very commonly used, hold text and other HTML elements, and have a built-in `display: block` style property  
    -- [`span`](https://www.w3schools.com/tags/tag_span.asp) tags are like `div` tags because the hold text and other HTML elements, but they have a built-in `display: inline` style property      
    -- [`h1` - `h6`](https://www.w3schools.com/tags/tag_hn.asp) tags hold text and other HTML elements and have built-in `font-size`    
    -- [`p`](https://www.w3schools.com/tags/tag_p.asp) tags hold text and appear as a paragraph       
    -- [`a`](https://www.w3schools.com/tags/tag_a.asp) tags create links to other webpages     
    -- [`img`](https://www.w3schools.com/tags/tag_img.asp) tags display an image on the page  
  - HTML5 may help  
    -- Modernized HTML tags designed for specific use cases  
    -- You may see [HTML5 tags](https://html.com/document/) online or in other people's code  
    -- It's okay to use HTML5 or to not use them; regardless, try to be consistent and predictable with your code  
    -- Among many benefits, HTML5 may make your code [easier for you and other developers to read and maintain](https://html.com/html5/)  
  - How to fill tags with content  
    -- An element with opening and closing tags holds content between those tags   
    -- Self-closing tags hold content in an attribute  
    -- Nesting elements inside other elements is a very common thing to do for purposes of layout and style  
  - Tips on working with images  
    -- [Web Images: Practical Tips Plus Code To Put Them To Best Use](https://html.com/images/)  
    -- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)  
  - How to use the inspector to assist you with writing HTML  
    -- Can you move the inspector to the right side of your browser?  
    -- Can you move the inspector to the bottom of your browser?  
    -- Look at the Elements tab and find the HTML elements  
    -- Where in the Elements tab do you see HTML content?  
    -- In the Elements tab, can you change the name of a tag?  
    -- Do you see any built-in styles for each HTML element?  
    -- How do you open HTML tags in the Elements tab so that you can see what's nested inside?  
    -- Find an img tag -- do you see its source? 
    -- Copy and paste the source into a browser's url
    -- Do you see an HTML5 tags on any websites?

## [HTML Attributes](#html-attributes)   

  - You can use HTML attributes to define and control HTML elements
  - An attribute is a property of an HTML element, and certain type of tags have certain kinds of attributes  
  - Many [HTML attributes](https://www.w3schools.com/tags/ref_attributes.asp) exist, and here are some you will use frequently:
    -- `class` for applying one or more CSS classes to an element (tags: any)  
    -- `href` for setting a link's destination (tags: `a`, `area`, `base`, `link`)  
    -- `id` for giving an HTML element a unique identifier (tags: any)  
    -- `rel` for linking the current document to another document (tags: `a`, `area`, `form`, `link`)  
    -- `src` for setting the url of a media file (tags: `audio`, `embed`, `iframe`, `img`, `input`, `script`, `source`, `track`, `video`)  
    -- `type` for defining the type of element (tags: `a`, `button`, `embed`, `input`, `link`, `menu`, `object`, `script`, `source`, `style`)
    -- `value` for setting an element's value (tags: `button`, `input`, `li`, `option`, `meter`, `progress`, `param`)  
  - Oftentimes you write tags without explicitly declaring any attributes (e.g., `<div>Welcome to ITC!</div>`)
  - When you do declare attributes: 
    -- Do so in the opening tag 
    -- Write attributes in [key:value pairs where the value is a string](https://www.tutorialrepublic.com/html-tutorial/html-attributes.php) (text wrapped in quotes)  
    -- Example: `<a href="www.itc.tech">Enroll</a>`
  - The `href` and `src` attributes  
    -- Can use absolute or relative path  
    -- Absolute path links to an external source  
    -- Relative path links to internal source  
  - You will see in code examples online use of the `style` attribute  
    -- The `style` attribute allows for setting an HTML element's style (called inline styling)  
    -- Do not to use this as your primary way of styling your web applications because it can be difficult to maintain  
    -- It is okay to not even use the `style` property or to use it only in special situations  
    -- Instead of using `style`, use a stylesheet that you write or import from a CSS framework
  - Some HTML attributes listen for events, and then trigger functionality when that event happens  
    -- Examples: `onchange`, `onclick`, `oncopy`, `ondrag`, `onsubmit`  
    -- When you learn JavaScript, it is better that you not use these  
    -- Instead, use JavaScript code to listen for events instead of an HTML attribute for code that is easier to read and maintain  
  
## [HTML Live Coding](#html-live-coding)  
 
