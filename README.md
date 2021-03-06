## Horiseon

[Horiseon Social Solution Services](https://revywatson.github.io/code-refractor/) provides search engine optimization, online reputation management, and social media marketing. They specialize in brand awareness, cost management and strategies for connecting costumers directly to websites.
https://revywatson.github.io/code-refractor/

![Screenshot (51)](https://user-images.githubusercontent.com/76264693/111364410-8ff6c600-8667-11eb-9583-3e800bff14db.png)
![Screenshot (52)](https://user-images.githubusercontent.com/76264693/111364417-92f1b680-8667-11eb-9897-02ce1abcd4e9.png)

## Acceptance Critria/
* This webpage must meet accessibility standards
* When user/collegues view the source code there are semantic HTML elements.
* The structure of the HTML elements follows a logical structure independent of styling and positioning.
* The image elements have accessible alt attributes.
* The heading attributes fall in sequential order.
* The title element is concise and descriptive.

## What, how and why…

* The navigation link at the top right of the page for "Search Engine Optimization" was not functioning. The element was missing `<id="search-engine-optimization">` within the section opening tag.

* The original code provided by [Horiseon](https://revywatson.github.io/code-refractor/
) had the `<div>` element tag used almost exclusively throughout the html file. I went through and replaced all of the `<div>` element tags with semantic html elements such as: `<header>`, `<footer>`, `<nav>`, `<article>`, `<section>`, etc.

* When I replaced the `<div>` elements for the ` <nav>`, and `<footer>` the appearance of the website changed. In order to maintain the original appearance I also had to edit the CSS style sheet. I replaced the div element for nav, and changed the .footer class into an element selector of footer. 

* **All** of the images were lacking alt attributes. I added alt attributes to all of the images on the html file. Initially when I drafted up descriptions for the alt attributes I was quite verbose. I tried to put myself in the shoes of a visually impaired person. I wanted to be as descriptive as possible and _really_ paint a word-picture! However, I was informed that the alt attributes are typically meant to be no more than two to six words. I did my best to condense them.

* The alt attribute for the background image was trickier. In most of my searches I found the other coding professionals seem to think that adding an alt attribute to a background image is not worth the effort, and or it is entirely impossible since the image is linked through the CSS file. I attempted many variations of code to achieve this. I’m still not certain if I succeeded.

* The link for the CSS style sheet was missing the file type so I added `type="text/css"` to clarify for others that may work on this project after me.

* The title was "Website". I changed it to be, "Horiseon Social Solution Services". In a real world setting I would ask the client if they preferred the use of the full company name or just "Horiseon".

* Consolidated the CSS codes. Several of the class attributes had the same code and were taking up space. By consolidating them the style sheet looks less congested and cleaner.

* Added a variable function at the top of CSS file. Only included the code in which I noticed colors repeated throughout the style sheet. I have hopes that as this projects changes and expands so shall the variable portion.


## The goal…

In building this project I hope to have gained experience and knowledge while simultaneously satisfying the client’s expectations and needs.
