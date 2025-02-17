# simple-blog-design (#1 Static Website)

## HTML

- HTML Basics
  - <svg> - icon for menu
  - <a> - pagination
- Semantic HTML

## CSS

- CSS Basics
- CSS Architecture (BEM - Block, Element, Modifier methodology) - a popular naming convention for classes in HTML and CSS
- Making layouts

  - Responsive Cards
  - Work with Page Container:
    ``` `.container {
          width: 92%;
          margin: auto;
          height: 100%;
        	/* border: 2px solid red; */} ```


- Responsive Web Design
  - Small Screen first
    
    ```  `/* smartphone style  */  @media only screen and (max-width: 767px) {}
    /* tablet style  */  @media only screen and (min-width: 768px) and (max-width: 1023px) {}
      /* dekstop style  */  @media only screen and (min-width: 1024px) {} ```
    

## Using Git Commnands with GitHub

GitHub Repo -- (Clone) --> Working Directory --- (Add) ---> Staging Area --- (Commit) ---> .git repo --- (Push) ---> GitHub Repo

### Cloning from GitHub
  
- ` $ git clone <repo url>` clone github repo

### Working with branch locally

- ` $ git branch` list of local branch
- ` $ git branch <branch-name>` create new branch
- ` $ git checkout <branch-name>` branch you want to start working with
- ` $ git branch -d <branch-name>` delete branch
- ` $ git push -u origin <branch-name>` linked this local branch to a remote branch on Github (u - craetes a tracking relationship between two branches (the local and remote))

### Pushing to Github

- `$ git add .` Add to Staging Area
- `$ git commit -m "comments"` Commit to .git repo
- `$ git commit -am "comments"` shortcut for git add/Commit to .git repo
- `$ git push origin main"` Push to GitHub Repo

### Working with Team

- `$ git fetch ` to look for update/branch from GitHub repo.
- `$ git status ` check the status of current working directory
- `$ git pull ` merge the changes from remote repo. to local repo.

### Type of branch (Git Flow)

- 2 Main branch
  - Master - deployable to productions
  - Develop - contains development changes for next released
- Supporting branches
  - HotFixes - Bug needs to be fixed
  - Release -
  - Feature - are short lived and deleted when merged into the base branch
