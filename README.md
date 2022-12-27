Steps to contribute to a project 🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️:-

Commit changes in a branch Codespace -> Push to branch in Personal repo -> Make pull request to brach in Company repo

1. FORK the whole company repo to your own github.
2. Create a Codespace for that BRANCH you have to work on in your own github ac or clone repo locally.
3. While local development, U need to install "Docker desktop" in laptop for opening the project in a container.
4. Install "dev conatiner"(in online codespace prebuild, no need to install dev container) to "Clone repository in container volume" -> select "BRANCH"-> "Environment like nodejs" if no docker file already defined.[Codespaces is same like local docker] [Never clone the repo locally]
6. COMMIT to that branch to save code/changes in codespace along with timestamp & message
7. PUSH the commits/Code from codespace to that brach in ur own repo.
8. SYNC FORK/FETCH to update to yr brach in repo with new changes made on company repo's brach by others. -> FETCH that changes from local repo to yr codespace
9. NOTE: While SYNC FORK ,if changes made on file in company repo & changes made on file by you is same file then CONFLICT will occur & u need to resolve it. 
10. Make a PULL REQUEST/Contribute to that brach in company repo to MERGE your code in their repo.

NOTE: Fork copies whole repo with all braches.
      But Commit,Push,Pull request,Sync/fetch is done only done on single brach which u are given to work on.

NOTE: In vscode desktop : 
1. Install git then connect ur local computer to github ac by typing this in the terminal : 
2. 1.git config --global user.name "amritrai5757" 
3. 2.git config --global user.email "amritrai5757@gmail.com"
4. Use "Clone repository" -> "Clone from github" -> Choose the destination.
Commiting saves code with timestamp in offline,local desktop file just like in online code saved in codespace by commiting. 


Install all other dependencies inside the project locally.

Install docker to  make copy the environment in devcontainer.

You dont need to install anything to open a repo having devcontainer. Just open in codespace it will automatically setup all environment written in devcontainer.
