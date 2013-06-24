CSS Quick Test
=============
A quick test of very basic css and javascript skills.  Used in initial interview for web design candidates.

Preface:
-------------------------------

### Expectations
For this test you may write plain CSS or use SCSS (with Compass CSS).  Each part should work the same in Firefox and Chrome.  You may use any of the listed resources as well as Google for CSS and jQuery reference.

### Process
Clone this repo into the apache directory (ex. /xampp/htdocs).  This will allow you to navigate with your browser to [http://localhost/interview_questions].  With a text editor edit the necessary files (sass/main.scss[or css/main.css] for Parts 1 and 2; js/base.js for Part 3).  Test you work in Firefox and Chrome and make sure that there are no errors.


[Part 1: Fix the "-flow":](http://localhost/interview_questions/1-fixlayout)
-------------------------------
Fix the existing bugs by editing the css/scss file (sass/main.scss, css/main.css).

Fix the following problems.
1. Form wrapper not following inner content height (You should not set a fixed height)
2. Labels and captions not wrapping long words without spaces
3. Main content does not scroll

[Part 2: Simple Layout:](http://localhost/interview_questions/2-simplelayout)
-------------------------------
Follow the example description and screenshot and create the layout editing the css/scss file (sass/main.scss, css/main.css).

1. Start with the base layout without borders.
    - Header/Footer: height 20%, width 100%, solid colored background #3B8686
    - Sidebars: one left and the other right positioned, fill center area height, width 20%, solid colored background #79BD9A
    - Content: fill center area height, width 20%, solid colored background #79BD9A
2. Extra Credit: enhance with borders.
    - Header/Footer: 10px border with #0B486B
    - Sidebars: 5px border with #3B8686
    - Content: 5px border with #3B8686

[Part 3: jQuery UI button with dialog:](http://localhost/interview_questions/3-jquerybuttondialog)
-------------------------------
Modify js/base.js to do the following.

1. Both button elements jQuery UI buttons.
2. Clicking the first button creates a blank jQuery UI Dialog.
3. Extra Credit:
    - The title of the dialog "I am the dialog"
    - The content should say "I am the content"
    - Buttons titled "Thanks" and "No Thanks"



Resources:
-------------------------------
Feel free to search google or checkout any of the resources.
- [jQuery API](http://api.jquery.com/)
- [jQuery UI Demos](http://jqueryui.com/demos/)
- [jQuery UI API](http://api.jqueryui.com/)
- [Compass CSS: SASS Library](http://compass-style.org/reference/compass/)
