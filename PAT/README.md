# Setup of Git using Personal Access Token (PAT)
1. Login to your Github -> Click on your profile icon -> Settings
2. Go to Developer Settings -> Personal Access Tokens -> Tokens (classic)
3. Click on 'Generate new token' and generate a new token with expriation date per your choice.
4. Make sure to copy the PAT you just created, since it can't be copied again.
![PAT](image.png)
5. After creating your repository. 
6. Make the remote origin for your repository using your Github PAT with following format:  
https://your-username:your-PAT@github.com/repo-name.git     
For example: https://HiraWaheed:PAT@github.com/HiraWaheed/commiting_tree.git  
7. Set this as remote origin of your repo using following command:
```
git remote add origin https://your-username:your-PAT@github.com/repo-name.git 
```
8. Now you won't need to enter your password everytime you push to a repo.
9. Note: PATs can have all kinds of access from admin to limited access to one repo as well.
