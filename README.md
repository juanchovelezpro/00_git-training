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
| Command                       | Description                                    |
|-------------------------------|------------------------------------------------|
| git branch -d <branch_name>   | Delete branch                                  |
| git branch                    | View branches and highlight the current branch |
| git checkout <branch_name>    | Switch to branch                               |
| git checkout -b <branch_name> | Create and switch new branch                   |
|                               |                                                |


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
![alt text](https://i.ibb.co/Gv8nFY1/pullrequest.png "Logo Title Text 1")  

### Discuss and review your code
> Once a Pull Request has been opened, the person or team reviewing your changes may have questions or comments. Perhaps the coding style doesn't match project guidelines, the change is missing unit tests, or maybe everything looks great and props are in order. Pull Requests are designed to encourage and capture this type of conversation.
![alt text](https://i.ibb.co/DfvzqzM/propened.png "Logo Title Text 1")  

### Update and merge
You can update local repository to newest commit  
- ```  git pull ```

For merge current branch with other branch
- ``` git merge <branch_name> ```  

### Utils commands
Replace local changes 
- git checkout -- <filename>
  
Undo all changes and commit
```
git fetch origin
git reset --hard origin/master  
```

## REFERENCES
- https://rogerdudler.github.io/git-guide/index.es.html
- https://guides.github.com/introduction/flow/


