# Manage subtree

This repository uses subtree for `ansible/symplegma`. To update subtree:

```
git remote add -f symplegma https://github.com/clusterfrak-dynamics/symplegma 
git subtree pull --prefix ansible/symplegma symplegma master --squash
```
