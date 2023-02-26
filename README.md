# Array-Questions
This repository contains list or array questions

1. Find largest and smallest element in array.

const arr=[1,2,3,-4,5,6];
 function getlargestNumber(arr)
{
  let max=Number.NEGATIVE_INFINITY;

for(let num of arr)
{
  if(num>max)
  max=num;
}
return max;
}

console.log(getlargestNumber(arr));



function getSmallestNumber(arr)
{
  let min=Number.POSITIVE_INFINITY;

for(let num of arr)
{
  if(num<min)
  min=num;
}
return min;
}
console.log(getSmallestNumber(arr));
