# Static Array Operations in Java

This project demonstrates how to perform basic operations on a static array in Java. It includes the following operations:

- **Insertion**: Adding elements to the array.
- **Deletion**: Removing elements from the array by index.
- **Traversal**: Displaying all the elements in the array.

## Features
1. **Insertion**: Inserts an element at the end of the array if there is space.
2. **Deletion**: Deletes an element at a specified index and shifts the remaining elements.
3. **Traversal**: Displays all the elements currently in the array.

## Requirements
- Java Development Kit (JDK) version 8 or above.

## How to Run
1. Clone or download the repository.
2. Compile the Java program:
    ```bash
    javac StaticArrayOperations.java
    ```
3. Run the program:
    ```bash
    java StaticArrayOperations
    ```

## Example
The program will execute the following steps:
1. Insert five elements: `10, 20, 30, 40, 50`.
2. Attempt to insert an additional element (will fail since the array is full).
3. Delete an element at index `2` (which will remove the element `30`).
4. Attempt to delete an element with an invalid index (will fail).
5. Display the array at various stages.

### Sample Output:
