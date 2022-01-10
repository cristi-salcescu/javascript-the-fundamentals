const currentDate = new Date();
console.log(currentDate);

//--------------------------

const date = new Date(2021, 0, 1, 10, 0);
console.log(date);

//--------------------------

const date = new Date(2021, 0);
console.log(date);

//--------------------------

const date = new Date(2022, 0, 1, 10, 15, 30);
date.getFullYear();
date.getMonth();
date.getDate();
date.getHours();
date.getMinutes();
date.getSeconds();

//--------------------------

const date = new Date(2022, 0, 1, 10, 15, 30);

date.toDateString();
date.toTimeString();

//--------------------------

const date = new Date('2021-01-15');
date.toDateString();

//--------------------------

const date = new Date("2021-01-15T10:10:00Z");
date.toDateString();
date.toTimeString();

//--------------------------

const date = new Date("2021-01-15T10:10:00Z");
date.toISOString();

//--------------------------

const timestamp = Date.now();

//--------------------------

const date = new Date(3_600_000);
date.getTime();

//--------------------------

const now = new Date();
now.getTime() === now.valueOf();
Number(now) === now.valueOf();

//--------------------------

const offset = new Date().getTimezoneOffset();

//--------------------------

const date = new Date(2021, 0, 15, 10, 10);
date.getTimezoneOffset();
date.getUTCHours();
date.getHours();

//--------------------------

const date = new Date(3_600_000);
date.getTimezoneOffset();
date.getUTCHours();
date.getHours();

//--------------------------

const date = new Date(2021, 0, 15, 10, 10);
date.toUTCString();

//--------------------------

const date = new Date(Date.UTC(2021, 0, 15, 10, 10));
date.getTimezoneOffset();
date.getUTCHours();
date.getHours();

//--------------------------

const date = new Date('2021-01-15T10:10:00.000Z');
date.getTimezoneOffset();
date.getUTCHours();
date.getHours();

//--------------------------

const date = new Date('2021-01-15T10:10:00.000');
date.getUTCHours();
date.getHours();
