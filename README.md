- 1. clone personal dotfiles repo
	- `git clone https://github.com/Oberfeldwedler/dotfiles.git`
- 2. optionally clone private `.ssh` submodule
	-
	  ```
	  git submodule init
	  git submodule update
	  ```
	-
- 3. create symlinks and adopt changes from parent directory
	-
	  ```
	  stow --adopt .
	  ```
- 4. use git to manage differences
	-
	  ```
	  git status
	  
	  git restore <<file>>
	  ```
