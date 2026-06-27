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

