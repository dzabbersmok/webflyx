Use git log -1 to get the hash of your last commit.


git log (q to exit, arrow keys to scroll)
git cat-file -p <hash>

Git has a command to view the contents of your config:
git config list --local

You can also just view the contents of your local config file directly:
cat .git/config
