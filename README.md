asciidoc-dvp-mavenbook
======================

Asciidoc Backend for generating Developpez.com article from Apache Maven Book (https://github.com/ndeloof/apache-maven-book) content.

Usage
=====

Install asciidoc tool (http://www.methods.co.nz/asciidoc/INSTALL.html)

Retrieve the _maven.adoc_ file from the Apache Maven Book repository (https://github.com/ndeloof/apache-maven-book)

Execute the following instruction:

    # asciidoc -a revdate=2014-02-20 -d book -f dvp.conf -o book-apachemaven.xml -v maven.adoc

This will produce the file _book-apachemaven.xml_ from _maven.adoc_. _-v_ parameter for printing processing information. _revdate_ parameter for fixing the revision date.

