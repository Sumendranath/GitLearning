# GitLearning
A Practise ground for me to learn git commans

If I create a local reposistory without a name and wants to upload to the github
git init
cat config                                                                                                                                                                [core]                                                                                                                                                                              repositoryformatversion = 0                                                                                                                                                 filemode = false                                                                                                                                                            bare = false                                                                                                                                                                logallrefupdates = true                                                                                                                                                     ignorecase = true   

git add <folder1> <folder2> <etc.>
  
git branch development 

git checkout development                                                                                                                                                  Switched to branch 'development' 

git commit -m "Your message about the commit"
git remote add origin https://github.com/yourUsername/yourRepository.git
git push -u origin development
git push origin development
