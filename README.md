# Build-the-Largest-Number-Finder---Build-the-Largest-Number-Finder-freeCodeCamp
/*using arrays to create a new array consinsting of only the largest value from the main arrays*/
/*CODE STARTS HERE*/
function largestOfAll(arrays){
return arrays.map(array=>array.reduce((pln,cln)=>(cln>pln)? cln:pln))
}
console.log(largestOfAll([[4, 9, 1, 3], [13, 35, 18, 26], [32, 35, 97, 39], [1000000, 1001, 857, 1]]))

   
 console.log(largestOfAll([[17, 23, 25, 12], [25, 7, 34, 48], [4, -10, 18, 21], [-72, -3, -17, -10]]))
