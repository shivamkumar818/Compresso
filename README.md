File_Compressor


A text file compression tool based on Huffman encoding algorithm. The tool enjoys the benefit given by huffman encoding algorithm, i.e, Lossless compression. We can compress the data upto 30-40% without any loss in the data, saving 60-70% space. This comes very handy in case of cloud sharing.

UseCase
Imagine you have to send a 1GB data file, and you only have 500MB of internet data. No need to worry! Huffman encoding algorithm got you covered. After compression the file's size becomes somewhere around 300MB(not guaranteed) which can now be safely sent without any problems.

About the Algorithm
Huffman coding, an optimal prefix-free binary code, is a renowned data compression technique designed by David A. Huffman in 1952. This ingenious algorithm is based on the principle of assigning shorter codes to frequently occurring symbols in a dataset, resulting in more efficient representation and compression. Huffman encoding achieves this by constructing a binary tree, known as the Huffman tree, where each leaf node corresponds to a symbol and is assigned a binary code based on its frequency in the input data. The algorithm employs a priority queue to efficiently merge nodes with the lowest frequencies until a single root node is formed. The resulting binary codes exhibit the desirable property of being prefix-free, ensuring that no code is a prefix of another. This characteristic simplifies decoding, as it enables unambiguous identification of each symbol in the compressed data. It finds its unique applications in the real-world. Notably, in file compression algorithms such as ZIP and in network protocols where efficient data transmission is crucial.
