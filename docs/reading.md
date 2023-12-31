# Project Workflows

## Bryan 2017
### setwd()
Using `setwd()` will work if isolated to one user and one system, though is not generalizable among multiple users or devices. Using the file structure developed in an R project and the here package makes it easy to reference document locations within a project (and it's specific subfolders) for any user/device with that given project available on their system. 

### rm(list=ls())
This line will only remove user created objects, but other features will still remain as is in the background (e.g., settings changed from their defaults, loaded packages). This can make things convenient when switching from one project to another in the same session, in that these preferred settings will remain intact. Though, will add hard to track obstacles when working on these projects in the future, as these changes will no longer be present. The Windows short cut is Ctrl+Shift+F10

## Braga et al., 2023

### Issues 
**Issue One:** From the internets, it seems that for new repos, this is a good place for users to id problems they face or is a good platform for discussion about those potential problems. This is preferred to email, as issues experienced by other users could be viewed here as well as their solutions. 

**Issue Two:** In addition to problem identification, issues can be assiged to other collaborators on the project where this tab can track such to-do items. If these requests were sent via email, they could get pushed to the bottom of the inbox pile. Using the issues tab, you can track who still needs to resolve what. woo project management!