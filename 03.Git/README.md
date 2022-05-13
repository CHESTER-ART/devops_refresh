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
printf "push to GitHub"
git push --set-upstream git@github.com:a-lik-a/DevOps.git master
printf "push to GitLab"
git push --set-upstream git@gitlab.com:a-lik-a/devops.git master
printf "push to BitBucket"
git push --set-upstream git@bitbucket.org:A_lik_A/devops.git master
printf "success maybe"
```
