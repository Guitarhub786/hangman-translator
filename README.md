# hangman-translator
Tests your translation of a language through a hangman game

Inspired by playing with the following Algorithm.

function titleCase(str) {
  var strLower = str.toLowerCase();
  var input = "is this"
  
  input = input.toLowerCase();
  var words = strLower.split(input).join("");
  
  return words;
}

x = titleCase("Is this a pen?");
