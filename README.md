# whale-talk
Codecademy Whale Talk JavaScript Project

     let input = 'turpentine and turtles';
const vowels = ['a', 'e', 'i', 'o', 'u'];
let resultArray = [];
for (let inputIndex = 0; inputIndex < input.length; inputIndex++){
  for (let vowel = 0; vowel < vowels.length; vowel++){
  if (input[inputIndex] === vowels[vowel]){
      if (inputIndex[inputIndex] === 'e'){
  resultArray.push('ee');
} else if (inputIndex[inputIndex] === 'u'){
  resultArray.push('uu');
} else {
      resultArray.push(input[inputIndex]);
      } 
    }
  }
}
console.log(resultArray.join('').toUpperCase());

