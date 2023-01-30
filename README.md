/* # calc
percentage calculator source: https://github.com/Nooder/javascript-in-depth/blob/main/011-array-map/exercises/exercise-2.js

    1. Create an array called "prices" with the following values:
        [1.23, 19.99, 85.2, 32.87, 8, 5.2]
    2. Create a new array using map called "taxedPrices" that:
        - If the price is greater than 10, add 20% tax to it
        - Otherwise, do not add any tax
    3. Print out both arrays
*/

const prices = [1.23, 19.99, 85.2, 32.87, 8, 5.2];

const taxedPrices = prices.map((price) => {
  if (price > 10) {
    return price * 1.2;
  }
  return price;
});

console.log(prices);
console.log(taxedPrices);
