



To prepare, please:

1. install `git` on your machine
	1. [http://git-scm.com/about](http://git-scm.com/about)
	2. Windows: git bash
2. Create an account on www.github.com

---
# what are we gonna do today?

1. explain git and github
2. a little hands-on workshop
3. set up a git repository in your own code

---
# git vs Github

- git: version control system:
	- software that runs on your computer [http://git-scm.com/about](http://git-scm.com/about)
- github/gitlab:
	- online tool
		- "version control interface" or "continuous integration (CI) server"
		- visualizes a git repository
		- online backup of you code
		- collaborate with other (comment, raise issues)
		- run pipelines on the code (testing, formatting, ...)

---
# a visualization of a local git workflow


![](attachments/commits.png)

- dots: **commits**
- series of commits: **branches**
- dashed dot: **merge commit**

>After three **commits** on the **branch** "main" a **new branch** (called "feature") is created. Three **commits** are done on the **new branch**. In the meantime, two commits are done on the lower branch. Then, the top branch is **merged** into the lower branch, creating a **merge commit** (dashed dot). The lower branch now contains the merged code from both branches (blue + yellow = green). Finally, another commit is done on the lower branch. The upper branch does not exist anymore.

---
# why is this useful?

1. backup of your code online (with version history!)
2. go back in time with your code
3. see exactly what change, when, and why
4. store multiple version of the code (try out different approaches)
5. collaborate with others

---
# demonstration in my IDE (integrated developer environment)

- showing the log of commits
- going back in time
- showing current changes
- diffing files

---
# setting up a git repository in your code

Very simple!

```
git init
```

--- 

# git status

- tells us the status of the repository, in which state are the files?


# git diff

# git commit


# git push


# branches

- 



# merging
