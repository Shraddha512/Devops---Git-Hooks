Git basics
==========

### Introduction Sequence

**Commits:**

```
git commit
git commit
```

**Branching with Git :**

```
git branch bugFix
git checkout bugFix
```

**Merging with Git :**

```
git branch bugFix
git checkout bugFix
git commit
git checkout master
git commit
git merge bugFix
```

**Learn Rebase Introduction:**

```
git branch bugFix
git checkout bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```

### Ramping Up

**Detaching HEAD :**

```
git  checkout bugFix
git checkout C4
```

**Relative References 1:**

```
git checkout bugFix
git checkout HEAD^
```

**Relative References 2:**

```
git branch –f master C6
git checkout HEAD~1
git branch –f  bugFix HEAD~1
```

**Reversing Changes In Git :**

```
git checkout local
git reset HEAD~1
git checkout pushed
git revert  HEAD
```
