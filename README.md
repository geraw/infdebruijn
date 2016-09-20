# A repository for files on infinite de Bruijn sequences and other creatures

This repository contains some preliminary results on de Bruijn sequences that we are working on.


## Outline of the proposed results
In essence, we are trying to establish the following results

* Onion property of prefer-max de Bruijn sequences: The nth sequence is a suffix of the (n+1)th sequence.

* Thus, the revere of the prefer-max sequence is an infinite de Bruijn sequence.

* The reversed sequence is a concatenation of representatives of cycles when we chose, as representative of a cycle, the first word in right-to-left lexicographic order.

* We can identify efficiently the position of every word as a "window" in this sequence.

* We can characterise this sequence as the result of a "cycle joining" process.

* This gives us properties that we call "jigsaw":
	* Cycles begin in increasing order: The (k+1)th cycle begin after the kth cycle (when ordered as described above).
	* Cycles are traversed linearly: If we project out all vertexes that are not on the cycle, we get that each remaining vertex is a rotation by one of the previous one.

	## Applets
Some of our constructions can be visualized using the foilowing links:

* [A demonstration showing how we propose to scan cycle representatives forwatrds and backwords](https://www.wolframcloud.com/objects/user-2002534f-d771-4ce5-afa8-f29d048208eb/Next word generator)
* [Word enumeration with highlgted "window"] (https://www.wolframcloud.com/objects/user-2002534f-d771-4ce5-afa8-f29d048208eb/Highlighter) 
