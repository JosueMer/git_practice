# git_practice
$ git add resume.txt
$ git commit -m "pro pirates"
[master 34f409f] pro pirates
 1 file changed, 1 insertion(+), 1 deletion(-)
$ git checkout fencing
Switched to branch 'fencing'
$ git add resume.txt
$ git commit -m "Smee"

$ git checkout master
Switched to branch 'master'
$ git merge fencing
Auto-merging resume.txt
CONFLICT (content): Merge conflict in resume.txt
Automatic merge failed; fix conflicts and then commit the result.
$ git add resume.txt
$ git commit -m "Resolve merge conflict"
[master b183442] Resolve merge conflict