This folder holds the ENGLISH CV.

It must be named exactly:

    Christian_Korreng_CV_EN.pdf

The "English" entry in the site's "Print CV" menu points at this exact path.
A static site cannot look inside a folder to find whatever PDF happens to be
there, so the filename has to match or the button will fall back to opening a
"not found" tab.

To use a different filename, edit the data-cv attribute on the English button
in index.html (search for: print-cv-lang).
