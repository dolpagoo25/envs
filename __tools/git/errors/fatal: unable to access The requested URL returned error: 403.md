# fatal: unable to access 'https://github.com/*/*.git/': The requested URL returned error: 403

## Problem
```bash
thekim@thekim32:~/github$ ./batch_git_push 
TARGET_REPOSITORIES: myweb
cd /home/thekim/github/myweb
git add . && git commit -m 'Add new stuff by batch_git_push' && git push
[main a74a355] Add new stuff by batch_git_push
 125 files changed, 44376 insertions(+)
 create mode 100644 public_html/assets/scss/abstracts/_mixins.scss
  ...
Username for 'https://github.com': dolpagoo25
Password for 'https://dolpagoo25@github.com':
remote: Permission to dolpagoo25/myweb.git denied to dolpagoo25.
fatal: unable to access 'https://github.com/dolpagoo25/myweb.git/': The requested URL returned error: 403
thekim@thekim32:~/github$
```

## Hint
```
I created a new GitHub account and setting it up on my local machine resulted in the following error. What's wrong?

$ cd /home/thekim/github/myweb
$ git add . && git commit -m 'Add new stuff by batch_git_push' && git push
  ...
fatal: unable to access 'https://github.com/dolpagoo25/myweb.git/': The requested URL returned error: 403
$
```
