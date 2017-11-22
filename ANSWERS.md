Try using a TreeMap and a HashMap instead of MyHashMap.
Are the resulting word frequencies any different?

There should not be any difference if both work correctly


Is the time performance any different? If so, how would you rank the three implementations (in increasing order of time complexity)?

HashMap works faster most of the time because it does not need a sorted table to run. In this case I believe HashMap would run faster
1. HashMap
2. MyHashMap (should really be the same as HashMap though)
3. TreeMap


How are % and Math.floorMod different? Which works more reliably for computing a hash table index?




What is the time complexity of MyHashMap.size(), and how could you make it much more efficient?




How does this implementation compare to one where you would directly use your linked Node class from the earlier assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
