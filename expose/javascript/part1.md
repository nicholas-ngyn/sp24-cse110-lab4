1.) values added: 20

2.) final result: 20

3.) values added: 20

4.) Returns an error because the let keyword only allows result to be accessed within its block scope and line 13 calls result but is out of result's block.

5.) Returns an error because it was trying to reassign a const variable.

6.) Returns an error because the const keyword only allows result to be accessed within its block scope and line 13 calls result but is out of result's block.

# Part 2:
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




