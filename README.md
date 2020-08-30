# Gulp File for WordPress
This is a simple Gulp file for automating some tasks while developing custom WordPress themes. It will run live server, complie SASS files to minified CSS, compress images, and complies ES6 JavaScript to ES5 through WebPack Stream (a Gulp plugin). 

## Commands:

`npm run start` -> Watches and compiles your files. Use it in dev.
<br>
`npm run build` -> Same as start but won't run live server.
<br>
`npm run bundle` -> Bundles and compresses your theme. Creates a folder called packaged and puts the compressed folder of your theme inside it. You can then install it on a WordPress site.

Simply put the files inside your child theme, run npm install and start coding!