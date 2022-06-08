
# Github

## SSH

### Windows配置Github的SSH-key

```bash
ssh-keygen -t rsa -C "bearfly1990@163.com"

cat ./id_rsa.pub

# Settings -> SSH and GPG keys -> New SSH key`

```

## Command

```bash
git config --global credential.helper store
git config --global http.sslVerify "false"
```

## 远程分支关联

```bash
git branch --set-upstream-to=origin/bf-workbench bf-workbench
```

## New

```
echo "# java-playground" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:bearfly1990/java-playground.git
git push -u origin main
```

## Delete commit totally

```bash
git rebase -i HEAD~3
```
