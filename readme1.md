Tutorial for contributing to a project with Git and GitHub: Beginners
Let's learn GitHub! Feel free to use the issues in this git sample Project to learn Git and Github. Add commands you learned that are useful to make this like documentation. Hopefully it will be fun and teach you so you can contribute to bigger projects in the future.

Mini tutorial for beginners
To contribute to a project the first thing you have to do is:

Create a Fork of the repository: we will have a button that specifically says Fork which will generate us an exact copy of the project we want to contribute to.
Then we clone the repository from our terminal.
Commands:

git clone [url] myproject
Explanation:

git clone allows us to specify that we will clone the repository.
url refers to the project where we want to contribute in this case https://github.com/namruthahari/Sample-Git-Repo.git.
myproject refers to the name we want to give to the project in our local files, in case we don't give it a name it will use the repository name.
Example:

git clone https://github.com/namruthahari/Sample-Git-Repo.git myproject
After cloning the repository you can start contributing to any file in the project. In our case we will create an index.html file.

We have created the index.html file now we want to keep track of that file.

The first thing we will do is:

Add our file to the scenario with the command:
git add .
Explanation:

git add . adds the changes that have been made to our repository, in this way we will send the changes to wait on the stage.

Check the status of our files with the command:

git status -s
Explanation:

with git status we are telling git that we want to check the status of the files we have added.
-s is a shorthand for output information indicating what change has been made to the file and the file name.
output:

M index.html