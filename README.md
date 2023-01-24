# SNA

# Purpose:
to convert Danielle Montagne's 2021-09-29 dataset to Jeffrey Smith's output (when in doubt go here: https://happygitwithr.com/rstudio-git-github.html)

# Inputs:
+ Markdown files to document what the R code is and does (.rmd), knit into a Word document (.docx)
+ datasets (with numerical values) from SharePoint 
(https://adminliveunc.sharepoint.com/:f:/r/sites/RADx-UPPublicationsAnalysis/Shared%20Documents/Network%20Analysis?csf=1&web=1&e=Yku2P8) 

# Outputs:
+ Knit Word documents (.docx)
+ social graphs of scientific collaboration (i.e., coauthorship) networks (.png?)

# Getting Started--Data Collection
+ automated searches of RADx-UP grant numbers in PubMed and Scopus databases
+ quarterly publications tracking survey sent to RADx-UP project leads 

# Getting Started--R Studio
First time:
+ Create a repository in GitHub; update README
+ Download R & RStudio; open RStudio
+ Create a new project (top right) > version control > GIT > e.g., https://github.com/ [owner name]/[repository name].git. This will create a local directory (i.e., a folder with the repository name in your Documents folder).
+ Upload your exported datasets and Markdown files there. Knitting the Markdown file will generate the visualizations, also saved in that local directory folder
+ Commit your changes: Git tab (top right) > select all those additions (A), add a commit message that summarizes what you're doing in this version, session, or draft > commit those changes > push those committed changes to GitHub (enter your GitHub username and password)

Every time:
+ Set your project (top right in RStudio)
+ Pull any changes made in GitHub to your local directory
+ Commit any changes you make (i.e., saving changes frequently) with a description
+ Push those committed changes to GitHub before you close out of RStudio
