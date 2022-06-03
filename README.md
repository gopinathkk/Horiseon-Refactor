# Code Refactor Starter Code
The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.
This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px
this webapge includes Accessibility features which ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards.

Refactoring by Gopi K :22May2022
The following changes have been made to refactor the HTML code.
Commit 1:
- Reorganised lines to improve visual and readability of the HTML code
- added the following Semantic elements
    head: added meta vieport, chnaged <title> to "Horiseon" from "website"
    body:  - added a <header> to page title
           - added <nav> to header links
           - added "id=search-engine-optimization" for the link #search-engine-optimization
           - added "alt" attributes to all images
           - removed </img> from "benifit cost"
           - added <footer>
           - added classes available in css to <img> in "benefit" div
           - Index.html still has several instances where generic <div> tags used, that are replaced with semantic elements <article>, <section>, <aside>
           - The <title> element updated from "website" to the "Horiseon"
           - The "alt" attributes added with brief description of each image to make them actually accessible to screen readers

    CSS:
            - added comments to CSS sections
            -CSS file has multiple instances where selectors with identical styling properties, and those are moved to the same like so the styling only needs to be written once
   