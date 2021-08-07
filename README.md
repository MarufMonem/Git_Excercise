# Git_Excercise
The sole purpose of this repo is to make exercises to practice the art of git! 

## Exercises Steps

_Remember commit messages should be to the point and easily understandable by anyone._

* Clone the following git repository: https://github.com/MarufMonem/Git_Excercise.git
* Create a new branch with the following branch name format Excercise_20____________________. For example: excercise_20210708_1539
* Have a look at the files to understand the structure and data we are dealing with. 
* Lets add your employee information into the employee_info.txt file using the format shown in the employee_list_format.txt file. Then commit changes.
* Due to the huge increase in employees, Enosis has changed its offices from Gulshan 1 to Banani. Lets fix it? 
* But wait, we forgot to add the phone number. Let's do that and make all the commits.
* Check the logs to see the head locations
* Lets merge with the main branch?
* Now as we have merged the change to the master branch we can update the salary code. Seems like we have never passed the number of employees working here. Let's add the total count (see the count from slack? Or make up something 😅).
     
     ```java
     public static void main(String []args){
        int salary = 100000;
	totalSalary (49);
     }
     ```

* Commit to the main branch.
* Let's switch to our exercise branch and add the mail address to the company info.
* We forgot this is the end of the year so people are getting a 10k bonus for performing so well. So we need to add 10k to the salary and while we are at it, why not make the code dynamic? Update the code to the following or add your code with any language you prefer, the skies the limit here! 
```java
public class HelloWorld{
     static void totalSalary(int total_employees, int salary){
         System.out.println(salary * total_employees);
     }
     public static void main(String []args){
        int salary = 110000;
	    int employee_count = 49;
	    totalSalary(employee_count, salary);
     }
}
```

* Lets check the status first then commit
* Merge with the main branch.
#### Oh no we have a conflict!! Can you figure out why we have a conflict?* 
* Lets see where it is (which file) and fix it and make sure the latest changes made are present. 
* Now with the help of git log graph we can see how we branched out and resolved conflicts. Pretty neat, right? 😯 A job well done. 
* Lets go to our projects.txt file and add the last project, “GIT_excercise” and commit changes.
* Let's go back to our branch but alas it doesn have the changes made to main.! Lets update our branch to have all the latest changes (This is a bit tricky).
* Push the changes to remote.
* Now going to the github location you can see your branch https://github.com/MarufMonem/Git_Excercise/branches

Congratulations, you  are done! 🥳 You successfully 
* Made changes
* Committed them
* Created branches
* Switched between them
* Resolved conflicts
* Updated the repo
* Pushed to remote.

> _The branch you created won't be merged due to the structured of the repo where reviews are needed to make changes to the master branch (just in case you were wondering 😅)_
 
 

