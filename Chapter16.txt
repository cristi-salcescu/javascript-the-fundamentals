var name;

console.log(name);

//------------------------

{
   var name = 'Jon Snow';
}

console.log(name);

//------------------------

console.log(name);
var name = 'Jon Snow';

//------------------------

var name = 'Eddard Stark'
{
   var name = 'Robb Stark';
}

console.log(name);

//------------------------

var name = 'Eddard Stark'
var name = 'Robb Stark';

console.log(name);

//------------------------

var name = 'Tywin Lannister';

function process(){
  var name = 'Tyrion Lannister';
}

//------------------------

{
   let name = 'Jon Snow';
}

console.log(name);

//------------------------

let name = 'Eddard Stark'
{
   let name = 'Robb Stark';
}

console.log(name);

//------------------------

let name;

console.log(name);

//------------------------

console.log(name);

let name = 'Daenerys Targaryen';

//------------------------

let name = 'Cersei Lannister';
let name = 'Cersei Baratheon';

//------------------------

const name = 'A Game of Thrones';
name = 'A Clash of Kings';

//------------------------

const name = 'Eddard Stark'
{
   const name = 'Robb Stark';
}

console.log(name);

//------------------------

const castle = 'Casterly Rock';

//------------------------

const castle = { name : 'Casterly Rock' };

castle.name = 'Winterfell';
console.log(castle);

//------------------------

const castle = Object.freeze({ 
  name : 'Casterly Rock' 
  });
  
castle.name = 'Winterfell';

//------------------------

const arr = [1, 2, 3];

const [a, b, c] = arr;

console.log(a);
console.log(b);
console.log(c);

//------------------------

const arr = [1, 2, 3];
let a, b, c;
[a, b, c] = [1, 2, 3];

console.log(a);
console.log(b);
console.log(c);

//------------------------

const arr = [1, 2, 3];
const [a, b] = arr;

//------------------------

const [a, b, c] = [1, 2];
console.log(a);
console.log(b);
console.log(c);

//------------------------

const [a, b, c = 0] = [1, 2]
console.log(a);
console.log(b);
console.log(c);

//------------------------

const [a, ...newArr] = [1, 2, 3];

console.log(a);
console.log(newArr);

//------------------------

function getValues(){
  const v1 = 1;
  const v2 = 2;
  return [v1, v2];
}

const [a, b] = getValues();
console.log(a);
console.log(b);

//------------------------

const point = { x: 1, y: 2};

const {x, y} = point;

console.log(x);
console.log(y);

//------------------------

const { x } = point;

console.log(x);

//------------------------

const { x, z } = point;

console.log(x);
console.log(z);

//------------------------

const { x, z = 0 } = point;

console.log(x);
console.log(z);

//------------------------

const point = { x: 1, y: 2};
const { x : xAxis, y: yAxis } = point;

console.log(xAxis);
console.log(yAxis);

//------------------------

function getValues(){
  const v1 = 1;
  const v2 = 2;
  return [v1, v2];
}

const [a, b] = getValues();
console.log(a);
console.log(b);

//------------------------

const point = { x: 1, y: 2};

const {x, y} = point;

console.log(x);
console.log(y);

//------------------------

const { x } = point;

console.log(x); //1

//------------------------

const { x, z } = point;

console.log(x);
console.log(z);

//------------------------

const { x, z = 0 } = point;

console.log(x);
console.log(z);

//------------------------

const point = { x: 1, y: 2};
const { x : xAxis, y: yAxis } = point;

console.log(xAxis);
console.log(yAxis);