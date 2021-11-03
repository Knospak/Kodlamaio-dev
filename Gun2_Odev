// Soru 1

function findPrime(...numbers){
  numbers.map(number=>{
      let prime=findPrimefunc(number);
      console.log(prime ?  `${number} sayısı asaldır.` : `${number} sayısı asal değildir.`);
  });
}

function findPrimefunc(number){
  let prime = true;
  for(let i=2; i < number; i++){
      if(number % i == 0)
          prime = false;
  }
  return prime;
}

// Soru 2

function FriendNumber(x,y){
  let a = 0 
  let b = 0;
  for(let i=0; i < x; i++){
      if(x % i == 0)
         a += i;
  }
  for(let i=0; i < y; i++){
      if(y % i==0)
         b +=i ;
  }
  let Friends = (a == y && b == x);
  console.log(Friends ? `${x} ve ${y} sayıları arkadaş sayıdır.` : `${x} ve ${y} sayıları arkadaş sayı değildir.`);
}

//Soru 3

function AllPerfect(){
  let perfectNum=[];
  for(let i=1; i<=1000; i++){
      let a = [i];
      for(let j = 1; j < i; j++){
          if(i % j == 0)
              a.push(j);
      }
      if(a.reduce((a,b) => a+b,0) / 2 == i)
          perfectNum.push(i);
  }
  console.log(`1000'e kadarki mükemmel sayılar : ${perfectNum}`);
}

// Soru 4

function AllPrime(){
  let primes = [];
  for(let i = 1; i <=1000; i++){
      if(findPrimefunc(i))
         primes.push(i);
  }
  console.log(`1000'e kadarki asal sayılar : ${primes}`);
}
