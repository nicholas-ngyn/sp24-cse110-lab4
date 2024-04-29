1.) The console will output 3 as that is what i incremented to and it can output i since i was declared a var variable.

2.) The console will output 150 because the for loop keeps on changing discountedPrice and the last element of prices is 300 so that will also be the last element discountedPrice will process with the discount and get set to.

3.) The console will output 150 because the for loop keeps on changing finalPrice and the last element of prices is 300 so discountedPrice will be 150 after its operations and finalPrice will take the 150 and do its operations which in the end results in 150 and that is the last time it is set.

4.) [50, 100, 150] because this function takes each price in the input array (prices) and multiplies it by (1 - discount) to apply the discount and the result will be rounded using Math.round(discountedPrice * 100) / 100. The rounded discounted price is then added to the discounted array.

5.) Causes an error because the let keyword on i binds it to the block scope of the for loop therefore attempting to console.log it causes an error since it is outside the block.

6,) Causes an error because the let keyword on discountedPrice binds it to the block scope of the for loop therefore attempting to console.log it causes an error since it is outside the block.

7.) The console outputs 150 and it is allowed to do this because the finalPrice variable was declared within the same block scope as the console.log.

8.) [50, 100, 150] because this function takes each price in the input array (prices) and multiplies it by (1 - discount) to apply the discount and the result will be rounded using Math.round(discountedPrice * 100) / 100. The rounded discounted price is then added to the discounted array. This doesn't change between changing variables from var to let because the code layout enables both var types to have the same effect on discounted.

9.) Causes an error because the let keyword on i binds it to the block scope of the for loop therefore attempting to console.log it causes an error since it is outside the block.

10.) The console outputs 3 because length is a const type and we set it to prices.length which is 3 since there are 3 elements in the array.

11.) [50, 100, 150] because this code iterates over each element in the prices array using a for loop and it calculates the discounted price for each element and then pushes it into the discounted array. After the loop finishes, it logs the discounted array to the console and returns it.

12.A) student.name

12.B) student['Grade Year']

12.C) student.greeting()

12.D) student['Favorite Teacher'].name

12.E) student.courseLoad[0]

13.A) '32' because it converts 2 into a string and then concatenates it with the string '3'. This is because the + operation can behave as a concatenation operator or an addition operator and in this case, it was a concatenation.

13.B) 1 because the subtraction operation converts '3' to a number and then performs the subtraction of 3 - 2 which equals 1.

13.C) 3 because it treats null as 0 when + operator behaves as an addition therefore 3 + 0 = 3.

13.D) '3null' because the + operator is treated as a concatenation operator here therefore it converts null into the string 'null' and concatenates it to the string 3.

13.E) 4 because true maps to 1 so 1 + 3 = 4

13.F) 0 because false is mapped to 0 and null is mapped to 0 therefore 0 + 0 = 0.

13.G) '3undefined' because it converts undefined to a string and concatenates with the string '3'.

13.H) NaN because it will convert 3 to a number and undefined to a number but undefined cannot be converted to a number so it returns NaN to indicate that the result is not a valid number.

14.A) True because it converts '2' to a number since > expects numeric operands therefore it compares 2 > 1 which is true.

14.B) False because comparing 2 strings with < operator causes a comparison between the 2 strings by their unicode values in which the first characters '2' and '1' are compared but '2' comes after '1' so '2' is greater therefore it returns false.

14.C) True because == converts one of the operands to match the type of the other operand in which it converts '2' to 2 and compares 2 == 2 which is true.

14.D) False because the === operator checks both the value and the type of the operands and in this case, one is a string and one is an integer so it returns false.

14.E) False because true maps to 1 therefore it compares if 1 == 2 which is false.

14.F) True because Boolean(2) automatically evaluates to true therefore we get true === true which is true since both are the same type and value.

15.) The difference between == and === is that == performs type coercion and checks for equality after conversion, while === strictly compares both the value and the type of the operands without performing type coercion.

17.) [2, 4, 6] because the array [1, 2, 3] is passed as the first argument to modifyArray and the second argument is the doSomething function, which pretty much multiplies its input by 2. So inside modifyArray, each element of the array [1, 2, 3] is passed through the doSomething function which results in the modified values [2, 4, 6] and these modified values are then pushed into a new array newArr.

19.) 

    1
    4
    3
    2
