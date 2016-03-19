# CSS Library

The CSS Library I have put together includes 3 separate pieces: Reset, Common, Media

##Basics

  **Reset**
    
    The reset file is used to strip away most default styles set by a browser. It was created
    to make cross-platform styles more uniform in appearence.
    
  **Common**
    
    The common file re-adds some default styling to maintain *expected* behavior. Having some default styling
    seems to be for the best because ground-up styling for every project would just extend the styling phase
    (after incorporating the reset) rather than speed it up (or enhance it).
    
    Some class styles are also added in the common file for quick *common* styling.
    
  **Media**
    
    The media file changes certain styling depending on the pixel width of the screen. As of now (v1)
    this only affects text size.
    
  **Media Extend**
    
    This file is almost identical to the Media file but it extends beyond commonly used screen resolutions.
    -> It is not incorporated into the library or library-min files by default.
    
Last Updated: 3-18-16
