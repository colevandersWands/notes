tags:: narrative

- (... more story ...)
- Some principles behind Study Lenses:
	- "code is content" or "study code, not explanations":
	  1. teach learners how to study code
	  2. make it easy to study code effectively
	  3. write code intended for study
	  4. let learners construct their own understanding
	- Use source code and the raw material to generate exercises supporting a variety of [[Learning Objectives]] - [[as Code/Content]]. [[Block Model]], [[PRIMM]]
	- Content should be developed using skills & technologies covered in the course so a learner can own their own education
	- content should be developed using standards from the domain you are teaching to avoid platform lock and learning extranious syntax
	- Code is data: if an application is "just" data + interactions, then Study Lenses can be defined as: code + study techniques
	- [[Context is Content]], [[Means of Instruction]], [[Open Education]], [[Open Source]], [[PRIMM]], [[Explicitly Teach the Implicit]], [[Notional Machine]], [[Expertise Reversal Effect]], [[Skill Transfer]], [[Learner-Accessible OER]]
- Study Lenses is a concept, not a specific tool.  You could integrate study lenses into an existing [[Learning Environment]], develop them as IDE plugins for learners or professionals, or create mobile-friendly lenses for studying on the go.
	- developing Study Lenses in concept and implementation was a long winding design process.  New feedback or ideas would lead to changes/new feature -> changes led to new possibilities -> which led to new feedback -> ...
- currently, the most complete implementation of Study Lenses is [this one](https://github.com/colevandersWands/study-lenses).  It's designed for learning web development and is built around an express server; Open any folder of code in the terminal, enter `$ study`, and the folder's content will open in your browser ready to study.
	- [online study lenses demo](https://study-lenses-demo.onrender.com/?--defaults)
	- A Study Lenses video guide covering basic use and features: ![guide.mp4](../assets/guide_1677497948858_0.mp4)
	- See the "Hierarchy" below "Linked References" to explore more Study Lenses features
- Some constraints that let to s-l include:
	- teaching web dev in a short period: no luxury to choose a more "learnable" language, had to make JS as learnable as possible
	- ditto for learning environments.  there was no time in the course for the [[Skill Transfer]] from a "learning environment" to a "development environment".  the design challenge became how to add layers of learning environment _on top of_ the professional environment so skill transfer can happen naturally by removing one layer at a time.  configurable layers also helps accommodate the [[Expertise Reversal Effect]]
	- the T & C of web dev bootcamps aligned nicely ([[TPACK]]), making it easier for me to prototype since I didn't need to know two languages and environments:  one to teach and one to build prototyps
	- i wanted easy authorship content authorship using only web standards, not specialized or extra langauges
	- learners should be able to use the environment to explore any code they write or encounter
	- discussion, feedback and observation of learners & coaches using Study Lenses
- i wonder about [[Study Lenses]]
	- Does a [[PRISMM]] curriculum made of code, some small comments in english, and [[Study Lenses]] make programming more accessible to ESL learners?  they can then think, write, discuss, and find relevant tutorials in their own language while still focusing on the course's objectives.  anecdotally this is true.  #question
	  id:: 640b8af2-3406-4d12-a88b-468f3992b1a9
		- Reading or listening to lots of english is not easy for everyone. Depending on your goals, you may need to eventually use english with programming. But that doesn't mean it's helpful to combine both objectives (english & programming) at the beginning.
		- How does this relate to [[PRIMM]] or [[PRISMM]] ?
	- can [[Large Language Models]] and other code generators be combined with [[Study Lenses]] to generate tailored curricula? #question [[Codeschool in a Box: A Low-barrier Approach to Packaging Programming Curricula]]
	- how does study lenses compare to other things out there? and in which ways? #question
		- https://www.codespec.org/ ([paper](https://camps.aptaracorp.com/ACM_PMS/PMS/ACM/ICER2022V2/6/da576267-ed8d-11ec-a76e-16bb50361d1f/OUT/icer2022v2-6.pdf)): same challenge, different exercise type (pseudo -> parsons -> faded parsons -> fix bugs -> write code).  
		  id:: 641a5554-5ba6-4331-8dc6-ad12254e8d82
			- is codespec a [[Spiral Curriculum]]? #question
			  id:: 641b1ef8-5cf5-46ec-93ab-923b7fb99ff1
		- https://futurecoder.io/: several run options available (console, snoop, Python Tutor, birsdeye)
-