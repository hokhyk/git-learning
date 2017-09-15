https://github.com/hokhyk/git-learning.git

# git clean  -d  -fx ""
http://www.kernel.org/pub/software/scm/git/docs/git-clean.html

-x means ignored files are also removed as well as files unknown to git.
-d means remove untracked directories in addition to untracked files.
-f is required to force it to run.

# get remote branch to local directory.
git fetch origin master
git diff
git merge origin/master

git pull origin/master

#合并pull两个不同的项目 --allow-unrelated-histories
出现的问题如何去解决fatal: refusing to merge unrelated histories
git pull origin master --allow-unrelated-histories