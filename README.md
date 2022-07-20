# DAY5
print odd numbers
let arr = [1,2,3,4,5,6,7,8,9,10,11,12]

let odds = arr. filter(n => n%2)

console. log(odds)

string tittle caps string

<script>
function titleCase(str) {
  str = str.toLowerCase().split(' ');
  for (var i = 0; i < str.length; i++) {
    str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1);
  }
  return str.join(' ');
}
document.write(titleCase("GUVI"));
</script>

sum of all number in array
console.log(
  [1, 2, 3, 4].reduce((a, b) => a + b, 0)
)
console.log(
  [].reduce((a, b) => a + b, 0)
)
prime number
function checkPrime(number) {
  if (number <= 1) {
    return false;
  } else {
    for (let i = 2; i < number; i++) {
      if (number % i == 0) {
        return false;
      }
    }
  }
  palindromes
  function checkPrime(number) {
  if (number <= 1) {
    return false;
  } else {
    for (let i = 2; i < number; i++) {
      if (number % i == 0) {
        return false;
      }
    }
  }
  remove dublicats array
  let chars = ['A', 'B', 'A', 'C', 'B'];

let uniqueChars = chars.filter((c, index) => {
    return chars.indexOf(c) === index;
});

console.log(uniqueChars);
arrow function:
print odd numberfunction
let num = [1,2,3,4,5,6,7,8,9,];

console.log('even numbers are');
for (var i = 1 ; i < 10 ; i += 2 ) {
   console.log(i);
}


console.log('odd numbers are ');
for (var i = 2 ; i < 10 ; i += 2 ) {
  console.log(i);
}
tittele caps string
function toTitleCase(str) {
  return str.replace(
    /\w\S*/g,
    function(txt) {
      return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
    }
  );
}
sum of all number 
sum = (a, b) => {
return(a+b)
x= sum(34,87)
log(x)
prime number
const newArray = [1, 3, 2, 5, 10];
const isPrime = num => {
  for (let i = 2; i < num; i++) {
    if (num % i === 0) return false;
  }
  return num !== 1;
};


const myPrimeArray = newArray.filter(element => isPrime(element));
console.log(myPrimeArray);
palindromes
var name = prompt("Enter Name: ");
const isPalindrome = name => {

  const midPoint = name.length / 2;

  for (let i = 0; i < midPoint && i < name.length; i++) {
    if (name[i] != name[name.length - 1 - i]) {
      console.log(" Not Palindrome");
    }
  }
  console.log("Palindrome");
}
