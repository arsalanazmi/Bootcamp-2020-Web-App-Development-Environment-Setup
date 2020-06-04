# Bootcamp-2020
## Assignment#1 : Setup Website Development Environment

1.  Create a new public repository on github and clone it on your local repository.

2.  Create a simple hello world html file and name it index.html. Commit the code and push it on Github.

3. Install Node.js.

    https://nodejs.org/en/download/

4. Install Surge by using following command.
  
    npm install --global surge

5. Generate Surge token by the following command.
  
    surge token
  
6. Save the surge token in the repo's GitHubs secrets.

7. Configuring a Github Actions Workflow.
  
    https://help.github.com/en/actions/reference/workflow-syntax-for-github-actions

    https://help.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow

8. Create surge deployment action file in root repo in .github/workflow directory.

9. Make small change in index.html, commit it and push it again to github.com.

10. Check the action tab to GitHub website and see if the action executed.

11. open website in browser.

    http://bootcamp_practice.surge.sh/
