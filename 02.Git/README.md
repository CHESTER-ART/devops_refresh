# 02.Git
## bash
```bash
 1125  mkdir 02.Git
 1126  cd 02.Git/
 1127  git init
 1128  git config --global user.name “A-lik-A”
 1129  git config --global user.email “a.lik.a.v.rg@gmail.com”
 1130  date > file11
 1131  git add file11
 1132  git commit -m "1c master"
 1133  date > file12
 1134  git add file12
 1135  git commit -m "2c master"
 1136  git checkout -b "dev"
 1137  date > file23
 1138  git add file23
 1139  git commit -m "1ac dev"
 1140  date > file24
 1141  git add file24
 1142  git commit -m "2ac dev"
 1143  git checkout -b "features/do_one"
 1144  date > file35
 1145  git add file35
 1146  git commit -m "1ac feat"
 1147  git checkout master
 1148  git checkout -b "hotfix/we_gonna_die"
 1149  date > file43
 1150  git add file43
 1151  git commit -m "1ac fix"
 1152  git checkout master
 1153  git merge dev
 1154  git merge features/do_one
 1155  git log --oneline
 1156  git checkout f362638
 1157  git merge hotfix/we_gonna_die
 1158  git merge dev
 1159  git merge features/do_one
```
### master
```bash
b855fee (HEAD) +Merge branch 'features/do_one' into HEAD
ee30eb6 +Merge branch 'dev' into HEAD
0250b08 (hotfix/we_gonna_die) 1ac fix
6be32ff (master, features/do_one) 1ac feat
0560e12 (dev) 2ac dev
d778554 1ac dev
f362638 2c master
c1db03a 1c master
```
### dev
```bash
0560e12 (HEAD -> dev) 2ac dev
d778554 1ac dev
f362638 2c master
c1db03a 1c master
```
### features/do_one
```bash
6be32ff (HEAD -> features/do_one, master) 1ac feat
0560e12 (dev) 2ac dev
d778554 1ac dev
f362638 2c master
c1db03a 1c master
```
### hotfix/we_gonna_die
```bash
0250b08 (HEAD -> hotfix/we_gonna_die) 1ac fix
f362638 2c master
c1db03a 1c master
```
