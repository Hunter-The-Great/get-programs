A short program to get programs to grade from GitHub Classroom. 

Requires 3 files:
  `token.txt`- file containing your GitHub token
  `class.txt`- file containing the name of the class (used in the URLs of the repos)
  `usernames.csv`- file in the project directory containing all the usernames of the student's repos you want
  
---

Format command as such:
`python3 hw.py -t {token.txt} {class.txt} {assignment name} {destination directory}`
