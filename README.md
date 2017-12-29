# Chester-le-Street ASC Sass CSS
This is the SASS CSS repository for Chester-le-Street ASC's Global Styles. [Using Sass](http://sass-lang.com/ "Sass Homepage") on your computer, you can compile these files into CSS for use in any projects.

We use [the Bootstrap framework](http://getbootstrap.com/) for our work because it provides a solid foundation for our responsive web design, and means bugs will be dealt with by the wider community.

## Usage
You can either just compile the Global CSS as is, or can include and use your own files for compilation. This will allow you to make use of mixins.

To `@import` your files, open the `chester.scss` file and add it like so...

````scss
/*!
 * Chester-le-Street ASC CSS
 * Copyright Chester-le-Street ASC
 * Bootstrap Content Copyright Twitter Inc.
 */

@import "your_directory/yourFilename";  // Source File excluding .scss from filename
@import 'chester/custom';               // Bootstrap Overrides
@import "bootstrap/bootstrap";          // Bootstrap Source Files
````

That should be all you need to do, and from there, just compile as normal.
