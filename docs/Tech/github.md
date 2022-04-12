
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
