# AUTO-COMPLETE-FEATURE
In this project, we implemented the trie data structure to develop a system where we had a certain number of words preinstalled in our trie. We used the insert function to insert as many words as we wish to.
Then we typed in an incomplete word that we want to auto-complete. If there is no such word with that incomplete word as a prefix then there will be no useful output.
If the incomplete word is in itself the one and only meaningful word in our system then it will only be printed.
If there exist words with that incomplete word a prefix then all such words will be printed.
The time complexity of the algorithm is O(word length + no. of output).
We find out the other meaning of full words with the help of recursion.
