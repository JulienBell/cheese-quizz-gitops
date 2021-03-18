# cheese-quizz-gitops

Example where we define deployment configuration on two different environment UAT and Production

- Both environnement are using same deployment script located in **base** repository
- Configuration variations are described through patch scripts in **overlays** repository that define specific configuration adaptation per destination envir
