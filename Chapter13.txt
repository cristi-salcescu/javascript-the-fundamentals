/[0-9]/

//--------------------------

new RegExp('[0-9]')

//--------------------------

const userInputText = "ab";
const startsWithRegExp = new RegExp(`^${userInputText}`);
startsWithRegExp.test("ab1");
startsWithRegExp.test("bc1");

//--------------------------

const onlyNumbersRegex = /^[0-9]+$/;
const hasOnlyNumbers = onlyNumbersRegex.test("12345");

//--------------------------

onlyNumbersRegex.test("12345A");

//--------------------------

const onlyNumbersRegex = /[0-9]+/;
const result = onlyNumbersRegex.exec("123 234");

//--------------------------

const regExp = /\w+\s/;

//--------------------------

const regExp = new RegExp('\\w+\\s');

//--------------------------

const pattern = /^\w+$/
pattern.test("Asterix");
pattern.test("Astérix");

//--------------------------

const pattern = /^[a-zA-Zé]+$/
pattern.test("Asterix");
pattern.test("Astérix");

//--------------------------

const pattern = /^\p{L}+$/u
pattern.test("Asterix");
pattern.test("Astérix");

//--------------------------

const numbersRegExp = new RegExp('[0-9]+');
const text = 'ABC123ABC567';
const matches = text.match(numbersRegExp);

//--------------------------

const numbersRegExp = new RegExp('[0-9]+', 'g');
const text = 'ABC123ABC567';
const matches = text.match(numbersRegExp);

//--------------------------

const numbersRegExp = new RegExp('[0-9]+', 'g');
const text = 'ABC123ABC567';
const matches = text.matchAll(numbersRegExp);
for(match of matches){
  console.log(match)
}

//--------------------------

const regExp = new RegExp('[0-9]');
const text = 'The acount number is 12345';
const formattedText = text.replace(regExp, '0');

//--------------------------

const regExp = new RegExp('[0-9]', 'g');
const text = 'The acount number is 12345';
const formattedText = text.replace(regExp, '0');

//--------------------------

const numbersRegExp = new RegExp('[0-9]+');
const text = 'ABC123ABC567';
text.search(numbersRegExp);

//--------------------------

const separatorsRegx = /[,\.\?\s]+/

const text = "Quanta fretta, ma dove corri, dove vai?"
const words = text.split(separatorsRegx);