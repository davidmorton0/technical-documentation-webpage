# Technical Documentation Webpage

The page shows technical documentation on Ruby operators.
The page was made as a project as part of the Free Code Camp course on Front
End Libraries.  It uses html and css and inclues a fixed navbar and uses media 
queries.

## Technical Documentation Webpage Tests

### Content

1. I can see a &lt;main&gt; element with a corresponding id="main-doc", which
contains the page's main content (technical documentation).
2. Within the #main-doc ( &lt;main&gt; ) element, I can see several
&lt;section&gt; elements, each with a class of "main-section". There should be a
minimum of 5.
3. The first element within each .main-section should be a &lt;header&gt;
element which contains text that describes the topic of that section.
4. Each &lt;section&gt; element with the class of "main-section" should also
have an id comprised of the &lt;header&gt; innerText contained within it, with
underscores in place of spaces. The id may include special characters if there
are special characters in the respective &lt;header&gt; innerText. (e.g. The
  &lt;section&gt; that contains the header, "JavaScript &amp; Java", should
  have a corresponding id="JavaScript_&amp;\_Java").
5. The .main-section elements should contain at least 10 &lt;p&gt; elements
total (not each).
6. The .main-section elements should contain at least 5 &lt;code&gt; elements
total (not each).
7. The .main-section elements should contain at least 5 &lt;li&gt; items total
(not each).
8. I can see a &lt;nav&gt; element with a corresponding id="navbar".
9. The navbar element should contain one &lt;header&gt; element which contains
text that describes the topic of the technical documentation.
10. Additionally, the navbar should contain link (&lt;a&gt;) elements with the
class of "nav-link". There should be one for every element with the class
"main-section".
11. The &lt;header&gt; element in the navbar must come before any link
(&lt;a&gt;) elements in the navbar.
12. Each element with the class of "nav-link" should contain text that
corresponds to the &lt;header&gt; text within each &lt;section&gt; (e.g. if you
  have a "Hello world" section/header, your navbar should have an element which
  contains the text "Hello world").
13. When I click on a navbar element, the page should navigate to the
corresponding section of the "main-doc" element (e.g. If I click on a "nav-link"
 element that contains the text "Hello world", the page navigates to a
 &lt;section&gt; element that has that id and contains the corresponding
 &lt;header&gt;.

### Layout

1. On regular sized devices (laptops, desktops), the element with id="navbar"
should be shown on the left half of the screen. It should always be visible to
the user and should remain stationary. You may need to enlarge the viewport or
zoom out to ensure the navbar doesn't scroll with the page content.
2. My Technical Documentation page should use at least one media query.
