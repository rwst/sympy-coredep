# sympy-coredep
Visualization of dependencies of sympy/core

Files:
 * `raw-sfoot.dot` - output of `sfood *.py | sfood-graph` in current `sympy/core`
 * `inside.dot` - only the inside dependencies
 * `outside.dot` - only the outside dependencies
 * `inside.txt`, `outside.txt` - one dep per line
 * `inside.gml`, `outside.gml` - resp. GML files converted via dottoxml
 * `inside-circle.svg`, `inside-hierarchy.svg`, `outside.svg` - visualizations
 
Packages thankfully used, great software:
 * https://furius.ca/snakefood/
 * https://bitbucket.org/dirkbaechle/dottoxml
 * https://www.yworks.com/products/yed

Have fun,
R. Stephan
