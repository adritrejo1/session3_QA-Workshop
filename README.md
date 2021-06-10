# session3_QA-Workshop

*Description:

Author: Adriana Trejo Diaz

Challenge Execises-Performance session 3- Thursday Jun 3rd 2021

-Currently the folder contains the following request:


  "testCreateTask": "artillery run CreateATask.yml",
  "testGetActiveTask": "artillery run GetAnActiveTask.yml",
  "testUpdateTask": "artillery run UpdateTask.yml",
  "testCompleteTask": "artillery run ChangeToComplete.yml",
  "testReopenTask": "artillery run ReopenTask.yml",
  "testDeleteTask": "artillery run DeleteTask.yml"


*Intructions:


1.- need to create a folder : mkdir <folder_name>

2.- cd <Folder_name>

3.- npm init -y

4.- npm install --save-dev artillery

5.- cat package.json

6.- create the corresponding files:

"CreateATask.yml",
"GetAnActiveTask.yml",
"UpdateTask.yml",
"ChangeToComplete.yml",
"ReopenTask.yml",
"DeleteTask.yml"


7.- to Run the files one by one

  npm run testCreateTask
  npm run testGetActiveTask
  npm run testUpdateTask
  npm run testCompleteTask
  npm run testReopenTask
  npm run testDeleteTask
