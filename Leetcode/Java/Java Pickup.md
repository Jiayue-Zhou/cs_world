### Number
```java
Integer.MAX_VALUE;
Integer.MIN_VALUE;
```


### Array
```java
int[] array;
int size = array.length;
Arrays.fill(array, -1);
```

### HashMap
```java
HashMap<Integer, Boolean> map = new HashMap();
map.put(nums[i], true);
map.containsKey(nums[i));
for (Character c : map.keySet()) {}
map.put(nums[i], map.getOrDefault(nums[i], 0) + 1);
```

### String
```java
String cur = strs[i];
char[] chs = cur.toCharArray();
Arrays.sort(chs);
String temp = String.valueOf(chs);
```

### Queue
```java
PriorityQueue<Node> pq = new PriorityQueue<>((a, b) -> (b.freq - a.freq));
```
