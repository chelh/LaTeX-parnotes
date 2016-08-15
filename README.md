parnotes
========

The parnotes package adds a new note type, `\parnote`. Parnotes are set as normal, running paragraphs and may be placed two ways: (1) automatically, at the end of the paragraph, or (2) manually, using the `\parnotes` command.

To place parnotes automatically after every paragraph, use the `autopn` environment:

    \begin{autopn}
    Text\parnote{parnote}
    
    Text
    \end{autopn}
    
If environments are used within `autopn`, another `autopn` environment must be nested within them. To place notes elsewhere, use the `\parnotes` command.

For more details, read the project documentation in `parnotes.pdf`.

Contributing
------------
The development repository and the bug tracker for this package are hosted [on GitHub](https://github.com/chelh/LaTeX-parnotes).

License
-------
Copyright &copy; 2012, 2016 Chelsea Hughes

This work is distributed under the LaTeX Project Public License, version 1.3 or later, available at http://www.latex-project.org/lppl.txt

I currently maintain this project (comprising `parnotes.sty`, `parnotes.tex`, `README.md`, and the derived file `parnotes.pdf`) and will receive error reports at the project GitHub page (see **Contributing** above).

This package was started due to a question at the TeX Stack Exchange: http://tex.stackexchange.com/questions/34746/

Thanks to Stack Exchange users Ahmed Musa, Bruno Le Floch, and David Carlisle.
