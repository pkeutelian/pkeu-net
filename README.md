# pkeu.net

## Grunt Tasks
1.	grunt-include-replace, to replace flags with standard sections of code (mostly headers and footers)
2.	grunt-autoprefixer/grunt-postcss to fix browser compatibility.
3.	grunt-minify to reduce code
4.	vulcanize to reduce html file and dependent html import into one file.
5.	grunt-contrib-watch to automatically fire whenever watched file patterns are added, changed, or deleted.

code is in Gruntfile.js

## File Structure
The project is split into "dev" and "rel" folders - "Dev" should be where all the coding happens, while "Rel" should be where Grunt dumps all of its compiled results into, and what ultimately should be the only thing uploaded to the webserver.

images are in img/
css sheets are in css/
videos are in vid/

## Code Reuse
The menu bar and footers should be universal and imported on new pages.
New pages should use the "template.html" file as a starting point and renamed to serve the page's purpose.
