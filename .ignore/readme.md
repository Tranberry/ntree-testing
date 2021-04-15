# Directory for temp files

A place for temporary stuff.

## Meant to be added to .gitignore

    # Progrom specific files.
    .originals/**

    # Tempstuff
    .ignore/**

    # Media should not to be stored in rep
    media/**

    # HTML are compiled except the head.html which inserts favicons
    # among other things.
    *.html
    !.dist/head.html
