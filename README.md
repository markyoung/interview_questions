CSS Quick Assessment
=============
A quick test of basic CSS and jQuery skills.  Used in initial interview for web design candidates.

Preface:
-------------------------------

### Expectations
Complete this assessment by writing CSS or SCSS for Parts 1-2 and javascript for Part 3.  The questions will ask to you fix a common layout bug with CSS floats, create a CSS layout from scratch, and add a simple jQuery UI Button and Dialog to an existing page.  For each of these questions you should not modify index.html but you may modify if you are stuck.  Test your work in Chrome.  You may use any of the listed resources as well as Google for CSS and jQuery reference.

### Process
- Clone this repo into the apache directory (ex. /xampp/htdocs).  Also works without apache by opening the file in a browser.
- Point your browser to [http://localhost/interview_questions] or open the file directly in the browser.
- Edit the questions files
    - Part 1-2
        - CSS (QUESTIONDIR/css/main.css) or SCSS (QUESTIONDIR/scss/main.scss)
        - If using SCSS remember to start the compiler running `compass watch` from the question directory
    - Part 3
        - Edit the base.js file (QUESTIONDIR/js/base.js)
- Verify fixed in Firefox and Chrome.  Check for any javascript errors in the javascript console.
- Come and find me after you are finished


[Part 1: Fix the "-flow":](http://localhost/interview_questions/1-fixlayout)
-------------------------------
Part 1 is asking you to fix a common layout problem with clearing floats, scrolling, and text wrapping.  Edit the CSS/SCSS file to fix the issue.

1. Form wrapper not following inner content height (You should not set a fixed height)
2. Main content does not scroll
3. Extra Credit: Fix the problem with labels and captions wrapping

### Before
![part 1 what to fix](https://raw.github.com/markyoung/interview_questions/master/readme-images/1-1.png)
### After
![part 1 what it should look like](https://raw.github.com/markyoung/interview_questions/master/readme-images/1-2.png)

[Part 2: Simple Layout:](http://localhost/interview_questions/2-simplelayout)
-------------------------------
Part 2 is asking you to create a layout from scratch.  Do part 1 without including the borders and enhance with borders for extra credit.  Follow the example description and screenshot and create the layout editing the css/scss file (sass/main.scss, css/main.css).  [Note: Borders will throw off the box model calculations so you will need to figure out a way around that (there are a few ways and anything css3 is fair game)].


1. Start with the base layout without borders.
    - Header/Footer: height 20%, width 100%, solid colored background #3B8686
    - Sidebars: one left and the other right positioned, fill center area height, width 20%, solid colored background #79BD9A
    - Content: fill center area height, solid colored background #CFF09E
2. Extra Credit: enhance with borders.
    - Header/Footer: 10px border with #0B486B
    - Sidebars: 5px border with #3B8686
    - Content: 5px border with #79BD9A

### Before
![part 2 before](https://raw.github.com/markyoung/interview_questions/master/readme-images/2-1.png)
### After
![part 2 after](https://raw.github.com/markyoung/interview_questions/master/readme-images/2-2.png)

[Part 3: jQuery UI button with dialog:](http://localhost/interview_questions/3-jquerybuttondialog)
-------------------------------
Modify js/base.js to do the following.

1. Initialize all button elements as jQuery UI buttons.
2. For the first button only create a click event that creates a jQuery UI Dialog from the #dialog element.
3. Extra Credit:
    - The title of the dialog "I am the dialog"
    - The content should say "I am the content"
    - Dialog buttons titled "Thanks" and "No Thanks"
    - Dialog buttons should destroy the dialog


### Before
![part 3 before](https://raw.github.com/markyoung/interview_questions/master/readme-images/3-1.png)
### Add jQuery UI Buttons
![part 3 buttons](https://raw.github.com/markyoung/interview_questions/master/readme-images/3-2.png)
### Add the dialog for the first button
![part 3 dialog](https://raw.github.com/markyoung/interview_questions/master/readme-images/3-3.png)


Resources:
-------------------------------
Feel free to search Google or checkout any of these resources.
- [jQuery API](http://api.jquery.com/)
- [jQuery UI Demos](http://jqueryui.com/demos/)
- [jQuery UI API](http://api.jqueryui.com/)
- [Compass CSS: SASS Library](http://compass-style.org/reference/compass/)
