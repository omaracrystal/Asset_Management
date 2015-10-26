# Overview

### Concatenation
> combining several files into one file

### Minification
> get rid of extra characters, comments, white space, shorting variable names, removing console.log etc

### Obfuscation
> Makes code a little harder to read by making it a little harder to read.

### Transpilation
>

### Source Maps
> a tool that can relate between original code vs minified/ transpiled code. when debugging.

### Asset Tagging/ Fingerprinting
> change filename to include a hash ('fingerprint') of the contents of the file. This makes a new 'cache' for browser.

### Source Injection
> change the actual 'src' and 'href' attributes in the HTML to point to the asset-tagged files on a CDN

### Compression
> GZip the files once (before deploying) Configure your web server (Apache/ngnix) to serve gzipped files. Browsers send headers to indicate they can accept gzipped files. Servers send the gzipped versions whenever they can.

### Modules
> Browserify, Webpack, Work similarly to node

### Task Managers
> Gulp, Grunt ... important to Website speed. They can do several things such as: Running Tests, Image Sprites, Icon Fonts, PNG compression, Restarting servers...

### Compare Minification and Obfascation
> Minification's main purpose is to cut down the file size, by taking away extra characters that are not needed. Although this does make code harder to read it's simply just a shorter version of your original code. Now, as for obfuscation, this adds more complexity to your code so that when launched it is a bit harder to read. This doesn't necessarily save file space or time.
