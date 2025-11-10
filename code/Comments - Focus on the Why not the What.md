Adding comments on what the code does is just another form of duplication.
Comment and code have to be kept in sync when changes are made.
Instead focus on improving the structure of the code to communicate the What making the comment unnecessary.

```java
var items = Arrays.asList("three", "two", "one");
// iterate over all items in reverse order
for (int i = items.size(); i > 0; i--) {
    System.out.println(items.get(i-1));
}
```
Avoid comments explaining the What
```java
var items = Arrays.asList("three", "two", "one");
items.reversed().forEach(System.out::println);
```

Focus on comments explaining the Why
```java
var items = Arrays.asList("three", "two", "one");
// sorting in the external provider has a bug ES-327
// and returns the items in reversed order 
items.reversed().forEach(System.out::println);
```


[Don't write comments](https://www.youtube.com/watch?v=Bf7vDBBOBUA&t=11s)