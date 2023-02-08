The whole code is combined & separated in css & js & build in build folder while npm i. & that folder is used by develper tools so you can search the name of button etc in sources of developer tools

Steps to contribute to a project 🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️🤷‍♂️:-

Dont use mongodb atlas,use local mongodb inside github codespace it stores all data in cloud of database and even your link is something else of server but u will only get your CRUD using thunder by localhost:defined inside container.

Commit changes in a branch Codespace -> Push to branch in Personal repo -> Make pull request to brach in Company repo

1. FORK the whole company repo to your own github.
2. Create a Codespace for that BRANCH you have to work on in your own github ac or clone repo locally.
4. Install "dev conatiner"(in online codespace prebuild, no need to install dev container) to "Clone repository in container volume" -> select "BRANCH"-> "Environment like nodejs" if no docker file already defined.[Codespaces is same like local docker] [Never clone the repo locally & also in codespace u cant do that so its best to not clone it👍👍][Open docker desktop app before opeing vscode]
Note: U need to select a devcontainer to start local devlopment in container 
6. COMMIT to that branch to save code/changes in codespace along with timestamp & message
7. PUSH the commits/Code from codespace to that brach in ur own repo.
8. SYNC FORK/FETCH to update to yr brach in repo with new changes made on company repo's brach by others. -> FETCH that changes from local repo to yr codespace
9. NOTE: While SYNC FORK ,if changes made on file in company repo & changes made on file by you is same file then CONFLICT will occur & u need to resolve it. 
10. Make a PULL REQUEST/Contribute to that brach in company repo to MERGE your code in their repo.

NOTE: Fork copies whole repo with all braches.
      In local vscode directlly use pull(equals fetch->merge), because fetch just tells there is change local github website.
 

Install all other dependencies inside the project locally.

Install docker to  make copy the environment in devcontainer.

You dont need to install anything to open a repo having devcontainer. Just open in codespace it will automatically setup all environment written in devcontainer.

Note: If company repo is showing in your "Top repo", it doesnt mean u need to directlly work on it. It only means you have either opened a issue,commented or pull reequest. Even if company gives access to their repo, it is not for directly working on it. It is that only u can fork it.

How to reverse the commits 😎:-
After reset commit command (it will show to pull/sync from local github website, but dont do that) do "git push --force" to push it. It deletes all commit history after a selected commit. If u have generated PR & now reset the commit less than or equal to organization commit PR will automatically closed by you.


After revert commit command creates an new commit to nullify a commit.
Note:Deleting a individual commit requires revert or rebasing.Dont do that, it is not the way developers reverse commits. Never use rebase command while working on an organinzation projects. It is used for changing commit from one branch to another or something like this.

Note : You can revert a single commit but if no conflict occurs. If there is another commit in new line in same file & u want to revert previous commit, conflict will occur. So dont do it

You cant open another PR from one brach till it is not closed

💀Avoid Deleting file in file changed in PR doesnt deletes commit to that file but it creates a new commit which deletes the whole file.

👍PR automatically updated with your commits.

Clear cache if devcontainer not working.

If port not connecting in container, u need to delete the container & download repo again

In frontend, the developer tools 1st thing i,e console is used to print & debug indexing

IF u are either working in frontend or backend, u can access the exact divname or name of block in code by using devtools, since it is linked to your local code & localhost. 

🟢Docker crashes then dont retry or edit . Just close vscode & clear cache %temp% temp then restart

devcontainer.json is specially built for vscode to automatic build all environment or execute the files(it can be docker file also) & specially extensions written in it. It can also have independent images of noejs etc but locally u need docker desktop app to run.

All files having "docker" word are independent image created using docker.

If devcontainer is there & it is written inside devcontainer.json to execute the docker or a image it will execute but if Docker is independent than you can execute the docker file yourself

Run dev configuration using command pallette or anything & it will scan all docker files inside the repo. Either choose the docker or use microsoft devcontainer

Run npm install even after npm is auto installed in node container otherwise concurrency issue while npm run 
💀In devcontainer in codespace or local if select nodejs & monngodb npm install error . So use docker compose only
It doesnt run even if u use microsoft devcontainer environment & dont do npm install after the auto npm install.

If npm installtion or any installtion is stuck or doing samething at some point without resulting a error, it is internet problem even if it is 1mb/sec & even it is 5g wifi & its more than 1000s

After cant compose more than 1 docker file. So after composing using devconfigure, u cant compose any docker file of original github repo

In devcontiner, if asking selct service client server. Then select client it will start all the proxy servers required for it.

ThunderClient, PostMan can be used as client side to call the apis

502 gateway i,e port forwardeed but server not started run the server

NEVER EVER :Either commpose independt using docker or devcontainer make local environt. Dont compsose using devocntainer error in habitica

Github codespace extension : ALows to use localhost i,e 127.0.0.1. but direct codespaces doest allows port to be localhost

.env.example or config.json.example is given to modify & store local database & api keys setup

Adoption of devcontainer with take hardly 5 months then do development
