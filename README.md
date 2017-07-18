# Homework2
for (let i = 1; i <= 100; i++) {
  if (i % 3 == 0) {
    console.log('Fizz');
  } else if (i % 5 == 0) {
    console.log('Buzz');
  } else if (i % 3 == 0 && i % 5 == 0) {
    console.log('FizzBuzz');
  } else {
    console.log(i);
  }
}





//Part 2
function getAverage (array) {
  let total = 0;
  let averagetotal = 0;
  let j = 0;
  for (let i = 0; i < array.length; i++) {
    j++;
    total += array[i];
  }
  averagetotal = total / j;
  return Math.floor(averagetotal);

}

console.log(getAverage([1, 2, 3, 4,4]));
