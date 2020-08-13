# Gulp-assembly
My gulp-assembly includes:
- processing html files (fileinclude for comfort of working with files);
- processing scss files (file minification, auto-prefixer);
- processing js files (file minification, babel for older browsers);
- processing images(images minification, converting to webp for less image weight and writes the code in html for .webp so as not to write it manually);
- processing fonts(converting files to .woff and .woff2, creating a separate file fonts.scss which will store the name of the font, weight, etc., which is then applied together with the mixin from style.scss and creates a font-face without my participation for speed of work)
- task for fonts with extension .otf2ttf, converting this fonts to .ttf;
- task for svg sprite;
