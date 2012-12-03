# Intro 
Code listing snippet can be used in latex files.
It was tested with MacTex. 

# Usage
In the preamble, type: 
\include{path/to/snippet/codelisting.tex}

And in the document, use something like: 
\lstinputlisting[caption= Hello World, label=helloworld]{path/to/source/helloworld.c}