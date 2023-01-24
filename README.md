# SNA

# Purpose:
to convert Danielle Montagne's 2021-09-29 dataset to Jeffrey Smith's output (when in doubt go here: https://happygitwithr.com/rstudio-git-github.html)

# Inputs:
+ Markdown files to document what the R code is and does (.rmd), knit into a Word document (.docx)
+ datasets (with numerical values) from SharePoint 
(https://adminliveunc.sharepoint.com/:f:/r/sites/RADx-UPPublicationsAnalysis/Shared%20Documents/Network%20Analysis?csf=1&web=1&e=Yku2P8) 
+ process model of JS's inputs/outputs & programs, based on the SP information architecture (https://miro.com/app/board/uXjVPuznJ_k=/?share_link_id=344244582605)


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
+ Upload your exported datasets and Markdown files there. The code that you will run is an .rmd file. Markdown is a plain text format that incorporates R code and outputs into a .docx, .pdf, or .html files. Knitting the Markdown file will generate the visualizations, also saved in that local directory folder
+ Commit your changes: Git tab (top right) > select all those additions (A), add a commit message that summarizes what you're doing in this version, session, or draft > commit those changes > push those committed changes to GitHub (enter your GitHub username and password)

Every time:
1. Set your project (top right in RStudio)
2. Pull any changes made in GitHub to your local directory FIRST
3. R Markdown files tend to clean, analyze, visualize data:
 + import or read in your dataset
 + remove informational headers
 + define/recode missingness (e.g., -99 = NA)
 + factor categorical (dichotomous, nominal, ordinal) variables
 + select or subset the data you want to analyze
 + run any analyses
 + plot any visualizations
4. Commit any changes you  make (i.e., saving changes frequently) with a description.
5. Push those committed changes to GitHub before you close out of RStudio.
