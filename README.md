# huffman

A simple and pure Haskell implementation of the Huffman encoding algorithm.

The @huffman@ function provides the original O(n log n) algorithm implemented
with a priority queue.  If the input symbols are sorted by probability,
the O(n) @huffmanSorted@ function can be used instead.
