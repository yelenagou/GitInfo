**What is rebasing?**
1. Rebasing is to cleanup local history
1. Increase accuracy and quality
1. Do not use rebase on a public branch. 

**Rebase Branch from Master**

1. add first file then commit
1. add second file then commit


branch off master
```bash
git commit -a -m "comment a"
git merge-base new_branch master
```
**Cherry picking**
<p>making copies of commits into various branches</p>

```bash
git log --oneline
git log branch_name --oneline
git checkout branch_name
git cherry-pick sha
```


