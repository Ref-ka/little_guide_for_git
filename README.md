# Hi, there is little roadmap for work with git!
---
## 1. First step is download git (and gitbush if you work on windows)

## 2. Second step is make derictory 

### For moving you can use:

cd (a name of derictory/ "~" to move to root derictory in your computer/ ".." to move up from current derictory)

### For actions with files and derictories you can use:
1. touch (a name of file) "makes file"
2. mkdir (a name of derictory) "makes derictory"
3. rm (a name of file or derictory) "deletes a file or empty derictory"
4. rmdir (a name of derictory) "deletes full derictory"

## 3. Now you can start to work with git:

### For first actions with git you can use:
1. git init "initialyze git repository in current derictory"
2. git status "for checking the main information of git repository"
3. git add (name of file or derictory/ '--all' for add all content from current derictory) "this is prepare befor make commit"
4. git commit (name of file or derictory/ '--all' for add all content from current derictory) "for save all changes"

## There is some information about states of files in git:

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  staged -- "make changes" --> staged version and modified version;
  modified -- "git add" --> staged;

``` 