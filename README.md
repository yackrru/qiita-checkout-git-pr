# qiita-checkout-git-pr
The repository just to checkout pull request.
## Way1
```bash
git fetch origin pull/<IssueID>/head
git checkout FETCH_HEAD
(optional)
git switch -c new_branch
```
## Way2
```bash
git fetch origin pull/<IssueID>/head:new_branch
git checkout new_branch
```
