# Git-Hub-Actions-Actual-CI-CD-Deployment
3 tier application which has front end , backend and database, front end using nginx (mount our index.html file with nginx index.html file), in backend java code is there, compile this java code and generate .jar, and used this jar file for deployment , deployment have done using docker compose.


##### CI-CD Workflow Using Githhu Actions #######

## CI.yml --> github action pipeline

--> in ci we clone the code and move to actual code repo
--> and genereate artifact
--> run test cases


## CD.yml --> github ation pipeline

--> we take the artifact from ci pieline and use for deployment
--> deploymen using compose and completly automated
-->
