tags:: design

- Where and how a learner studies something should also be a learning objective.  Do your best to align your learner's study workflows with realistic workflows (whatever that means in your setting), this can help learners avoid challenges with [[Skill Transfer]] and save time in the long run.
  id:: 6400a99f-72f7-43a6-9366-df9772399d0c
- ## Case Study: Reverse a String
	- > Reverse the provided string. You may need to turn the string into an array before you can reverse it. Your result must be a string.
	- demonstrating how the same coding challenge in different learning environments gives a very different experience and learning outcomes.
	- To get the feel, take a look through the examples below.  Each example has the exact same challenge, test cases, explanation and resources, but they are not completely interchangeable:
		- how does each environment change your interaction with the code, is one easier or harder?
		- what implicit & explicit skills are practiced or avoided in each environment?
		- which version will most directly prepare students for developing real projects in a professional development environment?
		- which format is easier for making more exercises?  does the amount of effort relate to better student learning?
	- **[FreeCodeCamp](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-algorithm-scripting/reverse-a-string)**
	- **[JS Tutor](http://www.pythontutor.com/live.html#code=function%20reverseString%28str%29%20%7B%0A%20%20return%20str%3B%0A%7D%0A%0Avar%20olleh_type%20%3D%20reverseString%28%22hello%22%29%3B%0Avar%20olleh_value%20%3D%20reverseString%28%22hello%22%29%3B%0Avar%20ydwoH%20%3D%20reverseString%28%22Howdy%22%29%3B%0Avar%20htraE_morf_sgniteerG%20%3D%20reverseString%28'Greetings%20from%20Earth'%29%3B%0A%0A%0A//%20---%20tests%20---%0Aconsole.assert%28typeof%20olleh_type%20%3D%3D%3D%20'string',%20%0A%20%20%20%20'reverseString%28%22hello%22%29%20should%20return%20a%20string'%29%3B%0A%0Aconsole.assert%28olleh_value%20%3D%3D%3D%20'olleh',%20%20%0A%20%20%20%20'reverseString%28%22hello%22%29%20should%20become%20%22olleh%22.'%29%3B%0A%0Aconsole.assert%28ydwoH%20%3D%3D%3D%20'ydwoH',%20%0A%20%20%20%20'reverseString%28%22Howdy%22%29%20should%20become%20%22ydwoH%22.'%29%3B%0A%0Aconsole.assert%28htraE_morf_sgniteerG%20%3D%3D%3D%20'Greetings%20from%20Earth',%20%0A%20%20%20%20'reverseString%28%22Greetings%20from%20Earth%22%29%20should%20become%20%22htraE%20morf%20sgniteerG%22.'%29%3B&cumulative=false&curInstr=14&heapPrimitives=nevernest&mode=display&origin=opt-live.js&py=js&rawInputLstJSON=%5B%5D&textReferences=false)**
	- **[CodePen](https://codepen.io/colevanderswands/pen/NodZaW)**
	- **[Repl.it (browser)](https://repl.it/@colevandersWands/reverse-a-string-es6)**
	- **[Repl.it (node)](https://repl.it/@colevandersWands/reverse-a-string-node)**
	- **[Glitch](https://glitch.com/edit/#!/remix/reverse-a-string)**
	- In your browser's console:
		- ```js
		   /* 
		    Reverse the provided string.  
		    You may need to turn the string into an array before you can reverse it.  
		    Your result must be a string.  
		  */
		  
		  function reverseString(str) {
		    return str;
		  }
		  
		  /*
		      stuck?
		      1. read search ask: 
		        https://www.freecodecamp.org/forum/t/how-to-get-help-when-you-are-stuck/19514
		      2. get a hint:
		        https://guide.freecodecamp.org/certifications/javascript-algorithms-and-data-structures/basic-algorithm-scripting/reverse-a-string/
		      3. ask a question on the forum:
		        https://www.freecodecamp.org/forum/categories
		    */
		  
		  
		  // --- tests ---
		  var olleh_type = reverseString("hello");
		  if ( !( typeof olleh_type === 'string' )) {
		    console.log('reverseString("hello") should return a string');
		  };
		  
		  var olleh_value = reverseString("hello");
		  if ( !( olleh_value === 'olleh' )) {
		    console.log('reverseString("hello") should become "olleh".');
		  };
		  
		  var ydwoH = reverseString("Howdy");
		  if ( !( ydwoH === 'ydwoH' )) {
		    console.log('reverseString("Howdy") should become "ydwoH".');
		  };
		  
		  var htraE_morf_sgniteerG = reverseString('Greetings from Earth');
		  if ( !( htraE_morf_sgniteerG === 'htraE morf sgniteerG' )) {
		    console.log('reverseString("Greetings from Earth") should become "htraE morf sgniteerG".')
		  };
		  ```
		-