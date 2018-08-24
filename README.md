# dexydep

This is an example project to help try to work out dexy dependencies.

Dependencies:

* Dexy
* Asciidoctor
* GNU make

Generate the documentation via:

    make

`output/inc.html` will have content in it; if it has `Unresolved directive in sample.adoc - include::./subdirectory/foo.java` then the `dexy.txt` is still not being properly built.
