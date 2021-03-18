# 2gzip
2gzip is a script to compress recursively all the common files of a web project to gzip (.gz) extension.

Target extensions: js, css, html, svg, txt, eot, otf, ttf, gif.

Usage: sh 2gzip.sh {directory} (optional).

Output example: main.js > main.js.gz

*If the directory parameter is not present, 2gzip will search all the files and folders in the current location where the script is.