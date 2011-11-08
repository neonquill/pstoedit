pstoedit
========

These are my local modifications to
[pstoedit](http://www.pstoedit.net/).  They are designed to support
converting pdf files generated by Adobe Illustrator to pcb files that
can be used by [pcb](http://pcb.gpleda.org/) from the
[gEDA](http://www.gpleda.org/) tool suite.

The current code is based on version 3.50 of the parent project.

Example
-------

    pstoedit -v -f "pcb:-forcepoly" examples/dwatson_test.pdf test.pcb

