# Java - CheatSheet
A quick help from myself to myself to avoid confusions with Python


### Strings

``` 
String name = "Hello";
name.length();
name.charAt(3);
name.substring(0,5); 	// Exclusive upper limit
name.toUpperCase();
name.toLowerCase();
name.equals();
name.toCharArray();	// Useful when iterating thought chars
```

****

### Arrays
``` 
import java.util.Arrays;

int[] arr = new int[5];	// Initialized with 0 or false, depending on type
int[] arr = {1,2,3,4,5};
nums.length;
Arrays.sort(arr);
Arrays.fill(arr, 1);	// Useful when initializing
``` 

****


### Array lists (mutable!)
```
import java.util.ArrayList;
import java.util.List;
import java.util.Collections;

List <Integer> list = new ArrayListy<>();
list.add(num);		// Append num at the end
list.add(idx, num);	// Insert num at idx
list.set(idx, num);	// Replace position idx with num
list.size();
list.contains();
list.indexOf();
list.isEmpty();
Colelctions.sort(list);
```
****


###  (mutable, works like a dictionary)
```
import java.util.HasMap;

HashMap <String, Integer> map = new HashMap<>();
map.put("apple", 4);		// Create dict entry
map.get("apple");
map.getOrDefault("orange, 0")
map.containsKey();
map.containsValue();
map.keySet();			// Great of iterations
map.isEmpty();
```
****


###  (minHeap)

```
import java.util.PriorityQueue;

PriorityQueue <Integer> pq = new PriorityQueue<>();
PriorityQueue <Person> pq = new PriorityQueue<>((p1, p2) -> p1.age - p2.age) 
// negative if first element first

pq.add();
pq.peek(); 			// Check min element
pq.poll();			// Pop min
pq.size();			// Like a list
pq.remove();
pq.isEmpty();
pq.contains()
```