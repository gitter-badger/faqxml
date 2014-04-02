faqxml
======

Generate FAQ lists in html, plain text or TeX (convertible to PDF) from a single source written in XML. The stylesheets also define a glossary document type, which works similar to the FAQ with a simple change of headings and layout.

The [DocBook](http://sourceforge.net/projects/docbook/) xml format includes the qandaset element for the creation of FAQ listings and also a glossary element. 

On the other hand, this project implements simple xsl stylesheets, which I found useful for my own purposes to create a simple FAQ list and a glossary, intended for use in a website, where I wanted to see and control all of the details. There are stylesheets for 'folded' html using JavaScript, long html, plain text and TeX. 

This project is a modification of "faqxml" by Mikhail Yakshin [http://faqxml.sourceforge.net]. Also uses ideas from the book *XSLT (Second edition)* by Doug Tidwell (O'Reilly, 2008).

CURRENT STATUS: xsl files for html are available; others to be developed.


XSLT processor
--------------

You need an XSLT processor program to work with faqxml (and it needs to implement xslt version 2: so xsltproc will not work). There are numerous commercial versions. The preferred free program is [Saxon](http://saxon.sourceforge.net/).


How to use
----------

[TO COME]



Notes
-----

XSLT version 2 is required.

Cross-referencing: uses the ID datatype; note Tidwell, page 192 on limitations of this.