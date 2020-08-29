# GIT Tranining

### Initialize repository  

You can make new local repository: ```  git init ```
or you can clone from remote repository: ```  git clone <url>  ```

Do:

Fork the repository https://github.com/icesi-ops/00_git-training
![alt text](https://i.ibb.co/DbppL0k/Capture.png "Logo Title Text 1")  
  
Clone your forked repository  
- ```  git clone https://github.com/ikermatias/00_git-training  ```

### Workflow 

![alt text](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-Architechture-Git-Tutorial-Edureka-2-768x720.png "Logo Title Text 1")  
![alt text](https://rogerdudler.github.io/git-guide/img/trees.png "Logo Title Text 1")  

### Branches  

The branches are used for make new functions isolated.  
'master' is default branch.  
  
Do:
- ```  git checkout -b <my_name>  ```

Util commands:  
| Command                       	| Description      	|
|-------------------------------	|------------------	|
| git checkout -d <branch_name> 	| Delete a branch  	|
| git checkout <banch_name>     	| Switch to branch 	|
|                               	|                  	|
|                               	|                  	|
|                               	|                  	|
|                               	|                  	|


### Add and Commit  

Do:  

- ```  echo "your_name" >> names  ```
- ``` git add <filename> or git add .```
- ``` git commit -m "Add my name  ```

### Send your changes

Now that you have your changes in "HEAD" (local) you can send the change to remote repository.

Do: 
- ``` git push origin master ```  

Or Also you can send the changes to other branch of your remote repository  
- ``` git push origin <branch_name> ```  
  
## Pull request (Github flow)

> GitHub flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly. 

### Open pull request  
> Pull Requests initiate discussion about your commits. Because they're tightly integrated with the underlying Git repository, anyone can see exactly what changes would be merged if they accept your request.  


