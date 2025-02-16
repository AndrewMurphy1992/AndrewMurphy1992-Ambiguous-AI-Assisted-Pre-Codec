# AndrewMurphy1992-Ambiguous-AI-Assisted-Pre-Codec
A pre-compression algorithm that amplifies the effect of traditional compression algorithims based on Huffman, logarithms, etc.

WARNING: I AM NOT RESPONSIBLE FOR YOUR LOST DATA, OR MISUSE OF AI. KEEP BACKUPS OF ANY FILES YOU USE THIS 'PRE-COMPRESSION' ON. THIS IS A BETA PROGRAM AND ANY DATA YOU CODE THIS WAY IS VERY LIKELY TO BE CORRUPTED AND LOST FOREVER, OPTIMIZATIONS HAVE NOT BEEN MADE, AND IT DOES NOT YET HAVE A FINE-TUNED DECODING LLM. YOU WOULD HAVE TO USE AN UNTUNED LLM. YOU HAVE BEEN WARNED.  

How to use: Simply run either program on your text document. Next, use the traditional compression of your choice. To fully decompress, unzip the file. Next, feed the document to an LLM. With one layer of pre-compression LLMs will usually give you back something correct or very close to the original text.

#Update: Also included 'Vowel' program. This program demonstrates the concept of this process which is very much like the gameshow 'Wheel of Fortune.' It will ask you to open a file, and when you give it a text document it will remove all of the vowels and print the new document as a string in terminal. It seems AI is still able to read these texts, which is interesting. I can't.


Ambiguous-AI-Assisted-Text-Codec
Precompression Algorithm that makes your Compression more Compressive

It's all in the title. Actually, the below code is only the pre-compression part, which for us is simpler than the post-decompression part. The code was written using GPT 3.5, and what it does is generate a modified document before traditional compression is used. How I modified it is, I had it take the least commonly occurring symbols, which have the longest code, erased that code, and assigned it to the same code as the most commonly occurring symbol, which has the shortest code. As intended, that's pretty ambiguous. How are we going to decompress a document which has had half of the detail in the compressed string removed? How do we know which letters are which? Well, how do you know that one letter isn't an A vs. a Z? It's probably an A, in most cases. And that's where Artificial Intelligence comes to the rescue! We don't really want A and Z to be paired, we want A, or whatever the most commonly occuring character is, to be paired with the next most commonly occuring character. This makes the list of codes half the length, and the resulting Huffman codes can be shorter. 

You can also run the program on your text twice. That's harder to decompress, because it isn't as clear which characters are which. However, when compressed, the string will be even shorter. 

After I pre-compress many text documents, I'll use a tool like Tensor Flow to train an AI by having it match both the compressed and uncompressed documents. With a large enough data set, it should be enough for a deployment of a tuned AI decompress (actually to an extent, decrypt) the ambiguous document. 
