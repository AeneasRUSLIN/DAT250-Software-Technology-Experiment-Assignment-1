# DAT250-Software-Technology-Experiment-Assignment-1


During the installation of the Maven software management tool, when adding the PATH environment variable, I misplaced the JAVA_HOME in the "User variables for user" instead of "System variables". Then I used mvn -v to check that it was installed correctly.

Towards the end of the Heroku tutorial, in the "Define Config Vars" step, I couldn't use git commit -m "Demo". I received the error message :

"Author identity unknown
*** Please tell me who you are."

I had to run :
git config --global user.email "user@email.com"
git config --global user.name "username"

Afterwards, I was able to finish deploying my local changes to Heroku.

Deployed Heroku app URL :
https://mysterious-tor-52276.herokuapp.com/hello
