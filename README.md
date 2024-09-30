# A02
Repository for IS117 - Intro to Website Development

WebStorm Directions:
1. Type WebStorm download into any web browser and click on the JetBrains result.
2. Download the .exe file for your operating system.
3. Launch the .exe file and leave the default options on, unless you have a specific need.
4. From here, you can launch Webstorm and either purchase a license or start a free trial, after which you will be able to start using it.

WebStorm Download Link: https://www.jetbrains.com/webstorm/download/#section=windows


Git Directions:
1. Type Git download into any browser and click on the Git result.
2. Click on one of the three links that say your operating system (macOS, Windows, or Linux/Unix).
3. Click on the downloaded file, which will install Git Bash on your PC.
4. Once it is done installing, you have Git on your computer and can use it.

Git Download Link: https://git-scm.com/downloads


GitHub Directions:
1. Navigate to https://github.com/ and create a free account.
2. Once you have an account, go to your dashboard and creat a new repository that includes a readme file.
3. You can have a GitHub repository.


Connecting Git Bash to GitHub:
1. Open up Git Bash on your device.
2. Type in the command: git config --global user.name "Your username", where your username is your GitHub username.
3. Next, type in the command: git config --global user.email "Your email", where your email is your GitHub email.
4. Almost done. Next we need to clone the repository from GitHub onto the device you are using. Go to your GitHub repository, click on the green "<> Code" button, and click the two squares on top of each other which will say "Copy url to clipboard" if you hover over them.
5. Then, go to Git Bash on your device and type in: git clone and paste the url that you have copied from GitHub.
6. Your Git Bash is now "connected" to your GitHub. 
NOTE: Any time you make changes to either, you must update the other.

Using Git Bash:
1. When you create new files in the local repository, you must go to Git Bash and type: git add "filename or directory/". You must do this for all new files or directories and files or directories that have been changed.
2. You then have to commit the changes by typing: git commit -m "type a commit message here (Ex: Changed CSS file.)"
3. You can then update the GitHub repository by typing: git push origin main
4. In order to download new or updated files from GitHub you type: git pull origin main
5. Finally, in order to check if everything is in order between your local repository and the GitHub repository, use: git status

These are the basics of Git Bash and GitHub, but there are more advanced features that are not necessarily required to be used.


GLOSSARY:
Branch - A branch in GitHub is like a picture of a moment in time that you can interact with. It allows you to go back and fix any bugs, or gives you an environemnt to try to add a new feature. It's essentially version control.

Clone - A clone is simply an exact copy of a certain repository, which includes all of the files that were on GitHub in that repository at that time.

Commit - A commit saves the changes of all the files that you have added or modified to the current branch that you are in.

Fetch - Fetch is used to download the changes that other people have made to the Github repository, but it won't update your local repository.

GIT - Git is a free program that is used mainly by developers to track different changes to their projects and allows them to have different versions of that project.

GitHub - Github is on the opposite side of the same same coin as Git. They are always used together. Github simply allows you to upload your files from your local machine to an online repository. It makes it easier to manage different versions of your files and of course, allows you to access them from anywhere in the world on any machine.

Merge - A merge is used to apply changes from multiple branches into one single branch. Usually the single branch that changes are applied to is the "main" branch.

Merge Conflict - This is an error that occurs when Git cannot automatically apply changes, meaning you will have to manually go in and fix the issue. Some things that cause this are: deleting or changing files without committing, not adding all files, etc.

Push - A push is used to transfer your files, or more accurately your commits from your local repository to the online GitHub repository.

Pull - A pull is used to download files from the GitHub repository onto your local machine.

Remote - A remote is simply where all of your code is stored.

Repository - A repository is the home of the project. It's pretty much the root directory of the project you are working on.