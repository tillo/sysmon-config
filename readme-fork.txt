
Here is how to synchronise this fork's master with upstream

git clone https://github.com/tillo/sysmon-config.git
cd sysmon-config
git remote add upstream https://github.com/SwiftOnSecurity/sysmon-config.git
git branch -u upstream/master
git fetch
git merge
git commit
git branch -u origin/master
git push
