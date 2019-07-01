# My first collaborative Git Project

## Purpose
* To establish good `git` collaboration practices

## Objective
* To create an `index.html` webpage that has a link to each of your profile pages.


### Git Collaboration Strategy

#### Part 1 - Assigning an origin-owner
1. Assign one person to _fork_ the original repository. This will be the _origin-owner_.
2. The _origin owner_ should add each of the group-members as a _contributor_ to the project.


#### Part 2 - Pushing your first change
1. As each of you complete a `profile.html`, ensure that you are _pushing_ your changes.
	* _changes_ can be _pushed_ by executing the following commands.
		1. `git add .`
		2. `git commit -m 'update message'`
		3. `git push -u origin master` 
	



#### Part 3 - Pulling your first change
* You can keep in sync by executing the following commands
	1. `git pull origin master`
	2. `git add .`
	3. `git commit -m 'merged with master'`
	4. `git push -u origin master`

#### Part 4 - Edit the `index.html`
* Edit the `index.html` page to include a link to each of the newly created `profile.html` pages. 