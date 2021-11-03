# Cumulus AKM Proof of concept


This is an open respository for testing how the Active Knowledge Modelling (AKM) tool can be integrated with the OSDU community, open source software, and data definintions. The work is done as a collaboration between Equinor and Kavca. Kavca is developing as an open source tool for modelling data and workflows.

The OSDU platform is released under the Apache 2 software license. This site is used to store some of the OSDU data definitions for testing purposes. 

Relevant resources

https://osduforum.org/

https://akmclient-beta.herokuapp.com/


# Prosedure for downloading models

Modell and metamodel files are saved as a project (json file) in folders for each sub-project.


Initial step: 
1. Install VSCode editor
2. Go to CUMULUS-AKM-POC repository
3. Clone/dowload this repository to your local machine
   
---

To Download latest version of the project (models) :

1. Make sure you are in the CUMULUS-AKM-POC repository and in your branch. (not master or main)
2. git pull (to get latest version, if somone or you has made changes from another computer or cloud)
3. In AKM Modeller click on the "Model File" blue button and "Choose File", in the Model (light blue) area, then find the file in this local repository folder. ex. ..../github/cumulus-akm-poc/AKMM-Project_Cumulus.json 

---

# Procedure for uploading models

1. In AKM Modeller click the "File" button then in "Export to file" the " Save Project (all) to File".
2. Select the project folder in your local repository.

To update the project (models) in GitHUb, type the following in the terminal window  :

1. git pull ( to make sure you have the latest version from GitHub)
2. git add .  (adds all changed files to local repository)
3. git commit -m "change msg" (Commits the changed files with your message)
3. git push (uploads the local repository (with changes) to GitHub)

---

# Request for updating the main bransh project (models) in GitHub.

Go to the GitHub repository and select the branch you pushed above.
1. Click on the "Compare & pull request" button.
2. Other people can see the changes you have made, and can make comments and approve you pull request. After approval, the changes can be merged into the main branch.
3. Click on Merge pull request and the changes will be merged into the main branch.
4. If you are not going to make any more changes, you can delete your bransch, else just leave it and go back to your local repository and the same branch, and make more work on your model.