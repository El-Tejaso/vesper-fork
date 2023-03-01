# Vesper-Fork

Originally a fork of https://github.com/raunofreiberg/vesper.

This is the best VSCode I have seen by far. In fact, it is the only theme I have ever started using daily apart from the default VSCode default theme. However, it had a few issues (and the maintainer did not drop everything they were working on at the time and fix them within 5 min of my github issue), so I have decided to make a fork with my fixes. 

## Current issues

Can't find any others so far

## Fixed issues

- Can't read comments in git-dif
- Comments cant be read when Ctrl+f selection is over them
    - Fix: Made comments blue (#8eb7ff). Looks better than I thought it would
- nil, null, undefined kewords are being highlighted the same as varaibles
    - added settings to the JSON
- hard to see what tab is selected
    - Increased tab brightness.
    - Also I made the editor background pitch-black. Totally unnecessary, but I think it look cool.
    I think people avoid #000 at all costs, because it ruins all shadow effects that a UI popup modal might have. I don't really care about those though