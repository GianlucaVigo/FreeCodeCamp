# Learn HTML by Building a Cat Photo App
HTML tags give a webpage its structure

## HTML tags
*HTML elements* have opening and closing tags plus the content in between:

HTML element = \<tag> *content* \</tag>

### Heading
Decreasing importance:

\<h1> *content* \</h1>

\<h2> *content* \</h2>

\<h3> *content* \</h3>

\<h4> *content* \</h4>

\<h5> *content* \</h5>

\<h6> *content* \</h6>

### Paragraph
Paragraph of text:

\<p> *content* \</p>

### Comments

\<!-- *comments* -->

### Main
Main content of the body of an HTML document

\<main> *content* \</main>

### Images [VOID ELEMENT]
The image element is not requiring a closing tag = VOID ELEMENT

Attributes:
- src: image's URL (image location)
- alt: used for screen readers and displayed when fail to load the image (description of the image)

\<img src="*image_url*" alt="*alternative_text*">

### Links
Attributes:
- href: location URL
- target: to open links in a new tab (_blank)

\<a href="*linked_location*"> *clickable_text* \</a>

### Section
Define sections in a document: chapters, headers, footers, ...

\<section> *content* \</section>

### Unordered lists
\<ul>

  \<li> *item1* \</li>
  
  \<li> *item2* \</li>
  
  \<li> *item3* \</li>
  
\</ul>

### Ordered lists
\<ol>

  \<li> *item1* \</li>
  
  \<li> *item2* \</li>
  
  \<li> *item3* \</li>
  
\</ol>

### Figure
It allows to associate an img with a caption:

\<figure> 

\<img src="" alt="">

\<figcaption> *caption_text* </figcaption>

\</figure>

### Emphasis [italic]
Place emphasis on a word/phrase:

\<em> *content* \</em>

### Strong [bold]
Indicate something is of strong importance or urgent.

\<strong> *content* \</strong>

### Form
Get information from user (for instance: name, email, ...)

Attributes:
- action: indicates where the data should be sent.

\<form action=""> *content* \</form>

### Input [VOID ELEMENT] [INLINE ELEMENT]
Several ways to collect data from a form. It's defined within a *form* element.

Attributes:
- type: text, checkbox, radio, ...
- name: it is used to access form's data/field. If multiple associated inputs (multiple radios, ...), use this attribute with same value to have only one alternative that can be selected
- placeholder: hint about what kind of information to enter into an input
- required: if the field is required/compulsory
- id: it's used to identify in a unique way specific HTML elements
- value: if not binary, you can specify a more semantic value
- checked: (for checkbox, radio) option selected by default

\<input type="" name="" placeholder="" id="" value="" required checked> *content*

### Button [INLINE ELEMENT]
Add a clickable button. The default behaviour of clicking it is to submit the form to the location specified in the form's action attribute.

Attributes:
- type: submit, ...

\<button type=""> *Button_label* \</button>

### Label
It's used to associate the text for an input element with the input element itself

\<label>\<input type=""> *content* \</label>

### Fieldset
It's used to associate input and label elements together in a web form.

\<fieldset> *inputs + labels* \</fieldset>

### Legend
Caption for a form. Defined within a fieldset element.

\<legend> *content* \</legend>

### Footer
Define the footer for a document. It contains info like: author, contacts, copyright, ...

\<footer> *content* \</footer>

### Body
Everything visible in a webpage.

\<body> *content* \</body>

### Head
Everything "invisible" in a webpage: metadata.

\<head> *content* \</head>

### Title
Defined in a head element. It defines what the browser will show in the title bar or tab of the page.

\<title> *content* \</title>

### Meta [VOID ELEMENT]
Defined in a head element. It defines multiple metadata.

Attributes:
- charset: specify the characters encoding (ex. utf-8)
- content: different devices' dimensions (mobile, desktop, laptop, ...)
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

\<meta charset="">

### HTML
Contains everything: head + body

\<html> *content* \</html>

Attributes:
- lang: specify the used language (ex. en, ...)

### DOCTYPE
The document is an HTML5 document

\<!DOCTYPE html>
