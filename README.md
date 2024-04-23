# This project is created for practice purposes in learning how to automate APIs using Postman, newman as collection runner and jenkins to run on local machine.

https://docs.github.com/en/rest/repos/repos?apiVersion=2022-11-28#create-an-organization-repository

## **CRUD Operations**
1. Created a github repo
2. Get the repo
3. Update the repo
4. Delete the repo

## Integrated the same with newman using report https://www.npmjs.com/package/newman-reporter-htmlextra 

1. Created a Freestyle project in jenkins
2. Added a build step in the project, and chose Execute Shell. The build step executes a shell command. Enter a shell command to run, such as
  - newman run /Users/vinuthar/Desktop/GitHubAPIProject.json -e /Users/vinuthar/Desktop/GitHubEnv.json -r htmlextra

<img width="1786" alt="Screenshot 2024-04-23 at 7 54 55 AM" src="https://github.com/VinuthaRavindranath/Github-API-Postman-Project/assets/36601711/08b65b7a-7ecb-486b-997c-fb05073085ff">



