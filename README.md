# Horiseon webpage

## The Task
The following webpage was refactored in order for the codebase to follow accessibility standards so that the web site would be optimized for search engines. Modifications were made to the index.html and style.css in order to fulfill this requirement. 

## HTML Modifications
* Changed "website" in title tag to "Horiseon" to reflect the webpage.
* Changed "div" tag in header to "nav" to signify the section for the web links in the header.
* Changed "div" tag containing header information to "header" to represent the header of the webpage.
* Changed "div" tag to "section" which contained the "hero" class.
* Added a descriptive alt tag to the section tag containing class "hero".
* Changed "div" tag to "section" to signify a different portion for the content code.
* Added 'id="search-engine-optimization"' to link to #search-engine-optimization.
* Removed 'class="search-engine-optimization"', 'class="online-reputation-management"', and 'class="social-media-marketing"' from "article" tags in content section because they were no longer needed in CSS.
* Added a descriptive "alt" tag to each image in each article of the content section.
* Changed the three inner "div" tags to "article" to represent the three different portions within the content section tag.
* Changed "div" tag to "aside" to signify the portion of code that would be on the side of the webpage. 
* Changed "div" tags within the aside to "article" tags to separate each aside section.
* Added a descriptive "alt" tag to each image in each article within the "aside" tag.
* Changed "div" tag to footer to represent the footer of the page.

## CSS Modifications
* Changed ".header div" to ".nav" to reflect "nav" tag in html file. 
* Changed ".header div ul" to ".nav ul" to reflect "ul" tag in the "nav" tag in html file. 
* Changed ".header div ul li" to ".nav ul li" to reflect "li" tag in the "nav" tag in the html file. 
* Removed classes ".benefit-lead", ".benefit-brand", and ".benefit-cost" to consolidate their codes underneath new class ".benefits article".
* Removed classes ".benefits-lead h3", ".benefits-brand h3", and ".benefits-cost h3" to consolidate h3 code under ".benefit h3"
* Removed classes ".benefit-lead img", ".benefit-brand img", and ".benefit-cost img" then consolidated their img code under class ".benefit img"
* Removed classes ".search-engine-optimization", ".online-reputation-management", and ".social-media marketing", then consolidated the code under the class ".content article"
* Removed classes ".search-engine-optimization img", ".online-reputation-management img", and ".social-media-marketing img". Then consolidated the img code under ".content img".
* Removed classes ".search-engine-optimization h2", ".online-reputation-management h2", and ".social-media-marketing h2", then consolidated the code under class tag ".content h2".

## Screenshot of live Github repo
![screenshot](assets/images/github-horiseon-webpage-screenshot.png)

## Link to project
* https://jmaraya1229.github.io/horiseon-webpage/