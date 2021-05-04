# Cumulus AKM Proof of concept


This is an open respository for testing how the Active Knowledge Modelling (AKM) tool can be integrated with the OSDU community, open source software, and data definintions. The work is done as a collaboration between Equinor and Kavca. Kavca is developing as an open source tool for modelling data and workflows.

The OSDU platform is released under the Apache 2 software license. This site is used to store some of the OSDU data definitions for testing purposes. 

Relevant resources

https://osduforum.org/

https://akmclient-beta.herokuapp.com/


# Prosedure for downloading models
Modell and metamodel files are saved as a project (json file) 

---
Initial step: 
1. Install VSCode editor
2. Clone/dowload this repository
---
To Download project (models), type the following in the terminal window :

1.  git pull

---

To Upload project (models), type the following in the terminal window  :
1. git add .  (adds all changed files to local repository)
2. git commit -m "change msg" (Commits the changed files with a message)
3. git push (uploads the local repository (with changes) to GitHub)

---

To prepare the project file for upload (push)

The AKMM models are save as project files to the "Downloadsfolder" with a name like:

"AKMM-Project_Cumulus_2021-04-23T14_02_15.json"



The name i the repository is just: "Cumulus.json

Copy this file to a temporary file i.e. : "Cumulus_old.json"


To merge the new project file with the old file use the git command:

"git merge-file merged-file-name.json new-file-name.json old-file-name.json"



Ex.:
git    merge-file Cumulus.json      AKMM-Project_Cumulus_2021-04-23T14_02_15.json     Cumulus_old.json