INTRODUCTION
============
- To understand the organization of the styles in this site, please read the comments in "main.scss".
- The compiled CSS file will be: /public/assets/build/css/main.css.
- Note: if you want to add a new scss file, create it in the appropriate directory and then write a reference to it inside main.scss.
- IMPORTANT: DO NOT modify any of the files inside the "global", "layout-partials" and "components" unless all the FrontEnd team agrees with it; those are VERY important files and editing them would have repercussions on the entire website.

COMPASS COMMANDS
================
- Run "compass watch" in dev mode.
- Run "compass compile --output-style=compressed --force" for production releases

OTHER NOTES
===========
A compass plugin is used to split the CSS file into multiple files. This is done to cope with the 4096 selector limit of Internet Explorer 9<
The resulting files will be "assets/build/css/main.css", "assets/build/css/main_2.css", "assets/build/css/main_3.css" ...
