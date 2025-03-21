<img width="491" alt="image" src="https://github.com/user-attachments/assets/cf5b5ee3-5263-4b45-bfcb-bd9221285550" />

# ITMO OPD Professional Score

## What're we doing here?

**ITMO OPD Professional Score** — a public organization that consists of a set of projects that students of St. Petersburg ITMO University are working on.
Our goal is to develop a service that will allow users to receive recommendations for further job search based on the results of their passing special tests.

## About git rules

### Branches & Pull requests

All our projects are protected by special **rulesets** that prohibit direct pushing of changes to the main project branch. In this regard, the work with projects is carried out as follows:

1) When you receive a task, you need to create a new branch in which you will work in the future. Here are some tips on how to do it:
   - First, let's figure out how to name the branches correctly. All branches must conform to the following format: <br> `<issue-type>/<branch-name>`

     For example, you can create something like that: `feat/create-user-profile` _(you can find more information about branches & commits types below this topic)_

     You can create a new branch using the command `git checkout -b <branch-type>/<branch-name>`

     After creating and moving to a new branch, you can safely start working! :3

2) An important aspect of the work in our projects is the specification of commits. During the work process, we highly recommend making intermediate commits so that in case of unforeseen circumstances you can return to the working version of the project.
  
   Also, all our projects have their own rules for making commits, you can read about them below.

3) After you have finished working on your assignment, you need to push all commits to your newly created branch. After you do this, you will have to open a **Pull Request** to the main branch of the project.
  
   In the Pull Request, you need to fill in some fields: <br>
   1) **Assignees** — choose yourself here
   2) **Labels** — usually the labels are listed in the issue that was assigned to you. Just move them to this field (you can select several pieces)
   3) **Pull request title** - it is usually filled in automatically upon creation, you just need to check that it correctly reflects the essence of the task you were working on.
   4) **Pull request description** - if there are many changes or they cannot be reflected in the pull request title, you can describe them all in detail here. Also in this block, you need to specify the link words that will link the issue you were working on to the pull request. Examples of which words are suitable and how to formalize them can be found below.
      
        <img width="770" alt="image" src="https://github.com/user-attachments/assets/7dfa5fcc-5981-439e-a753-effceaeadc22" />
        
        The keywords can be followed by colons or in uppercase. For example: `Closes: #10`, `CLOSES #10`, or `CLOSES: #10`.

     
   6) **Reviewers** - fill in this section only if it is not filled in automatically. Point there to scobca and TheGeniusOfEternity
  
   **An example of a fully prepared Pull Request:**

    <img width="1264" alt="image" src="https://github.com/user-attachments/assets/c4f028ab-b8bd-4eb1-b996-8cdb0e0ce200" />

4) After you have published the Pull request, you should wait for your code to be checked. If there are any errors in it, we will leave comments and you will need to fix them (go back to paragraph 2 of this instruction), if everything is fine, we will fix the changes and freeze your Pull request.

5) After you have completed the task and your Pull request has frozen, you need to switch back to the main branch. use the command to do this: `git checkout main`

   After that, you need to update the local branch, use the command: `git pull origin main`


**That's it!**
