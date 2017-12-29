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

@import "chester/custom";               // Bootstrap Overrides
@import "bootstrap/bootstrap";          // Bootstrap Source Files
@import "your_directory/yourFilename";  // Source File excluding .scss from filename
````

That should be all you need to do, and from there, just compile as normal.

## Copyright
The Bootstrap source code is Copyright 2017 Twitter Inc./The Bootstrap Authors. You may use Bootstrap source code freely for any project, providing you credit Twitter/the Bootstrap Authors.

Chester-le-Street ASC source code is Copyright 2016-2017 Chester-le-Street ASC. You can use our code freely for Chester-le-Street ASC projects, but must ask permission to use it for other projects. You must credit Chester-le-Street ASC when using our code in any project.
