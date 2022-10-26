# Welcome to REC-CSE-LAB

This Public GitHub Organization is created for ***Learning Purpose Only***.
Please `Don't misuse` Any of Lab Repo present in this Organization as I have created this organization only for Learning and Lab exam preparation.
Hope you find this organization and Repos in it useful.
You are welcome to contribute to any of the Repos present in the organization.
You're also welcome to add any of your Repo related to CSE Labs.
For more details check out [Contribution section](#Contribution).

> **Note**
>
>> This GitHub Organization and the repos inside them are mainly for [REC](https://raghuenggcollege.com/ "visit our college website") student.
>
>> But, you're welcome to add your college lab repo to this organization.


<br/>


## Disclaimer:

As I have mentioned above, this GitHub Organization is created for sole purpose of **Learning and preparing for Lab Exams**. 
I [Shamith Nakka](https://github.com/iamwatchdogs "goto my @iamwatchdogs") *(creator of this GitHub Organization)* am **NOT** responsible for any *malpractice/improper/illegal* use of any repository present in this Organization.
And it's my duty to minimize the possiblity of any *misuse* of this Organization. 
I will **NOT** be taking any responsibility, if any of the *student was found cheating* in Lab exams using any of the forked Repos from this Organization.


<br/>


## Organization's Inventory:

This Public GitHub Organization is basically collection of REC Lab session. As for the time being, this organization contains the following Repos:

- [Complier_Design (Archived)](https://github.com/REC-CSE-LAB/Complier_Design "visit Complier_Design")
- [Computer_Network_Lab](https://github.com/REC-CSE-LAB/Computer_Network_Lab "visit Computer_Network_Lab")
- [DBMS_Lab](https://github.com/REC-CSE-LAB/DBMS_Lab "visit DBMS_Lab")
- [Java_Lab_sem_4 (Archived)](https://github.com/REC-CSE-LAB/Java_Lab_sem_4 "visit Java_Lab_sem_4")
- [Operating_System_Lab](https://github.com/REC-CSE-LAB/Operating_System_Lab "visit Operating_System_Lab")
- [R_Programming_Lab (Archived)](https://github.com/REC-CSE-LAB/R_Programming_Lab "visit R_Programming_Lab")


<br/>


## Contribution:

I heartly welcome people who are willing to [Contribution](#Contribution "Contribution means merging your work towards the repo into the original repo") to any of the repos present in this public organization.
Make sure you are fimilar with the following skills required:

- ***Lab related skills** *( like programming language and stuff )*.
- ***Git**.
- ***GitHub**.
- GitHub flavored Markdown Language *( optional, but still recommended to acquire )*.
- VS Code *( suggested )*.

After you're comfortable with the above mentioned skills, then you can start contributing to the repos.
You can follow the folloein basic step to started:

- **Step 1:** Fork any repo into your own personal GitHub account.

<div align="center">

![Forking a Repo](https://media.geeksforgeeks.org/wp-content/uploads/20220323232607/Screenshot20220323232536.png)
  
</div>

- **Step 2:** Clone the forked repo into your own personal system.

<div align="center">

![Cloning a Repo](https://media.geeksforgeeks.org/wp-content/uploads/20201220230314/Screenshot146.png)
  
</div>

```bash
# Use git clone command to download and set the remote url at a time.
git clone your_forked_repo_url

# To open the clone Repo in your personal system.
cd repo_name
```

- **Step 3:** Create a new branch and checkout to that branch.

```bash
# You can use 'branch' to create a branch.
git branch your_branch_name

# And checkout to that branch
git checkout your_branch_name
```

<p align="center"> -- OR -- </p>

```bash
# You can directly create and checkout
git checkout -b your_branch_name
```

- **Step 4:** Work on the repo. Then add and commit your changes.

```bash
# If you have added a new file/rename an file. 
# Then you should add them into git vcs database using 'git add .' command
git add .

# You can commit the changes in the repo using 'git commit' command
git commit -m "message describing the changes in the repo"

# If you have done changes to the existing file, 
# then you can directly commit using the following command:
git commit -am "message describing the changes in the repo"
```

- **Step 5:** After commit all your changes, push it to your Forked Repo
```bash
# You can use 'git push' command to push the changes into your remote repo
git push origin your_branch_name
```

- **Step 6:** As soon as you're done pushing changes, you can see a dialog box in you Forked repo say "Compare & Pull Request". Click it.

- **Step 7:** Create a Pull Request to the original repo with short title *( If possible, a detail description )*. you can also tag the issue, if there is any.

> **Note**
>
>> Some of the Repos present inside this Organization are archived as it has been completed and has no issue in it.
>> But if you wish to add some changes to it or found out something wrong with the repos, You can post it on the [Issues related to Archived Repos](https://github.com/REC-CSE-LAB/.github/discussions/2 "goto Issues related to Archived Repos") discussion tab.

