1) **3** was printed because var has no block scope, so we are able to see the value getting printed.
2) **150** was printed because var has no block scope, so we are able to see the value getting printed.
3) **150** was printed because var has no block scope, so we are able to see the value getting printed.
4) It will return **[50, 100, 150]** because the function was initially given [100,200,300],.5 and when we run through the code, for each price in prices [100,200,300]
   we are multiplying the price at the given index with 1-discount (.5) rate. So once that price is calculated, its then pushed into the return array and we end up with
   **[50,100,150]**

5) Line 11 will return an Uncaught ReferenceError: i is not defined because unlike var, let is block scoped. So because we declare let i=0 inside the for
  loop, anything inside the loop/block stays in the loop/block causing the error.
6) Line 12 will return an Uncaught ReferenceError: discountedPrice is not defined because unlike var, let is block scoped. So because we declare discountedPrice inside the for
  loop, anything inside the loop/block stays in the loop/block causing the error.
7) Line 13 will return **150** because let finalPrice was declared at the start of the function and not inside the code code block. We are only updating finalPrice
  inside the code block. Because it is declared outside of the for loop/block, the values that are edited are saved therefore we see an output.
8) It will return **[50, 100, 150]** because the function was initially given [100,200,300],.5 and when we run through the code, for each price in prices [100,200,300]
   we are multiplying the price at the given index with 1-discount (.5) rate. So once that price is calculated, its then pushed into the return array and we end up with
   **[50,100,150]**. Additionally, we are able to see a value get returned because let discounted = [] was declared at the start of the function and outside
the any code blocks/for loops.

9) Line 11 will return Uncaught TypeError:Assignment to constant variable because we are trying to change a constant variable when we shouldn't be.
10)Line 12 will return Uncaught TypeError:Assignment to constant variable because we are trying to change a constant variable when we shouldn't be.
11)Line 13 will return Uncaught TypeError:Assignment to constant variable because we are trying to change a constant variable when we shouldn't be.
12)It will return an uncaught TypeError:Assignment to constant variable because we are trying to change a constant variable when we shouldn't be.

13A)**student.name**
  B)**student['Grad Year']
  C)**student.greeting()**
  D)**student['Favorite Teacher'].name**
  E)**student.courseLoad[0]**

14A)The output was **32** because '3' is defined as a string, so it is adding (concat) 2 to the end of the string. So we end up with 32 instead of 5.
  B)The output was **1** because we are not able to subtract strings so the '3' will be type casted into an integer, allowing for normal arithmetic to occur to get 3-2 = 1.
  C)The output was **3** because the null was converted into a 0 since we aren't able to add a integer with a null value.
  D)The output was **3null** because '3' is defined as a string and since we can't add a string with a null value, the null is typecasted into a string 'null'. And
    the two strings ends up getting added (concat) together to get 3null
  E)The output was **4** because we are not able to add a boolean with an integer, so the true is converted to an integer of 1 (because true is 1 and false is 0) and then
    it is added together to get 1+3 = 4.
  F)The out was **0** because we are not able to add together a boolean and a null value. So instead, they are both converted into integer value of 0+0=0.
  G)The output was **3undefined** because when undefined is converted into a string it just becomes undefined then its concatted with 3 to get 3undefined.
  H)The output was **NaN** because when undefined is type casted into a number it becomes NaN and '3' is also type casted into a number so it becomes 3-NaN and ends up as just Nan

15A)The output was **true** because the string '2' becomes an integer 2. And then it compares if 2 > 1 which is true.
  B)The output was **false** because in string comparison, it compares it by each char so it will compare 2 < 1 which is false.
  C)The output was **true** because the '2' is converted into an integer and then the == sign will check if they are equal to each other which they are.
  D)The output was **false** because it compares both the value and the type and the type is different between the two in this case so it returns false.
  E)The output was **false** because true becomes 1 when it is convert and 1 != 2 so it output false.
  F)The output was **true** because boolean(2) becomes true since 2 is a non-zero number and === will check both the type and that they are both true which they are both boolean and true.

16)The difference between == and === is that == checks for whether or not the values matches up but === checks if the values matches up and the type are the same without any conversion.
  
17)The output was **How are you?** because the first statement 2 == true is not true because the true is converted into a 1 and 2!=1. The second statement else if (2) works because
  it is checking whether or not it is true and because 2 is a non-zero value it returns true and goes into the statement to print out How are you?. And it doesn't enter the last else
  statement because it has already entered the else if statement.
  
18) See **part1-question18.js** file

19)The output was **[6,8,10]** because when the function modifyArray([1,2,3],doSomething is called, it will first create a newArr that is empty to return. Then for each element in the array it will call callback(array[i]) which will take that value and add 2 to it and return it. Then that returned value will go into function x which will multiply it by 2. Once muliplied by 2, it will then be pushed in the newArr and then continue the loop for the next element in the array. So, the initial 1 will be sent to callback and be added with 2 to get 3 and that 3 will be sent to function(3) to get 6 and that 6 will be pushed into the newArr to get [6]. Then it goes on for the next element until we reach the last element in the array.

20) See **part1-question20.js**

21)
