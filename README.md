# leetcode documents

1. This question is too simple, used exhaustive method or hash table, hash table(O(n)) is 
   greater than exhaustive(O(n^2)).  
   (这个问题很简单， 使用穷举法或者哈希表，哈希表(O(n))比穷举法(O(n^2))更好。)
2. We can use exhaustive method or exhaustive method and hash table for solution this question,
   traverse all substring, for the former the time complexity is O(n^4), obviously it's too bad, 
   even it can't passing check mechanism of leetcode. for the latter we can use the hash table 
   for "check_repeat function", it will reduce a linear level, so the time complexity is O(n^3). 
   Obviously O(n^3) is bad, too, although it's better than O(n^4). 
   So next ways is "Sliding Window", it can reduce to linear complexity(O(n)), please see the code
   for details.
