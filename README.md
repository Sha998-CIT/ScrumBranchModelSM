# ScrumBranchModelSM
Project: M-theta Technology Solutions (not the real name) - I am asked to create a branching model to help M-theta Technology Solutions team understand the Git Feature Branch Workflow for faster and efficient integration of work. 
Background: 
M-theta Technology Solutions hired me as a DevOps Architect consultant. It is undergoing an infrastructural change to implement DevOps to develop and deliver the products. Since M-theta is an Agile organization, they follow the Scrum methodology to develop the projects incrementally. Hence, the company wants to adopt Git as a Source Code Management (SCM) tool for faster integration of work and smooth transition into DevOps.
As a DevOps Architect, I was asked to build a branching model to demonstrate the Git Feature Branch Workflow for the company’s engineering team. My branching model creates –
•	Production branch – this is the main (master) branch. Only initial and the final fair copy will be on this branch. 
•	Integration branch – this will be where most of the work and features will be developed. It will have two branches inside it namely Feature 1 and Feature 2, that represents two features that M-theta is developing on its gaming app (representing second and third life after Nebula WWIII between daredevils and evilangels) 
•	Hotfix branch – this will be used for fixing any issues that could come up from Integration or Production branches.

Steps to perform:
1.	Start with the Production branch (master branch), and then create a HotFix and Integration branch
2.	Subsequently, create Feature 1 and 2 branches that integrate to the Integration branch.
3.	Commit some changes in the Feature 2 branch and merge it into the Integration branch. Delete this branch once merging is complete.
4.	Commit some changes in the Feature 1 branch and rebase it to the Integration branch.
5.	Merge the Integration branch into Hotfix and Production branch to update these branches.
6.	Commit some changes in Feature 1 branch, and then merge it into Integration, Hotfix, and Production branch. Delete this branch once merging is complete.
7.	Commit some changes in the Hotfix branch and merge it into the Production as well as the Integration branch.


(This is an educational project to train and demonstrate Git and GitHub capabilities for facilitating  Scrum methodology to develop projects incrementally)
Source – Simplilearn USA
 
