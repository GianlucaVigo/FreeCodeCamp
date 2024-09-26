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

### Emphasis
Place emphasis on a word/phrase:

\<em> *content* \</em>
