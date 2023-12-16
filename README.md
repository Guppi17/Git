#  Git 

Git is a version control system available on every developer’s computer. It allows easy branching and merging. At the same time GitHub makes it a lot easier for individuals and teams to use Git for version control and collaboration. Here, I will share with you the fundamental steps and commands I used to create my portfolio. This project reflects my professional journey and skills.  

<div align="center">
<img src="https://github.com/Guppi17/Guppi17/blob/main/yes-hi.gif" width='600'/>
</div>



## ✰ Task 1

##### Creating, cloning, pushing and pulling repositories  
```git
git init Guppi17                                          # Create your repository with the same name as your username 
git clone git@github.com:Guppi17/Guppi17.git              # Clone your repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git          # Clone github.com/testrusau/testrusau on your computer to a separate folder
cd testrusau                                              # Push data from testrusau repository to your own one 
git push git@github.com:Guppi17/testrusau.git main:main
git commit -m "Update"                                    # Open the README.md file and replace each block with a separate commit 
git push 

```
## ✰ Task 2

##### Creating, adding remote repositories  
```git
git init SQL-Queries                                              # Create separate repository for portfolio item 
git remote add sql https://github.com/Guppi17/SQL-Queries.git     # Declarie repository remotely 
README.md edited manually                                         # Add links to your repositories to the README.md file
git commit -m "Update"                                            # Push changes to remote repository
git push                                                     
```

<div align="center">
<img src="https://github.com/Guppi17/Guppi17/blob/main/df8e36f90e6a20167f071ed1b6c10e50.gif" width='150'/><img src="https://github.com/Guppi17/Guppi17/blob/main/df8e36f90e6a20167f071ed1b6c10e50.gif" width='150'/><img src="https://github.com/Guppi17/Guppi17/blob/main/df8e36f90e6a20167f071ed1b6c10e50.gif" width='150'/><img src="https://github.com/Guppi17/Guppi17/blob/main/df8e36f90e6a20167f071ed1b6c10e50.gif" width='150'/>
</div>
