---
title: Find and fix bugs by using PoE
---
 # Guidance

 Hi students,

 You need to use the Poe for finding the bugs and fix them.

 ## Step 1: Access to Poe

 - Login to [Poe](https://poe.com/)
 - Create an AI bot

 ## Step 2: Copy the below codes to your editor tool
 - Copy each code to your editor tool
 - Can use VSCode or online tool such as: [Online JavaScript Compiler (Editor)](https://www.programiz.com/javascript/online-compiler/)

 **Sample 1**
 ```javascript
 function checkEvenOrOdd(number) {
  if (number % 2 === 0) {
    return "Số " + number + " là số lẻ."; 
  } else {
    return "Số " + number + " là số chẵn.";
  }
}
// Sử dụng hàm để kiểm tra một số cụ thể
var number = parseInt(prompt("Nhập số cần kiểm tra: "));
console.log(checkEvenOrOdd(number));
 ```

 **Sample 2**
```javascript
 function isFibonacciNumber(number) {
  var a = 0;
  var b = 1;
  while (b <= number) {
    var temp = b;
    b = a + b;
    a = temp;
  }
  if (b === number) {
    return true;
  } else {
    return false;
  }
}
// Sử dụng hàm để kiểm tra một số cụ thể
var number = parseInt(prompt("Nhập số cần kiểm tra: "));
console.log(number + " là số Fibonacci: " + isFibonacciNumber(number));
 ```

 **Sample 3**
```javascript
function isPrime(number) {
  if (number <= 1) {
    return false;
  }
  for (var i = 2; i < Math.sqrt(number); i++) {
    if (number % i === 0) {
      return false;
    }
  }
  return true;
}
function findPrimesInRange(start, end) {
  var primes = [];
  for (var number = start; number <= end; number++) {
    if (isPrime(number)) {
      primes.push(number);
    }
  }
  return primes;
}
// Sử dụng hàm để tìm các số nguyên tố trong khoảng cụ thể
var start = parseInt(prompt("Nhập giá trị bắt đầu của khoảng: "));
var end = parseInt(prompt("Nhập giá trị kết thúc của khoảng: "));
var primeNumbers = findPrimesInRange(start, end);
console.log("Các số nguyên tố trong khoảng từ " + start + " đến " + end + " là: " + primeNumbers);
 ```

 ## Step 3: Using Poe to find bugs
 - Finding bugs of the code by using [Poe](https://poe.com/)

 ## Step 4: Ask Poe to fix them
 - Asking [Poe](https://poe.com/) on tips for fixing bugs

 ## Step 5: Run the modified code
 - Modify the code based on suggestions from [Poe](https://poe.com/)
 - Run the modified code and make sure you have a correct output.