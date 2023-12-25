HyperText Markup Language (HTML)

W3C oversees standards on the Web. www.w3c.org
World Wide Web Consortium

Fragment Identifiers:
"Anchors" top, middle, and bottom.
http://www.webserver/webpages/next.html#middle

https://developer.mozilla.org/en-US/docs/Web/CSS
CSS3

https://validator.w3.org/

A DTD is a Document Type Definition.

A DTD defines the structure and the legal elements and attributes of an XML document.

 <?xml version="1.0"?>
<!DOCTYPE note [
<!ELEMENT note (to,from,heading,body)>
<!ELEMENT to (#PCDATA)>
<!ELEMENT from (#PCDATA)>
<!ELEMENT heading (#PCDATA)>
<!ELEMENT body (#PCDATA)>
]>
<note>
<to>Tove</to>
<from>Jani</from>
<heading>Reminder</heading>
<body>Don't forget me this weekend</body>
</note> 

Understanding vertical-align, or "How (Not) To Vertically Center Content" by Gavin Kistner.

“How to center in CSS” is a great web tool which helps to find the necessary CSS centering attributes for different situations.

In a nutshell (and to prevent link rot):

    Inline elements (and only inline elements) can be vertically aligned in their context via vertical-align: middle. However, the “context” isn’t the whole parent container height, it’s the height of the text line they’re in. jsfiddle example
    For block elements, vertical alignment is harder and strongly depends on the specific situation:
        If the inner element can have a fixed height, you can make its position absolute and specify its height, margin-top and top position. jsfiddle example
        If the centered element consists of a single line and its parent height is fixed you can simply set the container’s line-height to fill its height. This method is quite versatile in my experience. jsfiddle example
        … there are more such special cases.

https://www.django-rest-framework.org/api-guide/routers/

https://flask.palletsprojects.com/en/3.0.x/

https://tailwindcss.com/
