# 03.Git
```bash
 1313  git init
 1314  vim ~/DevOps/g_push.sh
 1315  ~/DevOps/g_push.sh
 1316  chmod +x ~/DevOps/g_push.sh
 1317  ~/DevOps/g_push.sh

```
### Script
```bash
git remote add github git@github.com:a-lik-a/DevOps.git
git remote add gitlab git@gitlab.com:a-lik-a/devops.git
git remote add bitbucket git@bitbucket.org:A_lik_A/devops.git
printf "push to GitHub"
git push --set-upstream github master
printf "push to GitLab"
git push --set-upstream  gitlab master
printf "push to BitBucket"
git push --set-upstream  bitbucket master
printf "success maybe"
```
### +commit
