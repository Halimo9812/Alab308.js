// The initial numbers that must be verified.
// const n1 = 10;
// const n2 = 15;
// const n3 = 20;
// const n4 = 5;


// Check one: add up to 50
// This is a fairly simple operation using
// arithmetic operators and a comparison.
// const isSum50 = (n1 + n2 + n3 + n4) == 50;
// console.log(n1 + n2 + n3 + n4) ==50;
// let sum= n1 + n2 + n3 + n4
// console.log(sum);
//50//
// Check two: at least two odd numbers
// Here, we use modulus to check if something is odd.
// Since % 2 is 0 if even and 1 if odd, we can use
// arithmetic to count the total number of odd numbers.
// const isTwoOdd = (n1 % 2) + (n2 % 2) + (n3 % 2) + (n4 % 2) >= 2;

// Check three: no number larger than 25
// This time, we use the OR operator to check
// if ANY of the numbers is larger than 25.
// const isOver25 = (n1 > 25 || n2 > 25 || n3 > 25 || n4 > 25);
// console.log(n1 > 25 || n2 > 25 || n3 > 25 || n4 > 25);


// Check four: all unique numbers
// This is long, and there are more efficient
// ways of handling it with other data structures
// that we will review later.
// const isUnique = n1 != n2 && n1 != n3 && n1 != n4 && n2 != n3 && n2 != n4 && n3 != n4;

// Here, we put the results into a single variable 
// for convenience. Note how we negate isOver25 using
// the ! operator. We could also have tested for 
// "isUnder25" as an alternative.
// const isValid = isSum50 && isTwoOdd && !isOver25 && isUnique;

// // Finally, log the results.
// console.log(isValid);

// Here's another example of how this COULD be done,
// but it SHOULD NOT be done this way. As programmers,
// we break things into small, manageable pieces so that
// they can be better understood, scaled, and maintained.
// const dontDoThis = ((n1 + n2 + n3 + n4) == 50) && 
//   ((n1 % 2) + (n2 % 2) + (n3 % 2) + (n4 % 2) >= 2) && 
//   !(n1 > 25 || n2 > 25 || n3 > 25 || n4 > 25) && 
//   (n1 != n2 && n1 != n3 && n1 != n4 && n2 != n3 && n2 != n4 && n3 != n4);

// 
// Check if all numbers are divisible by 5. Cache the result in a variable.
// const n1 = 10;
// const n2 = 15;
// const n3 = 20;
// const n4 = 5;

1. */....*
    return each number that is divisible by the divisor
   let num = prompt ("enter number");
   if ((num%5 === 0)){
    console.log("Number is divisible by 5");
   }
   else{
    console.log ("Not divisible by 5")
   }
 
2. Check if the first number is larger than the last. Cache the result in a variable.
 
let number =[10,20];
if(10>20)
{
console.log("true");
}
else{
    console.log("false")
}

 3. Subtract the first number from the second number.
Multiply the result by the third number.
Find the remainder of dividing the result by the fourth number

const n1 = 10;
const n2 = 15;
const n3 = 20;
const n4 = 5;
 
console.log(10-15) // -5
console.log((-5)*20)// 100
console.log((-100)%5)// -0

4. Change the way that isOver25 calculates so that we do not need to use the NOT operator (!) in other logic comparisons. Rename the variable as appropriate. 
Not sure about this one.//

Part 2: Practical Math
You are planning a cross-country road trip!
The distance of the trip, in total, is 1,500 miles.
Your car’s fuel efficiency is as follows:
At 55 miles per hour, you get 30 miles per gallon.
At 60 miles per hour, you get 28 miles per gallon.
At 75 miles per hour, you get 23 miles per gallon.
You have a fuel budget of $175.
The average cost of fuel is $3 per gallon.
const totalmiles = 1500;
const budget= 175;
const fuelPG = 3

 
 console.log(1500%175)*3
 console.log(1500%60)
 console.log(1500%75)

 let totalDistance = 1500
 let fuelprice = 3
 
 let totalPrice = fuelPrice * totalDistance 
 
 console.log(3*1500%55);
