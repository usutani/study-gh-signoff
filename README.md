[gh-signoff](https://github.com/basecamp/gh-signoff) を試す。

GitHub にパブリックリポジトリを作る。

```
gh repo create study-gh-signoff --public --source=. --remote=origin --push
git remote -v
```

How to sign off

```
# Install the extension
gh extension install basecamp/gh-signoff

# When your tests pass, sign off on your PR
gh signoff
```

To require signoff for PR merges

```
# Require signoff to merge PRs
gh signoff install
```

PR を作る。サインオフしてマージする。

```
gh pr create -f
gh pr view --web
gh signoff status
gh signoff
gh signoff status
gh pr merge -d
```
