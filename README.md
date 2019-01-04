### `huffman`

A simple and pure Haskell implementation of the Huffman encoding algorithm.

The `huffman` function provides the original _O(n log n)_ algorithm implemented
with a priority queue.  If the input symbols are sorted by probability,
the _O(n)_ `huffmanSorted` function can be used instead.
