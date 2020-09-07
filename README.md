# ICDSS Public Website
This website is built on top of the template from https://keenthemes.com/free-bootstrap-templates/asentus.


# How to use
The website uses HTML, CSS, Bootstrap v3.3.6, JS and JQuery. The master branch of this repo is hosted using github pages onto the domain https://www.icdss.club.

To edit any CSS elements of the website itself, please edit using the SCSS files in the sass folder. 

If you are unsure of how to use Sass, do checkout this tutorial https://www.w3schools.com/sass/default.asp.
To compile the Sass files to update the CSS files, either use the VS Code Plugin, Live Sass Compiler, or follow the steps in this website https://webdesign.tutsplus.com/tutorials/watch-and-compile-sass-in-five-quick-steps--cms-28275 to initialise Sass using NPM.

# Limitations and Issues

Currently github pages are served to "https:\\www.icdss.club". However, despite adding the forwarding settings on GoDaddy, only the http version of the naked domain will be forwarded to the www subdomain. 

So only "http:\\icdss.club" can be redirected but  "https:\\icdss.club" will face privacy issue. Apparently this is a limitation on GoDaddy as they currently are not able to forward https naked domain to the www subdomain. https://sg.godaddy.com/community/Managing-Domains/Godaddy-Domain-Does-Not-redirect-when-you-add-https-to-it/td-p/136971
