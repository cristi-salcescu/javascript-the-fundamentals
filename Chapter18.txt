typeof 1
typeof ''
typeof {}
typeof function(){}

//-----------------

let x = 1;

typeof 1;

typeof x;

//-----------------

x = 1n;

typeof 1n;

typeof x;

//-----------------

const x = 1;
typeof x;

x = '';

//-----------------

const obj = { x: 1 };

typeof obj.x

//-----------------

'use strict';
const obj = Object.freeze({
  x: 1
});

typeof obj.x

obj.x = 2n;

//-----------------

const obj = { x: 1 };

typeof obj.x

//-----------------

'use strict';
const obj = Object.freeze({
  x: 1
});

typeof obj.x

obj.x = 2n;

//-----------------

function log(x){
  console.log(x);
}

log(1);
log('one');
log({value : 1});

//-----------------

const arr = [1, '2', '3'];

arr.map(Number);

arr.map(String);