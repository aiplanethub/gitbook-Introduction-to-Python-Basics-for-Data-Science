# Strings

### Sequence Types

* Sequences allow you to store multiple values in an **organized and efficient way**. 
* There are seven sequence types: strings, Unicode strings, lists, tuples, bytearrays, buffers, and xrange objects. 
* _Nothing to worry looking at this long list, you will get to know it gradually._

### Python Strings

* Strings are sequence of characters. 
* Let us see some examples of String: My name is Rahul, Rahul, Go home. All these are examples of String. 
* In Python, Strings are called str. 
* There is a specific way of defining String in Python – it is defined within single quote (‘) or double quotes (“) or even triple quotes (“‘). 

### Accessing String Elements

* Square brackets can be used to access elements of the string.
* **Remember that the first character has index 0.**
* Index refers to position of a character in a string. In python index number starts from 0.
* Example: \
  **`a = "Hello, World!"`**\
  **`print(a[1])`**
* ** Will give an output e. Can you understand why?**

![](https://lh5.googleusercontent.com/c1mE3QqOIu6tDGHVRxGW_vhmNgTywCuMij-ZzFBGrXrUxvI1PYMGeWGssS3n\_4PqTqcnnkx3oPCs2feWKRFWfMLFXLdu4HgxArUdXSXKr5Sndy5IR98bWNYg8hHPk1ZzzYDnCXR\_28U=s0)

* Hope you got the answer to the previous question now!

### String Slicing

* We can also call out a range of characters from the string using string slicing.
* Specify the start index and the end index, separated by a colon, to return a part of the string. Note that the character of the end index is not included.
* Suppose we want to print World from the string “Hello World”. We can do so as below:

![](https://lh5.googleusercontent.com/FQ_wXPLtEywN822BAg7TZrwUAjFvc3jjzPqi8q-3oHY1Myqzt_d\_8wUwy1qA0xX0OScYUa7Ga9NjRmrPXoSnabFDphZlnNbuyzbg6TlI7fzN9tDdZ8i5AClPRpZxIqokDSqchtMIS5s=s0)

### Negative Indexing

* If we have a long string and we want to pinpoint an item towards the end, we can also count backwards from the end of the string, starting at the index number -1
*   Printing ‘r’ from the string :\
    **`a = "Hello, World!"`**

    **`print(a[-4])`**
* Get the characters from position -5 to position -1, starting the count from the end of the string: \
  **`print(a[-5:-2])`**
* Will give an output :orl

### String Concatenation

* String concatenation means adding strings together.
* Use the + character to add a variable to another variable:
*   Example:

    ![](https://lh3.googleusercontent.com/QQiTc8tB8Vv-06Sk1czxk6Eu-glX9TCQkyWvjSRvu2Xq-clUSUh-4RCy7aypa6kyhnFvK8lhsiCE0nLRWF4CbIgULdCwBR13CY2kCRhoGZJVqqw2q-qc7ipb7AJRsRvElHxrCMVQU60=s0)****
* Another example:\
  **`x = "Python is "`**\
  **`y = "awesome"`**\
  **`z =  x + y`**\
  **`print(z)`**
* **Output: Python is awesome**

### String Concatenation: Add Space

* We can also add spaces between two strings

![](https://lh6.googleusercontent.com/RfPVFKHFAPvXS8jB9oQRSwTskU-j2JbaOiOMFmrhNWPRI55gqUGJCqrdWQHC07OFHmo7uy0C2XtzTi39rfs-qoQ0ezcWfb4HEKKY_K0zKDNySXq1jUJ_Tx5s5P96Llkyx5b3mCcvf2E=s0)

### String Length

* To get the length of a string, use the len( ) function.
*   Getting length of the string a :

    **`a = "Hello, World!"`**

    **`print(len(a))`**
* **Output: 13**

### **String Methods**

* Python has a set of built-in methods that you can use on strings.
* Must learn: Learn about important string methods from the below cheatsheet: [https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-strings/cheatsheet](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-strings/cheatsheet) 
* Tip: If you are unable to follow, run the code and make out the difference.
