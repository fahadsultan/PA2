
# Programming Assignment 2 

## Question 1. Singly Sorted Linked List

Implement a singly sorted linked list. The list should be sorted in ascending order. 

Fill in skeleton code in `LinkedList.java` located in `app/src/main/java/pa2/` folder. 

The code should be able to compile and run.

You can use the main method in `LinkedList.java` to test your initial implementation.

Please note that the list should be sorted at all times and the implementation of `traverse` must be recursive.

## Question 2. Write JUnit Test Cases

Write test cases for the singly sorted linked list from Question 1. 

Try to cover ALL cases for each method. Missing a test case scenario, even if your implementation is correct, will result in a deduction of points.

Fill in skeleton code in `LinkedListTest.java` located in `app/src/test/java/pa2/` folder

An example test case is given in the skeleton code: 

```java
@Test
void testRemove() {
    LinkedList list = new LinkedList();
    list.add(1);
    list.add(2);
    list.add(3);
    list.remove(2);
    assertEquals("1 3 ", list.traverse());
}
```

The test case above tests the add and remove methods. First 1, 2, 3 are added to the list. Then 2 is removed. Then traverse() is called to get the string representation of the list. The string representation should be "1 3 ".