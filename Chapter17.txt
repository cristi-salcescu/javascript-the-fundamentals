const value = NaN;

if(Number.isNaN(value)){
  console.log('NaN');
}

//-----------------------

const value = 1.2;

if(Number.isInteger(value)){
  console.log('Integer');
} else {
  console.log('Not an Integer');
}

//-----------------------

const action = 'INCREMENT';

switch(action){
  case 'INCREMENT':
    console.log('INCREMENT');
  break;
  case 'DECREMENT':
    console.log('INCREMENT');
  break;
  default:
    console.log('DEFAULT');
}

//-----------------------

function doAction(action, value){
  switch(action){
    case 'INCREMENT':
      return value + 1
    case 'DECREMENT':
      return value - 1;
    default:
      return value;
  }
}

doAction('INCREMENT', 0);

//-----------------------

let sum = 0;
for(i = 1; i <= 3; i++){
  sum = sum + i;
}

console.log(sum);

//-----------------------

const flight = {
  no: 815,
  from: 'Sydney',
  to: 'Los Angeles'
}

for (key in flight) {
  console.log(key)
}

//-----------------------

const letters = ['A', 'B', 'C'];

for (index in letters) {
  console.log(index);
}

//-----------------------

for(const value of [1,2,3]){
  console.log(value);
}

//-----------------------

for(const value of new Set([1,2,3])){
  console.log(value);
}

//-----------------------

const map = new Map();
map.set(1, 'A');
map.set(2, 'B');
for(const value of map){
  console.log(value);
}

//-----------------------

for(const value of 'ABC'){
  console.log(value);
}

//-----------------------

let i = 3, sum = 0;

while(i){
  sum = sum + i;
  i = i - 1 ;
}

console.log(sum);

//-----------------------

const x = 1;
const y = 2;

//-----------------------

const x = 1
const y = 2

//-----------------------

const x = 1; const y = 2;

function getGameObject(){
  return 
    { name: 'Fornite'};
}

console.log(getGameObject());

//-----------------------

function getGameObject(){
  return;
    { name: 'Fornite'};
}

//-----------------------

function getGameObject(){
  return { 
    name: 'Fornite'
  };
}

console.log(getGameObject());

//-----------------------

return
1

//-----------------------

return 1;
return 'Hello'
return true;

throw 'There was an error';