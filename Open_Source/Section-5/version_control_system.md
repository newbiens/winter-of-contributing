
**Version Control**

_It is basically all things managing the **source code**._
>It keeps track of all the modifications and changes that are done to the code.
It helps in tracking every individual change made by each contributor and helps in preventing the current work from confliciting.



**Version control is of 2 types.**
1. Centralized Version Control
2. Distributed Version Control

**1. Centralized Version Control**

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/z8l1npw8rrbv9ghwkcyu.png)

 

>In centralized version control there is one main repository and multiple users commit and update in that repository. 

**All changes in the file are tracked in the centralized repo/server**
>In case you lose your central repo, your whole source code will be gone and this is one of the major drawbacks of centralized version control system.

*examples of centralized version control*
  * Tortoise SVN
  * Perforce
  * CVS

**2. Distributed Version Control**

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hpndfhtmjyrx4j236c8j.png)

  

>To overcome the drawbacks of **centralized Version Control** ,distributed version control was introduced.
In this type of version control, a developer clones the main repository of the project and saves it to his/her local hard disk
(disk space is not a matter of concern here as disk space is so cheap that storing many copies of a file doesn’t create a noticeable dent in a hard drive’s free space.)
After cloning the central repo, user commits and updates in the local repo and then do the push pull events to central repo.
If the data on central server is lost, there stays a sense of relief because of repo of project being present in the machine of developers.


*Examples of distributed Version Control*

* Git
* Mercurial
* Bazaar

**There are plenty of advantages of using distributed version control system over centralized one.**

* Branching and merging can happen automatically and quite faster.

* Contributors can work offline because there exist a local repository of the project in their local machine so they can make changes offline.

* Since there are multiple copies of one central repo, even if the central repo gets deleted or lost, we can have a backup.




_This was about the version control system and its types_


Image Source:- [link](https://www.google.com/search?q=version+control&sxsrf=AOaemvJdokxFI_9FqZ7qgNPlQvZfX2cR-Q:1632679740319&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiAjtD_nZ3zAhUnzzgGHXFYB1sQ_AUoAXoECAEQAw&biw=1366&bih=657&dpr=1#imgrc=dtq9En5Aqy4fpM)

