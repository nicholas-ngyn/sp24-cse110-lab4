1.) The bug was that the first number and the second number was fetched as a string so when we calculated the sum, it concatenated the 2 strings together rather than added them as integers.

2.) I would fix this bug by parsing the num1 and num2 which are strings into integers before adding in result.
