# FizzBuzz
Sulution to FIZZBUZZ challenge


let num = 0;

while (num < 100) {
  num += 1;

  if (num % 3 === 0 && num % 5 === 0) {
    console.log("FIZZBUZZ");
  } else if (num % 3 === 0) {
    console.log("fizz");
  } else if (num % 5 === 0 && num % 3 !== 0) {
    console.log("buzz");
  } else {
    console.log(num);
  }
}



    
    


