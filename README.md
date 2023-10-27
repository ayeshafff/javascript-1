# javascript-1
Take a sentence as an input and reverse every word in that sentence. a. Example - This is a sunny day > shiT si a ynnus yad.

#code


function reverseWords(sentence) {
  return sentence.split(" ").map(word => word.split("").reverse().join("")).join(" ");
}

const sentence = prompt("Enter a sentence: ");
const reversed = reverseWords(sentence);
console.log(reversed);
