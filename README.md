1.Задание 
console.log("Hello, Word");
2.Задание
console.log('You know nothing, Jon Snow!'); // For Lannisters!
3.Задание
console.log('Robert');
console.log('Stannis'); 
console.log('Renly');
4.
console.log('9780262531962');
5.
console.log("What Is Dead May Never Die");
6.
console.log(81 / 9);
7.
console.log(6 - -81);
8.
console.log(3 ** 5)
console.log(-8 / -4)
9.
console.log(((8 / 2) + 5) - (-3 / 2))
10.
console.log(70 * ( 3 + 4 ) / ( 8 + 2 ));
11.
console.log(0.39*0.22)
12.
console.log(10 / 0); 
13.
console.log("NaN")
14.
console.log((5 ** 2) - (3 * 7))
15.
console.log("\"Khal Drogo's favorite word is \"athjahakar\"\"")
16.
console.log('- Did Joffrey agree?\n- He did. He also said "I love using \\n".')
17.
console.log('Winter ' + 'came ' + 'for ' + 'the ' + 'House ' + 'of ' + 'Frey.')
18.
console.log(String.fromCharCode(126));
console.log(String.fromCharCode(94));
console.log(String.fromCharCode(37));
19.
let motto = 'What Is Dead May Never Die!';
console.log(motto);
20.
let name = 'Brienna';

// BEGIN
name = 'anneirB';
// END

console.log(name);
21.
/* eslint prefer-const: 0 */

// BEGIN
let myBrothersCount = 2;
console.log(myBrothersCount);
// END
22.
/* eslint prefer-const: 0 */

let family = 'Targaryen';

// BEGIN
let pet = 'Dragon';
// END

console.log(family);
console.log('and');
console.log(pet);
23.
/* eslint prefer-const: 0 */

let eurosCount = 100;

// BEGIN
let dollarsPerEuro = 1.25;
let yuansPerDollar = 6.91;

let dollarsCount = eurosCount * dollarsPerEuro;
console.log(dollarsCount);
let yuansCount = dollarsCount * yuansPerDollar;
console.log(yuansCount);
// END
24.
/* eslint prefer-const: 0, prefer-template: 0 */

let info = "We couldn't verify your mother's maiden name.";
let intro = 'Here is important information about your account security.';

let firstName = 'Joffrey';
let greeting = 'Hello';

// BEGIN (write your solution here)
console.log(greeting + ', ' + firstName + '!');
console.log(intro + '\n' + info);
// END
25.
 /* eslint prefer-const: 0 */

// BEGIN
let firstNumber = 11;
let secondNumber = -100;

console.log(firstNumber * secondNumber);
// END
26.
/* eslint prefer-const: 0, prefer-template: 0 */

let king = 'King Balon the 6th';
console.log(king + ' has ' + (6 * 17) + ' rooms.');
// BEGIN (write your solution here)

// END
27.
const pi = "army"
console.log("the white walkers");
28.
const stark = 'Arya';

// BEGIN (write your solution here)
const firstName = 'Arya';
const greeting = 'Do you want to eat';

console.log(greeting + ', ' + firstName + '?');
// END
29.
const name = 'Na\nharis';

// BEGIN
console.log(name[7]);
// END
30.
console.log(-0.304);
31.
let name;
console.log(name);
32.
const one = 'Naharis';
const two = 'Mormont';
const three = 'Sand';

// BEGIN (write your solution here)
console.log(`${one[2]}${two[1]}${three[3]}${two[4]}${two[2]}`)
// END
33.
console.log('7' - (-8 - -2));
34.
import { length } from 'hexlet-basics/string';

const company1 = 'Apple';
const company2 = 'Samsung';

// BEGIN
const company1Length = length(company1);
const company2Length = length(company2);

console.log(company1Length + company2Length);
// END
35.
const soldiersCount = -2309;

// BEGIN
console.log(Math.abs(soldiersCount));
// END
36.
const number = 923.2238;

// BEGIN
console.log(Math.ceil(number));
// END
37.
import { round } from 'hexlet-basics/math';

const number = 10.1234;

// BEGIN
console.log(round(number, 2));
// END
38.
import { length } from 'hexlet-basics/string';

const text = 'Never forget what you are, for surely the world will not';

// BEGIN
const result = `First: ${text[0]}\nLast: ${text[length(text) - 1]}`;
console.log(result);
// END
39.
console.log(Math.min(3, -3, 10, 22, 0));
40.
// BEGIN (write your solution here)
console.log(Math.ceil(10));
// END
41.
const motto = 'Family, Duty, Honor';

// BEGIN (write your solution here)
console.log(typeof motto); 
// END
42.
const text = 'a mind needs books as a sword needs a whetstone, if it is to keep its edge.';

// BEGIN (write your solution here)
const name = 'Robb';
const len = 'a mind needs books as a sword needs a whetstone, if it is to keep its edge.'.length;
console.log(len);
// END
43.
const text = 'a MIND needs Books as a Sword needS a WHETSTONE, if it is to keep its edge.';

// BEGIN (write your solution here)
console.log('a MIND needs Books as a Sword needS a WHETSTONE, if it is to keep its edge.'.toLowerCase());
// END
44.
let firstName = '  Grigor   \n';

// BEGIN (write your solution here)
console.log(firstName);
// END
45.
const text = 'Never forget what you are, for surely the world will not';

// BEGIN
console.log(`First: ${text[0]}\nLast: ${text[text.length - 1]}`);
// END
46.
/* eslint no-tabs: 0 */

const text = 'When \t\n you play a \t\n game of thrones you win or you die.';

// BEGIN (write your solution here)
 console.log(text.slice(5, 15).trim().length)
// END
47.
// BEGIN
const printMotto = () => {
  console.log('Winter is coming');
};
// END

// exports are studied on Hexlet
export default printMotto;
48.
// BEGIN
const sayHurrayThreeTimes = () => {
  const word = 'hurray!';
  return `${word} ${word} ${word}`;
};
// END

export default sayHurrayThreeTimes;
49.
const truncate = (text, length) => {
  // BEGIN
  const result = `${text.slice(0, length)}...`;
  return result;
  // END
};

export default truncate;
50.
// BEGIN
const getHiddenCard = (cardNumber, starsCount = 4) => {
  const visibleDigitsLine = cardNumber.slice(12);
  return `${'*'.repeat(starsCount)}${visibleDigitsLine}`;
};
// END

export default getHiddenCard;
51.
// BEGIN
const capitalize = (text) => `${text[0].toUpperCase()}${text.slice(1)}`;
// END

export default capitalize;
52.
// BEGIN
const isPensioner = (age) => age >= 60;
// END

export default isPensioner;
53.
// BEGIN
const isMister = (greeting) => greeting === 'Mister';
// END

export default isMister;
54.
// BEGIN
const isInternationalPhone = (phone) => phone[0] === '+';
// END

export default isInternationalPhone;
55.
// BEGIN
const isLeapYear = (year) => {
  const result = year % 400 === 0 || (year % 4 === 0 && year % 100 !== 0);
  return result;
};
// END

export default isLeapYear;
56.
// We wrote the reverse() function solely for our exercises
// It uses some techniques that we haven't covered in our lessons yet
const reverse = (s) => s.split('').reverse().join('');

// BEGIN
const isPalindrome = (word) => {
  const lowerWord = word.toLowerCase();
  return lowerWord === reverse(lowerWord);
};

const isNotPalindrome = (word) => !isPalindrome(word);
// END

export default isNotPalindrome;
57.
// BEGIN
const getLetter = (text, position) => text[position - 1] || '';
// END

export default getLetter;
58.
// BEGIN
const guessNumber = (guess) => {
  if (guess === 42) {
    return 'You win!';
  }

  return 'Try again!';
};
// END

export default guessNumber;
59.
// BEGIN
const normalizeUrl = (site) => {
  let normalizedUrl;

  if (site.startsWith('https://')) {
    normalizedUrl = site;
  } else {
    normalizedUrl = `https://${site}`;
  }

  return normalizedUrl;
};
// END

export default normalizeUrl;
60.
// BEGIN
const whoIsThisHouseToStarks = (houseName) => {
  let status;

  if (houseName === 'Karstark' || houseName === 'Tally') {
    status = 'friend';
  } else if (houseName === 'Lannister' || houseName === 'Frey') {
    status = 'enemy';
  } else {
    status = 'neutral';
  }

  return status;
};
// END

export default whoIsThisHouseToStarks;
61.
import { reverse } from '../../../src/hexlet/string.js';

// BEGIN
const convertText = (text) => {
  if (text === '') {
    return '';
  }

  const reversable = text[0] !== text[0].toUpperCase();
  return reversable ? reverse(text) : text;
};
// END

export default convertText;
62.
// BEGIN
const getNumberExplanation = (number) => {
  switch (number) {
    case 666:
      return 'devil number';
    case 7:
      return 'prime number';
    case 42:
      return 'answer for everything';
    default:
      return 'just a number';
  }
};
// END

export default getNumberExplanation;
63.
// @ts-check
/* eslint operator-assignment: 0 */

const printNumbers = (initialNumber) => {
  // BEGIN
  let i = initialNumber;
  while (i >= 1) {
    console.log(i);
    i = i - 1;
  }
  console.log('finished!');
  // END
};

export default printNumbers;
64.
/* eslint operator-assignment: 0 */

// BEGIN
const multiplyNumbersFromRange = (start, finish) => {
  let i = start;
  let result = 1;

  while (i <= finish) {
    result = result * i;
    i = i + 1;
  }

  return result;
};
// END

export default multiplyNumbersFromRange;
65.
/* eslint operator-assignment: 0 */

// BEGIN
const joinNumbersFromRange = (start, finish) => {
  let i = start;
  let result = '';

  while (i <= finish) {
    result = `${result}${i}`;
    i = i + 1;
  }

  return result;
};
// END

export default joinNumbersFromRange;
66.
/* eslint operator-assignment: 0 */

// BEGIN
const printReversedWordBySymbol = (word) => {
  let i = word.length - 1;
  while (i >= 0) {
    console.log(word[i]);
    i = i - 1;
  }
};
// END

export default printReversedWordBySymbol;
67.
/* eslint operator-assignment: 0 */

// BEGIN
const countChars = (str, char) => {
  let i = 0;
  let count = 0;
  while (i < str.length) {
    if (str[i].toLowerCase() === char.toLowerCase()) {
      count = count + 1;
    }
    i = i + 1;
  }

  return count;
};
// END

export default countChars;
68.
/* eslint operator-assignment: 0 */

// BEGIN
const even = (str) => {
  let i = 0;
  let result = '';
  while (i < str.length) {
    if (i % 2 !== 0) {
      result = `${result}${str[i]}`;
    }
    i = i + 1;
  }

  return result;
};

// END

export default even;
69.
// BEGIN
const filterString = (str, char) => {
  let i = 0;
  let result = '';
  while (i < str.length) {
    const currentChar = str[i];
    if (currentChar !== char) {
      result = `${result}${currentChar}`;
    }
    i += 1;
  }

  return result;
};
// END

export default filterString;
70.
// BEGIN
const makeItFunny = (str, n) => {
  let i = 0;
  let result = '';
  while (i < str.length) {
    const current = str[i];
    if ((i + 1) % n === 0) {
      result = `${result}${current.toUpperCase()}`;
    } else {
      result = `${result}${current}`;
    }
    i++;
  }

  return result;
};
// END

export default makeItFunny;
71.
// BEGIN
const hasChar = (str, char) => {
  let i = 0;
  while (i < str.length) {
    if (str[i] === char) {
      return true;
    }

    i += 1;
  }

  return false;
};
// END

export default hasChar;
72.// BEGIN
const encrypt = (str) => {
  let result = '';
  for (let i = 0; i < str.length; i += 2) {
    const nextSymbol = str[i + 1] || '';
    result = `${result}${nextSymbol}${str[i]}`;
  }

  return result;
};
// END

export default encrypt;
