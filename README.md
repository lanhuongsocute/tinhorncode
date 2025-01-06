Tinhorn (Fake) Commit Generator
This project is a "phông bạt" (Tinhorn - fake) code that I found on a Facebook group. It demonstrates how to generate a series of random commits in a Git repository. This project uses some popular Node.js libraries, such as random and simple-git, to automate Git operations and create fake commit histories.

Libraries Used
random: A library for generating random numbers, used here to calculate random weeks and days for generating commit dates.
simple-git: A lightweight library for working with Git commands. It simplifies adding files, committing changes, and pushing them to a remote repository.
moment: A library for manipulating and formatting dates. It is used to calculate random commit dates between two specific points in time.
jsonfile: A library for reading and writing JSON files. This is used to update the data.json file with the generated commit information.
Prerequisites
Node.js installed on your computer.
Git installed and configured.
A GitHub repository ready to push the commits.
Steps to Set Up and Run the Project
Initialize a Node.js Project
Create a new project directory and initialize it with Node.js. Then, install the required libraries (jsonfile, moment, random, simple-git).

Create a Data File
In the root directory of the project, create an empty file named data.json. This file will store the date of each commit.

Write the JavaScript Code
Create a file named index.js and include the code that automates the creation of fake commits. The code reads random dates, creates commits, and pushes them to your Git repository.

Initialize a Git Repository
Inside your project folder, initialize a Git repository using the git init command. This creates the necessary .git folder in your project.

Run the Script
Execute the JavaScript file using Node.js. The script will generate and push commits based on the configuration in the code.

Push to GitHub
Add the remote GitHub repository URL, set the branch (usually main), and push the generated commits to GitHub.

Example Workflow
Initialize the project by running npm init.
Install the required libraries with npm install jsonfile moment random simple-git.
Create the data.json file in the root of the project directory using touch data.json.
Create the index.js file using touch index.js and paste the code into it.
Initialize Git in your project folder by running git init.
Run the script by executing node index.js.
Push the repository to GitHub by first adding the remote origin, then pushing your changes.
Notes
This project is purely for fun and educational purposes. It is a "phông bạt" example of how to use Node.js to automate Git tasks. It should not be used for unethical activities, and the commits generated have no meaningful content.

License
This project is shared as-is with no specific license. Use it responsibly.
