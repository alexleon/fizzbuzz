A javascript fizz buzz one-liner. Took two tries to get it right. Forgot to log the output of the loop the first time.

var i=1; for (; i<=100; i++) console.log( i % 3 === 0 ? (i % 15 === 0 ? 'fizzbuzz' : 'fizz') : (i % 5 == 0 ? 'buzz' : i) );
