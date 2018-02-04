# Sources of the po4a website

This repository contains everything needed to generate the 
[po4a website](https://po4a.org/). Most of its content
is translated, using po4a of course.

The build scripts are not very advanced for now, and you must clone
this repository in a directory containing an uptodate checkout of po4a
(the source code repository). That other repo *must* be called `po4a`.

### Editing

The source files are located in `src/`.

### Building

To rebuild the website, just type `01-build-pages.sh` and you can
inspect the result in `html/`

### Uploading

Just type `02-upload.sh` after rebuilding it.


### TODO

The website uses php to allow switching to other languages, and to
have a common header. Since we compile the pages anyway, it'd be good
to not use php. Viewing the result for verification before uploading
would be easier this way.