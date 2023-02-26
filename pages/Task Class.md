- [4CID]([[Four Component Instructional Design]])
  id:: 63f4bbe3-812a-4421-aaf3-0428228a6208
- If a task class is well defined:
	- learners can use the task class to focus and measure their own study
	- teachers can use a task class to informally asses and guide students
	- task classes can be used as the basis for rubrics and assessments
	- task classes are a helpful guide when creating projects, templates, process guides and exercises
- possible outline for defining task classes in CE
	- (description: a couple sentences overview of the task class' deliverable)
	- *_[[Language Level]]_*: ("allowed" language features)
	- *_[[Notional Machine]]_*: (how to visualize the language level's program memory (either an automated tool or a guide on how to do it manually))
	- *_Environment_*: (where/how a student can run their code. runtime, version, ...)
	- *_Technologies_*: (the language, any libraries, build tools, quality scripts, ...)
	- *_Starter_*: (describe what a learner has to bootstrap a deliverable)
	- *_[[Assessment]] Criteria_*: (how will a task-class deliverable be evaluated)
- An example task class (rewrite to align with [[Welcome to JS]] )
	- Given a buggy program that processes user input, uses an array, uses a function, 1 error, has 1-2 bugs, and 1-2 unnamed variables, a student can complete, fix and describe the program.
	- *_Language Level_*: what is covered in the /isolate folder
	- *_Environment_*: a modern browser's console + debugger, an editor with helpful suggestions and auto-complete, a way to get the code from the editor to the devtools
	- *_Technologies_*: JS
	- *_Starter_*: a program with 1) user data stored in an array 2) a buggy, undocumented function that takes an array as an argument + correct test cases 3) 2-3 level-appropriate bugs in the main script 4) 1-2 unnamed variables 5) an error
	- *_Assessment Criteria_*: is the function fixed and documented, are the bugs fixed (and the process documented), are the variables well-named (and the process documented), is the error fixed (and the process documented), is the program well-described