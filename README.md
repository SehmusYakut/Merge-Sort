# Merge-Sort

[16,21,11,8,12,22]

Firstly; we should divide the array into two until each number remains single.



[16,21,11,8,12,22]


16     21     11	 ||   8   12   22

16   |   21	  11	 ||   8   |   12	 22

16   | 	21	|  11  || 	8  | 	12  |	 22




Then; we compound each single elements with sequently.
					


16 21   |   11   ||   8 12   |   22

11 16 21         ||   8 12 22

8 11 12 16 21 22




Big O notation: O(n.logn) => O(6.log6)


patika.dev ===> https://app.patika.dev
