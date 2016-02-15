* Getting a git repository

	* Can create a new repository
	* Can take existing project/directory and import repository as a clone

	* Import = git clone [url]
	* New = 
		* git add *.c
		* git add LICENSE
		* git commit -m 'initial project version' 


* Recording changes to repository

	* git status - checks which files are in which state (git status -s = simplified output)
	* The states are:
		* Untracked
		* Unmodified
		* Modified
		* Staged
	* git add [filename] = adds untracked file to staging area
      - think of more as “add this content to the next commit”
