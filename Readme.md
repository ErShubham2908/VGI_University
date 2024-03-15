# HTML - HyperText Markup Language
HTML - HTML stands for **Hypertext Markup Language**. It's the standard markup language for creating web pages and web applications. HTML provides the structure and content of a webpage by using a system of tags and attributes.

These tags define the various elements of a webpage such as headings, paragraphs, links, images, forms, and more. Web browsers interpret HTML documents and render them into visual web pages for users to view and interact with on the internet.

## What is Tag, Attributes, Elements, and content?
1. Tag : Imagine tags like little instruction manuals for the web browser. They come in pairs, a start tag < and an end tag >  with the element name in between. For example, 
< h1> is a start tag for a heading element, and </ h1> is its closing tag.

    Ex - img tag for image, p tag for paragraph, h1 to h6 for heading.

2. Attributes : Attributes provide additional information about HTML elements and are always specified in the opening tag of an element. Attributes are made up of a name and a value, separated by an equal sign (=) and enclosed in double or single quotes. Attributes modify the behavior or appearance of an element.

    Ex : the href attribute in an < a> tag specifies the URL of the link, and the src attribute in an < img> tag specifies the source (URL) of an image.

3. Content : This is the information that goes between the start and end tags of an element. It can be text, images, videos, or even other HTML elements (elements can be nested within each other). The content determines what the user sees or interacts with on the webpage.

    Ex : `<p>This is Paragraph Content</p>`

4. Elements : An element is a complete set of tags and their content, including the opening tag, closing tag, and any content nested within them. Together, they define a particular component or piece of content on a webpage.

    Ex : `<p>This is a Paragraph.</p>`


## heading In HTML - Six heading tag
# h1 - Heading 1
## h2 - Heading 2
### h3 - Heading 3
#### h4 - Heading 4
##### h5 - Heading 5
###### h6 - Heading 6

# Q 1. Difference b/w b tage and strong tag, i tag and em tag?

## Fonts tag in HTML
1. **b tag:** The < b> tag is used to make text bold. However, it doesn't carry any semantic meaning and is purely presentational.
2. **strong tag:** Similar to < b>, the < strong> tag also makes text bold, but it carries semantic weight, indicating that the enclosed text is of strong importance.
3. **i tag:** The < i> tag is used to italicize text. Like < b>, it doesn't carry any semantic meaning and is purely presentational.
4. **em tag:** Similar to < i>, the < em> tag italicizes text, but it carries semantic weight, indicating emphasis.
5. **u tag:** The < u> tag underlines text.
6. **s tag:** The < s> tag is used for strikethrough text, indicating that the content is no longer accurate or relevant.
7. **del tag:** Similar to < s>, the < del> tag also represents strikethrough text, but it carries semantic weight, indicating deleted text.
8. **mark tag:** The < mark> tag highlights text with a background color, typically yellow.
9. **sup:** The < sup> tag is used for superscript text, often used for mathematical expressions.
10. **sub:** The < sub> tag is used for subscript text, typically used for footnotes or chemical formulas.

## Tag in HTML

**1. Semantic tag:** A semantic element clearly describes its meaning to both the browser and the developer.
- Ex - < form> < table> < header> < footer> < article>

**2. Non-semantic tag:** < div> and < span> is non-semantic tag

**3. Block-Level Element:** Block-level elements typically start on a new line and occupy the full width available (by default). They force a line break before and after their content.
- Ex: < header>, < nav>, < section>, < article>, < aside>, < main>, < footer>, < h1> to < h6> headings, < p>, < div>, < ul>, < ol>, < table>, < form>, < pre>, and < hr>

**4. Inline Element:**  Inline elements typically display their content on the same line with surrounding text and only occupy the space needed for their content. They don't inherently create line breaks.
- Ex: < span>, < b>, < i>, < strong>, < em>, < a>, < img>, < code>, < em>, < sup>, < sub>, < br>, and most emphasis and formatting tags.
  
|Feature|Block-Level Elements|Inline Elements|
|-------|--------|-------|
|Line Breaks|Force line breaks before and after by default|Don't inherently create line breaks|
|Width|Occupy full available width (by default)|Only occupy space needed for their content|
|Stacking|Can stack vertically on top of each other|Can flow horizontally alongside other inline elements|

In HTML, there's a distinction between how tags are used depending on whether they represent elements that can contain content or not. Here's a breakdown of self-closing tags and separate closing tags:

**1. Self-Closing Tags:** These tags are written with a forward slash (/) directly following the element name and before the closing angle bracket (>). They represent elements that don't contain any content within them.

***Note:** While self-closing tags are valid in HTML, some stricter environments like XML might require them to be closed with separate tags (e.g., < br> instead of < br />).
- Ex: < br/> (line break), < hr/> (horizontal rule), < img src="image.jpg" alt="Image description" /> (image), < input type="text" name="username" /> (form input field). 

**2. Separate Closing Tags:** These involve an opening tag with the element name followed by a closing angle bracket (>), and a separate closing tag that starts with a forward slash (/) followed by the element name and a closing angle bracket (>). They represent elements that can contain content within them.
- Ex: < p>This is a paragraph.< /p>, < b>Bold text< b/>
< div>This is a section with content.< /div>
## Image and Multimedia
### Image 
    tag - img 
    attributes - src (source), alt 
    width, height

## Video 
    tag - video tag, source tag
    attributes of video tag - autoplay, controls, muted
    attributes of source tag - src (source link), type (video type)

## 2nd March 
### What is List?
### Ordered List
    tag - ol - ordered list - parent tag
    li - list items
    attributes 
        type - A, a, I, i, 1 (default)
        reversed - to reversed the list item
        start - always accept number as value
### Unordered Lists
    tag - ul unordered list
    li - list item
    attributes - type -  Square, circle, disc, none

### Description List
    

# 7th mar '24

## Table in HTML

## Tag - Table, th - table heading, td - table data, tr - table row
## Attrbiutes - table  (Border)
## colspan, rowsapn, cellspacing, cellpadding


## 9th Mar '24

## form in HTML
1. Form tag -  sep closing tag
   1. attributes - action 
2. label - sep. closing tag
   1. attribute - for
3. input - self closing  tag < input />
   1. attributes - type, placeholder, name, id, value, required


### Q1. Create a form using HTML, form contain Name, Email, Password, Gender (Male, Female, Other), fav Language (HTML, CSS, JavScript, React JS) and Submit Button

## Q2. Create a form - contain Name, email, password, DOB

## 14th Mar '24

### Q1. creaet a profile using HTML, profile contain student Name, Education, DOB, Address and P-size Photo. detail about your education in detail, address in detail, hobby, interesst, skill, technology you know, project you completed in school and college.

# 15th Mar '24
## CSS - Cascading Style Sheet
1. inline CSS
2. internal CSS
3. external CSS

P - Inline > Internal > External

CSS Selector
1. Universal Selector (*)
2. group Selector
3. Tag selector
4. ID Selector
5. Class Selector

## Q1. Heading with h3 and color is green and font size id 100px; (use class, A to M, ID N - Z)