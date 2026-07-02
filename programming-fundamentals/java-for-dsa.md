# Java for DSA

This chapter is a focused crash course on the Java features used repeatedly in DSA and coding interview preparation. Instead of covering the entire language, we will concentrate only on the parts that matter for solving problems efficiently in interviews.

## Common Imports

On LeetCode, most imports are available automatically. But when writing Java locally or in some interview platforms, you need to know what to import. Here are the imports that cover 95% of DSA problems:

```java
import java.util.*;        // ArrayList, HashMap, HashSet, Queue, PriorityQueue, etc.
import java.util.Arrays;   // Arrays.sort(), Arrays.fill(), Arrays.asList()
import java.util.Collections; // Collections.sort(), Collections.reverseOrder()
```

The wildcard `java.util.*` covers almost everything you need. In a real interview, you can write this at the top and move on. Do not waste time importing individual classes.
