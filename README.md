<h1 align="center"> TXT </h1>
 
Create an remote repository called TXT.

A repository is created in github.

=> respositories =>new

Clone the TXT repository to the local machine.

git clone

Inside the local TXT create a file “new.txt”.

touch new.txt

Add file in git.

git add new.txt

Commit the file.

commit –m “add new.txt”

Submit a file to an external GitHub repository.

git push

Edit the contents of the “new.txt” file - write information about yourself (full name, age, number of pets, future desired salary). Everything should be written in TXT format.

to start editing => i

vim new.txt

1. Full name: Anastasia Alexandrovna,
2. Age: 20,
3. No. of pets: 1 cute kitty,
4. Future desired salary: 100 million.

to exit editing => esc => :wq

Push changes to an remote repository.

git add new.txt, git commit –m “edited content”, git push

Create preferences.txt file

touch preferences.txt

Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in the file preferences.txt in TXT format.

vim preferences.txt

to start editing => i

1. Favorite movie: maid,
2. Favorite series: Killing Eve,
3. Favorite food: noodles,
4. Favorite season: spring and autumn,
5. Country I want to go to: France.

to exit editing=> esc => :wq

Create a file sklls.txt add information about the skills that will be studied on the course in TXT format

vim skills.txt

to start editing => i

Skills: Basic theory. Structure and methods of HTTP. JSON, XML, their structure. API testing with Postman. Mobile testing. Basics of SQL.

to exit editing => esc => :wq

Make a commit in one line.

git commit –m “new txt files”

Send 2 files at once to an external repository.

git add .

git push

On the web interface, create a bug_report.txt file.

The bug_report.txt file is created in the github.

add file=>create new file

Commit changes changes on the web interface.

сommit changes

Modify the bug_report.txt file on the web interface, add a bug report in TXT format.

The bug_report.txt file changes in the github.

=>Edit this file

1. Summary: Constant sneezing,
2. Project: Nastya,
3. Component: Nasopharynx,
4. Version: 1.20 ,
5. Severity: S5 Trivial,
6. Priority: P3 Low,
7. Status: New,
8.Author: Anastasia,
9. Assigned To: Anastasia,
10. Description: The bug was found at home, this error appeared due to allergies or dust, inhale deeply enough and the error will repeat, error result: sneezing, expected result: no sneezing.

Commit changes changes on the web interface.

сommit changes

Synchronize external and local TXT repository

git pull (to check if everything is synced correctly use the git fetch command)
