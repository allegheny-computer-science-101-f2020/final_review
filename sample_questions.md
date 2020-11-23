# CMPSC 101 Final Sample Questions

Here are examples of the kinds of questions that might be asked. This is not intended to be a sample exam, it does not include all topics covered on the exam, instead the goal here is to familiarize individuals with the format of the exam. 

1. Give an example of a reference data type (i.e., an `Object`), explaining its purpose and showing how to construct it by calling one of its constructors.

2. Explain the concept of method overriding with an example.

3. What is the output of the following method when it is called with the input of `-1`?

```
public static int factorial(int n) {
   if(n < 0)
      throw new IllegalArgumentException();
   if (n == 0)
      return 1;
   else
      return n * factorial(n-1); 
}
```

Put "X" inside brackets [ ]  of the correct answer.

    - [ ] Exception thrown
    - [ ] 1
    - [ ] -1
    - [ ] 0

4. State two key differences between an iterative and recursive data processing technique.

5. Given the snippet program below, answer the following questions.

``` 
public class ArraySum {
    public static double sum(double[] data) {
      double total = 0;
      for (int j = 0; j < data.length; j++) {
         total += data[j];
      }
      return total;
   } 
}
```

(a) What is the meaning of the following code segment?

`total += data[j];`

(b) What is the worst-case time complexity of the `sum(double[] data)` method? Please use the method’s source code and the big-Oh notation to explain your response.

6. [True or False.] Elements in an array are located in contiguous memory location. 

Put "X" inside brackets [ ]  of the correct answer.

    - [ ] True.
    - [ ] False.
    
7. A two-dimensional array should always have the same number of rows and columns.

Put "X" inside brackets [ ]  of the correct answer.

    - [ ] True.
    - [ ] False.

8. A software engineer must assess the trade-offs associated with using different data structures inside of a Java program. Answer the following questions by comparing the following data structures in these pairs, highlighting the strengths and weaknesses of each data structure.

(a) `Array` compared to `ArrayList`

(b) `ArrayList` compared to `SinglyLinkedList`

9. Furnish a one to three sentence explanation of the following code segments:

(a) `private Node<E> header;`

(b) `int[][] data = new int[12][20];`

10. What are the contents of `backup` array after the following lines of code are executed?

```
int[] data = {2, 3, 5, 7, 11, 13, 17, 21}; 
int[] backup;
backup = data.clone();
```