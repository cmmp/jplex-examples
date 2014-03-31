Simple examples using JPlex to compute persistent homology.

To run them you will need [Java 1.5+](http://www.java.com/en/) installed, along with the [JPlex](http://comptop.stanford.edu/u/programs/jplex/) library [jar](http://comptop.stanford.edu/u/programs/jplex/files/plex.jar). You only need the standalone jar, there is no need to compile the library from source.

To execute JPlex run: `java -cp plex.jar JPlex`

To open the examples click `File > Workspace Editor`.

In the editor, choose `File > Open` and find the example.

To run an example click in `Evaluate > Eval in Workspace` in the editor window.

All examples plot the barcode graph of the computed persistent homology.

The first example shows points in a line, thus with no 1st order holes.

The second example shows points in a circle, which encompass a 1st order hole.

The third example shows points in a triangle shape and prints the 1 and 2-simplices found.
