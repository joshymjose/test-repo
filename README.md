# test-repo
1. install the "repo" utility


```bash
    mkdir ~/bin
    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo
```

2. initalize and sync using repo

repository to test google repo tool
```bash
    repo init -u git@github.com:joshymjose/test-repo.git -b main -m default.xml
    repo sync -j4
```
