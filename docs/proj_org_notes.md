#How to get RStudio and GitHub to talk 

## Things to do once within your new R Project

### Creating a GitHub respository

*RStudio*: In the **terminal** run `git config --list` and then, in the **console** run `usethis::use_git_config(user.name = "enazario11", user.email = "enazario@ucsc.edu")`. 

*GitHub*: create a personal token with the command `usethis::create_github_token()`. Name the token "RSTUDIO" and change the expiration date to the preferred setting. Then, click generate token. Copy the token text on the next page and enter it when asked after running `gitcreds::gitcreds_set()` in the **console**. Yay! Now they can chat!

*Using RStudio to create the GitHub repo*: 
  **A.** Commit the uncommitted files with `use_github()`
  **B.** Call `git_default_branch_rename()`
  **C.** Call `use_github()`

# What to do when future changes are made that we want to synch from our local system. 

## **Step 1:** Activate pages on GitHub in browser (Settings > Pages). "Source" should say *Deploy from a branch*, "Branch" should change from *none* to *main*, and directory should change from */(root)* to */docs*. Save!

## **Step 2:** Using the Git pane within RStudio, check the boxes next to the modified files, click commit and add a message then commit, then click push. 

## **Step 3:** Return to your GitHub browser and make sure it worked! Progress can be seen under the actions tab. 
