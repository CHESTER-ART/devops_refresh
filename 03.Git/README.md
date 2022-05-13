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
#!/bin/bash
# git push to GitHub, GitLab, BitBucket
git remote set-url --add --push github git@github.com:a-lik-a/DevOps.git
git remote set-url --add --push gitlab git@gitlab.com:a-lik-a/devops.git
git remote set-url --add --push bitbucket git@bitbucket.org:A_lik_A/devops.git
printf "push to GitHub"
git push github
printf "push to GitLab"
git push gitlab
printf "push to BitBucket"
git push bitbucket
printf "success maybe"
```
