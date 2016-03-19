# CSS Library

The CSS Library I have put together includes 3 separate pieces: Reset, Common, Media

##Basics

 **Naming Convention**

    You may notice the crazy file names for the css library files. Generally speaking a hyphen (-) is used
    to replace most spaces. For example the space in *library min* is replaced resulting
    in *library-min*.

    Also in the file names the *v* is the beginning of the version number. Generally there will only be one version
    number per file and the specific version number will be separated by a period. An example of this would be
    "common-v1.1.css" where it is the first version of the common file with the first significant change made to
    that version.

    It gets slightly more complicated in the library files however that incorporate several files and their versions
    into only one file. In those cases the start of the versions is still identified by a *v* but then the versions
    for each file are separated by a hyphen in order of: reset, common, media. So a library file may be named
    *library-v1-1-1* where the library incoporates the first version (without changes) of each of the three separate
    files.

  **Reset**

    The reset file is used to strip away most default styles set by a browser. It was created
    to make cross-platform styles more uniform in appearence.

  **Common**

    The common file re-adds some default styling to maintain *expected* behavior. Having some default styling
    seems to be for the best because ground-up styling for every project would just extend the styling phase
    (after incorporating the reset) rather than speed it up (or enhance it).

    Some class styles are also added in the common file for quick styling.

  **Media**

    The media file changes certain styling depending on the pixel width of the screen. As of now (v1)
    this only affects text size.

  **Media Extend**

    This file is almost identical to the Media file but it extends beyond commonly used screen resolutions.
    -> It is not incorporated into the library or library-min files by default.

Last Updated: 3-18-16
