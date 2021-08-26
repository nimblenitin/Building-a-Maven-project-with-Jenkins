# Building-a-Maven-project-with-Jenkins

Steps to build a simple Java application with Maven in Jenkins-

*As Root*
```
1. Setting up Git in Jenkins-
- Go to Manage Jenkins from the Jenkins dashboard and select Global Tool Configuration.
- Scroll down to the Git section and click on Add git.
- Enter a name to refer to the git installation.
- Enter the path to git at the Path to git executable field (/usr/bin/git) and click Save. 

2. Forking a sample repository
- Login to your Github account.
- Navigate to https://github.com/jenkins-docs/simple-java-maven-app and click on Fork.
- Open the terminal.
- Run git clone [Forked_REPO URL] to clone the repo locally.

3. Creating a Jenkins build job to build a Maven project.
- Select Maven Project as the build job type for the new item in Jenkins.
- Click OK.
- Leave the defaults as they are and scroll down to the Source Code Management section.
- Select Git.
- Enter the local path to the app directory in the Repository URL field.
- Click Save.

4. Building the Maven project.
- Click on the project name in the Jenkins dashboard.
- Click Build Now in the project window. Jenkins will now build your project.
- Click on the Build History to view the build results.
- Click on the Console Output to view the build logs.

```
*As Root*

 

 





