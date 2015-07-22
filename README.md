pos-v0.1-homework-for-class-2-student
=====================================

### 在新建submodule时可以用下面的命令

```
cat repos.txt | awk '{system("git submodule add \"" $2 "\"  \"" $1 "\" ")}'
```
