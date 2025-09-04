Git/Linux commands		Function
ls				lists the files in the present working directory
cd				changes directory
mkdir				creates a new dirctory
pwd				tells you where you are, present working directory
touch				creates an empty file
git init			Initializes a new Git repository in your current directory.
				Creates a `.git` folder to start tracking version history.
git status			Displays the current state of your working directory and staging 
				area.  Shows which files are modified, staged, or untracked.
git add <filename>		Stages changes to a specific file so they’re ready to be committed.
				Use `git add .` to stage all changes.
git commit -m "message"		Records a snapshot of staged changes in the repository with a 
				message describing the update.
git remote add origin <URL>	Connects your local repository to a remote one (usually on GitHub)
				using the provided URL.  “origin” is the default name for that
				remote.
git push origin			Pushes your committed changes to the remote repository named
				“origin.”  You’ll usually specify a branch.
git push origin main		Sends your local `main` branch commits to the `main` branch on the
				remote repository named “origin.”

