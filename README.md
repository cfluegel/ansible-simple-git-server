# (Very simple) Git Repo Server

I followed the instruction from the website https://dylanninin.com/blog/2013/12/23/git_server.html and made a rudimentary playbook.


## Gettings Started

Prepare a inventory file (currently ignored by gitignore) and edit the 'group_vars/all'.

Add the ssh keys and the repositories to the appropriate lists. Existing repos will be skipped and thus not reinitialized once again.