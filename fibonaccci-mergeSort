//loop method function fib(n) {
    let arr = [];
    for(let i=0; i < n; i++ ) {
        if (arr.length < 2) {
            arr.push(i)
        } else {
            arr.push(arr[arr.length - 1] + arr[arr.length - 2])
        }
    }
    return arr;
}

let oya = fib(8);

console.log(oya)


//recursive method

function fib(n) {
  if (n <= 0) return [];
  if (n === 1) return [0];
  if (n === 2) return [0, 1];

  const prev = fib(n - 1);
  return [...prev, prev[prev.length - 1] + prev[prev.length - 2]];
}



//mergesort algorithm

//first step merg data

function merge(left, right) {
let i = 0;
let j = 0;
let result = [];

while (i < left.length && j < rigth.lenght) {
 if ( left[i] < right[j] ) {
	result.push(left[i]);
	i++;
 } else {
	result.push(right[j]);
	j++;

 }
}

while(i < left.length) { result.push(left[i++])
while(j < right.length) { result.push(right[j++])

return [left,right] 

}




//then the mergesort function

function mergeSort(arr) {
//base case

   if (arr.length <= 1 ) {
	retun arr;
    }

   const mid = Math.floor(arr.length / 2);
   const right = mergeSort(arr.slice(0, mid));
   const left = mergeSort(arr.slice(mid);


   return merge(left, right)
 }
