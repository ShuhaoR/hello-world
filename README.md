# hello-world

I love teaching Git!
I love CS
third line

git add
git add README.md
git add \*.md
git commit -m "Anything"
git push origin main
git pull
git status

My commands:
Last login: Mon Sep 19 14:16:27 on ttys000
(base) shuhaoruan@10-23-5-35 ~ % ssh-keygen -t ed25519 -C "sr5553@nyu.edu"  
Generating public/private ed25519 key pair.
Enter file in which to save the key (/Users/shuhaoruan/.ssh/id*ed25519):
Created directory '/Users/shuhaoruan/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /Users/shuhaoruan/.ssh/id_ed25519.
Your public key has been saved in /Users/shuhaoruan/.ssh/id_ed25519.pub.
The key fingerprint is:
SHA256:M7WBLNr/bkOCBE6ZAAVQEmWcy4DOCWk1c9bIP0CNb4A sr5553@nyu.edu
The key's randomart image is:
+--[ED25519 256]--+
|OXB*+_= |
|=+oEX_ + . |
|=o.+ ._ o o |
| +o .o.\* . o |
| ..o.S . |
| ...o. |
| .o |
| .o |
| oo. |
+----[SHA256]-----+
(base) shuhaoruan@10-23-5-35 ~ % cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIB55YWswDejjJe4gam4my2vsBmhIIi3LzajNUwFpJg6R sr5553@nyu.edu
(base) shuhaoruan@10-23-5-35 ~ % git config --global user.name "ShuhaoR"
(base) shuhaoruan@10-23-5-35 ~ % git config --global user.email"sr5553@nyu.edu"
(base) shuhaoruan@10-23-5-35 ~ % git config --global init.defaultBranch main
(base) shuhaoruan@10-23-5-35 ~ % git config --list
credential.helper=osxkeychain
user.name=ShuhaoR
user.email=test@w3schools.com
core.autocrlf=input
init.defaultbranch=main
(base) shuhaoruan@10-23-5-35 ~ % cd ~/Desktop
(base) shuhaoruan@10-23-5-35 Desktop % git clone git@github.com:ShuhaoR/hello-world.git
Cloning into 'hello-world'...
The authenticity of host 'github.com (140.82.112.3)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,140.82.112.3' (ECDSA) to the list of known hosts.
Enter passphrase for key '/Users/shuhaoruan/.ssh/id_ed25519':
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
(base) shuhaoruan@10-23-5-35 Desktop % ls
561653658248_.pic
661653658806*.pic.pdf
Arch
Blank_Authorization_for_Release_of_Information.pdf
Certification_of_Disability.pdf
ComSecAssOne
Coursera F5CCLLKQQK9D.pdf
HTML
IpserLabCofounderAgreementShuhaoRuan.docx
IpserLabCofounderAgreementShuhaoRuan.pdf
IpserLabInternshipOfferLetterShuhaoRuan (1) (1).pdf
IpserLabInternshipOfferLetterShuhaoRuan (1).pdf
IpserLabInternshipOfferLetterShuhaoRuan.docx
IpserLabInternshipOfferLetterShuhaoRuan.pdf
Letter of Residence* Shuhao Ruan.pdf
Memory
Midterm Materials
NJ TRANSIT Rail System Map – October 2021.pdf
NRc7xB3wQZ-XO8Qd8CGfng*8e2ffd04e9b64f1787517b179f5b3710_YelpDataCourseraPR2.txt
NYC DOT
NYUWASSBUNAP.pdf
OS pfd
Paid-internship-agreement-form (1).pdf
Paid-internship-agreement-form.docx
Paid-internship-agreement-form.pdf
PolyArchive
Question8.py~
Screen Shot 2022-05-28 at 1.29.41 PM.png
Screen Shot 2022-05-28 at 1.29.56 PM.png
Screen Shot 2022-05-29 at 12.46.53 PM.png
Screen Shot 2022-06-01 at 4.49.51 PM.png
Screen Shot 2022-06-05 at 10.30.19 PM.png
Shuhao Ruan - Assignment 1.pdf
Shuhao Ruan - Assignment 2.pdf
Shuhao Ruan - Introduction.pdf
Shuhao Ruan_offer_letter.pdf
ShuhaoRuanPaid-internship-agreement-form.pdf
SolarSystemAssets
Student Self-Service Site* Portal.mht
Student Self-Service Site* Portal.pdf
Unpaid-internship-agreement-form.pdf
View Submission * Gradescope_files
Year 2020
**pycache**
algo
anubis — Anubis IDE_files
app.py
app.py~
e15_simple_incomplete
equip-list.pdf
extractFunction.py
firstPage.html~
hello-world
hw1.css
index.html
index.html~
jre-8u333-macosx-x64.dmg
lent.html
lent.html~
licensed-image.jpeg
maclea_UCL
me.html
me.html~
myDoc
resumeFall2022.pdf
resumeShuhao (1).docx
sRuanVisualStudio
shuhao.css~
shuhaoLearningCoursera.html~
shuhaoUdemy
single-file-example.html
sr.html
sr.java
sr.java~
sweAssignmentOne.pdf
(base) shuhaoruan@10-23-5-35 Desktop % cd hello-world/
(base) shuhaoruan@10-23-5-35 hello-world % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

no changes added to commit (use "git add" and/or "git commit -a")
(base) shuhaoruan@10-23-5-35 hello-world % git add README.md
(base) shuhaoruan@10-23-5-35 hello-world % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
modified: README.md

(base) shuhaoruan@10-23-5-35 hello-world % git commit -m "wrote a line about teaching"
[main 3967df2] wrote a line about teaching
1 file changed, 3 insertions(+), 1 deletion(-)
(base) shuhaoruan@10-23-5-35 hello-world % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
(use "git push" to publish your local commits)

nothing to commit, working tree clean
(base) shuhaoruan@10-23-5-35 hello-world % git push origin main
Enter passphrase for key '/Users/shuhaoruan/.ssh/id_ed25519':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 287 bytes | 287.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:ShuhaoR/hello-world.git
758b5ef..3967df2 main -> main
(base) shuhaoruan@10-23-5-35 hello-world % git add \*.md
(base) shuhaoruan@10-23-5-35 hello-world % git commit -m "wrote a line about teaching"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

no changes added to commit (use "git add" and/or "git commit -a")
(base) shuhaoruan@10-23-5-35 hello-world % git push origin main  
Warning: Permanently added the ECDSA host key for IP address '140.82.112.4' to the list of known hosts.
Enter passphrase for key '/Users/shuhaoruan/.ssh/id_ed25519':
Everything up-to-date
(base) shuhaoruan@10-23-5-35 hello-world % git commit -m "wrote a line about teaching"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

no changes added to commit (use "git add" and/or "git commit -a")
(base) shuhaoruan@10-23-5-35 hello-world % git add \*.md  
(base) shuhaoruan@10-23-5-35 hello-world % git commit -m "wrote a line about teaching"
[main ca822a6] wrote a line about teaching
1 file changed, 1 insertion(+)
(base) shuhaoruan@10-23-5-35 hello-world % git push origin main  
Warning: Permanently added the ECDSA host key for IP address '140.82.113.4' to the list of known hosts.
Enter passphrase for key '/Users/shuhaoruan/.ssh/id_ed25519':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:ShuhaoR/hello-world.git
3967df2..ca822a6 main -> main
(base) shuhaoruan@10-23-5-35 hello-world %
