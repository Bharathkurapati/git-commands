# git-commands

//////////////////////////////////////////////////


		git commands
		
//////////////////////////////////////////////////

///////////////////////////////////// take test_deployment /////////////////

1. git status (to check any changes)

2. git checkout test_deployment	(switch to test_deployment branch)

3. git pull origin test_deployment (to take pull from test_deployement branch code using this code)		

4. git checkout obelas_UI (to switch by brach)  (switch to obelas_UI branch)

5. git pull origin obelas_UI (server to take pull our local branch obelas_UI)

6. git merge test_deployment (to merge test_deployement code in obelas_UI branch)


///////////////////////////////////// my changes push to test_deployment /////////////////

7. git add --all

8. git commit -m "message"

9. git push origin obelas_UI (to push your changes to server)

10. git checkout test_deployment (switch to test_deployment branch)

11. git pull origin test_deployment (pull the code from test_deployment)

11. git merge obelas_UI (to merge obelas_UI code in to test_deployment branch)

12. git status (to check obelas_UI & test_deployement branches changes) 

13. git push origin test_deployment (to push code your branch to test_deployement)

14. git checkout obelas_UI (back to my branch)

15. python manage.py migrate

///////////////////////////////////// git commit  /////////////////


1. git add -all

2. git status

3. git commit -m  "message"

4. git checkout test_deployment

5. git pull origin test_deployment

6. python manage.py migrate

7. git status

8.  git checkout test_deployment

9. git pull origin test_deployment

10. git pull origin obelas_UI









