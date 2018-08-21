var arr = [
	"apple",
  "banana",
  "avovado",
  "strawberry"
];

var x = Math.floor(Math.random() * arr.length);

window.alert(arr[x]);

//create an array of the adjectives or adverbs
var adj = [
	"tall",
  "pretty",
  "good looking",
  "bad looking",
  "short"
];
//Ask the person for his or her name
var name = prompt(" what is your name");

//Generate a random number

var x = Math.floor(Math.random() * adj.length);

window.alert(name + adj[x]);
//let the user know kind of person are. Froexample,
//username followed or preceded by the array item.
