COMP30680 Web Application Development
Assignment 1: HTML and CSS
Student ID: 22205530
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
###My thought on concept & design:###
For my website project, I decided to make a personal website displaying my CV and acting as
a place to showcase my personal projects (and in the future, also programming successes). 
Sticking to a black-and-offwhite color scheme, I wanted my website to remind the viewer of
a Wordpress blog and reflect my personality. As an accent color, I used purple and a 
mediumvioletred (see the Home page's feature font), and many of the images have a greyscale 
filter, which removes itself upon hovering on the image (see Writing page's collage-image)
(consulted REF5 and REF8, see in References section).
My website is a mixture of my social media activity, my professional CV, my writing passion,
and an insight into my travel experiences. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
###Requirements & where to find them:###
(0.5) Use all three levels of CSS styling:
I mostly used my website.css file for the css styling of my website. In the beginning, I 
defined the general attributes applicable (i.e., body background-color:whitesmoke (line 3) 
or cursor:default (line 8) to all pages. Then, I created my home page first with the 
animated website name like a typewriter (see REF3), social media icons 
including links to external websites, a navigation bar, a general body, and a footer. To
demonstrate my ability to use page-specific CSS, I have moved the CSS into the <style> section
of p1-home.html (lines 9-139). An example of in-line CSS styling is the scroll box on my
p4-writing.html (lines 58-77) page, where I assigned its style next to its id="scroll-box" 
in the div.

(1) Links to both your own pages and external webpages:
In my nagivation bar and my sitemap, I have internal links between my webpages. Furthermore,
I have two buttons ((a) p1-home.html lines 23-38, 183; (b) p3-portfolio.html line 93 and 
website.css lines 474-502) linking between my pages.
I have linked to external webpages in my social media buttons (p1-home.html lines 151-158,
website.css lines 115-129) as well as external links within the div.features and 
div.features-images sections on my home page (p1-home.html lines 62-138 and 201-236).

(2) A navigation bar:
I implemented a navigation bar with a :hover effect. It connects the pages of my website.
For further inspection, you can find it here: p1-home.html lines 166-174, 
website.css lines 132-156.

(3) At least one table used in an appropriate manner:
I implemented a table on my p2-cv.html page, where I have given it a table-heading, used 
colspan and rowspan to customise the table cells, and used various combinations of 
:first-child and :last-child pseudoelements to affect the border styles. I also included 
different styles and colors upon hovering on the table.
You can find it here: p2-cv.html lines 57-95, website.css lines 505-563

(4) At least one list (ordered or unordered):
I implemented an unordered list on my p3-portfolio.html page, where I defined the 
list-style-type:square and styled it as text-justify: inter-word within its container.
You can find it here: p3-portfolio.html lines 56-72, website.css lines 275-315

(5) At least one local or embedded video:
I embedded a local video of myself (p3-porfolio.html lines 45-52, website.css lines 262-272). 
I also utilised the in-line styling in CSS to define the autoplay, controls, loop, muted, 
and preload="auto" features of the video. With this combination, it has the quickest start-up
and enables looping (because the browser blocks autoplay with sound, that is why its initial 
state is mute and it can be changed with the controls). I read up on the video features on
w3school (see REF6).



(6) At least five CSS3 and four HTML5 specific elements:

I used HTML5-specific elements in:
-- the <video> tag on the portfolio page (p3-porfolio.html lines 45-52, website.css lines 
262-272), which I explained further above.
-- the <header> tag, which I used to contain and signify for my animated typewriter font and 
my social media buttons (p1-home.html lines 145-162, webside.css lines 91-129).
-- the <nav> tag, which I used to contain and signify my navigation bar (p1-home.html lines 
166-174, website.css lines 132-156).
-- the <footer> tag, which I used to contain and signify my social media links as footer 
links (p1-home.html lines 240-263, webside.css lines 682-740) and a sitemap of my pages, as
well as the footer info of my copyright notice.
-- the <figure> tag, which I used on my gallery page (p5-travel.html lines 57-86, website.css
lines 372-440) together with the <figcaption> tag to simplify image alignment with their
respective caption.

I used CSS3-specific elements in:
-- my feature-font on p1-home.html (lines 39-49, 181), where I used a linear-gradient background
and several -webkit properties to fill my font with a color gradient and a thin black border
around the letters (learned with REF1 and REF2).
-- my "Goldenboy" title with id="extra-1" (p4-writing.html line 48, website.css lines 331-340),
where I used the new CSS3 property of a solid text-shadow helping with the readability of the
golden text on that page.
-- my gallery on p5-travel.css (website.css lines 431-2), where I used the CSS3 properties of
transform:scale(1.5) to make the image larger upon hovering (learned with REF9) and the 
transition:0.4s property, which allows effects to happen less abruptly.



(8) Make use of both inline and block elements:
I implemented many inline and block elements throughout my pages. The div elements I learned
by taking the medialoot example as guidance (REF10), which is how I structured most of my
pages with a reset.css page, a fixed width of 900px, and positioning of smaller divs within
the larger divs with margin and padding values.

(7) Make use of the CSS positional properties (e.g. position, float):
(9) Explore elements of HTML and CSS that make a website responsive:
To make my website reponsive, I created a flexbox for my gallery images (see p5-travel.html 
lines 57-86, website.css lines 372-440), where I first created a container div#gallery with
a width:75%, which adjusts the images according to the web browser's size. For this, it was
crucial to have the div#gallery with a position:relative to the previous oage element, as well
as the images with position:relative to each other and a display:flex, flex-direction:row and
flex-wrap: wrap. To place the <figcaption> underneath each flexbox element, I used the
align-self:flex-start property.
~~~~~~~~~~~~~~~~~~~~~~~~
###Other points of interest:###
-- on the cv page, I used the pseudo-element ::first-letter in the work experience section as
well as a hover effect with a display:none and display:inline property for the years.
-- on the writing page, I used <span> tags to style the abstract text, a hover effect to add
color to the collage image, and a scroll box for the beginning of my written passage. The
written text I stylised to look like a novel page with text-ident and another ::first-letter.
~~~~~~~~~~~~~~~~~~~~~~~~~
###References:###

-(REF1) Gradient in hero-image h2 font:
https://codepen.io/argyleink/pen/OJMEpGp

-(REF2) Set Font Border in CSS:
https://www.delftstack.com/howto/css/css-font-border/#:~:text=font%20in%20CSS.-,Use%20the%20%2Dwebkit%2Dtext%2Dstroke%20Property%20to%20Apply%20Borders,browsers%20like%20Safari%20and%20Chrome

-(REF3) CSS Typewriter Effect for header font:
https://css-tricks.com/snippets/css/typewriter-effect/

-(REF4) Scroll Box:
https://www.quackit.com/html/codes/html_scroll_box.cfm

-(REF5) Display an Element on Hover:
https://www.w3schools.com/howto/howto_css_display_element_hover.asp

-(REF6) HTML <video> Tag:
https://www.w3schools.com/tags/tag_video.asp

-(REF7) Image <figcaption> tag:
https://www.w3schools.com/tags/tag_figcaption.asp

-(REF8) Black/White to Color Image on Hover:
https://thebrandsmen.com/css-image-hover-effects/

-(REF9) Enlarge Images on Hover:
https://success.appen.com/hc/en-us/articles/202703155-CSS-Guide-to-Enlarge-Images-on-Hover

-(REF10) Guidance on website layout and div-sections:
https://medialoot.com/blog/how-to-code-a-homepage-template-with-html5-and-css3/