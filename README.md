# Vesper-Fork

Originally a fork of https://github.com/raunofreiberg/vesper.

Most VSCode themes I have seen are quite bad. Most of the time, they sacrifice all of the useability and utility of VSCode's default theme, or they just look bad. I believe this is the first theme I have seen so far that is actually really good, so it has become my daily driver. However there are a few minor inconveniences in this theme that I aim to fix myself, as I believe that spamming the parent repo with issues or constantly hitting F5 on that repo waiting for all of the issues to be fixed is probably not something I would want to do into the future.

## Current issues

Still looking for them

- hard to see what tab is selected


## Fixed issues

- Can't read comments in git-dif
- Comments cant be read when Ctrl+f selection is over them
    - Fix: Made comments blue (#8eb7ff). Looks better than I thought it would
- nil, null, undefined kewords are being highlighted the same as varaibles
    - added settings to the JSON