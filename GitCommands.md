### Open Source Projects

Open source projects are projects which
are initiated by a developer or a team of
developers and made open so that
anyone can contribute to its
development and maintenance. Such
projects are made by collaborative
efforts of several people.Some examples are

- Android Operating System
- VLC media player
- Firefox Web Browser

### Git divides our workarea into 3 stages:

1. **Working directory:** Where we
   are creating and making edits to
   our files.

2. **Staging area:** When the files are
   ready to be committed, we have
   to stage them first.

3. **Local Git Repository:** After the
   files are committed, they become
   a part of commit history in a local
   repository.

## Git Commands

- **git init:** initialize your repository
  with git. Git starts tracking
  changes in your files
- **git add [file]:** add a file/file
  change from your working
  directory to staging area
- **git commit-m:** Commit a file to
  commit history

  You can compare this with Get, Set, Go!
  First we **GET** the files we have
  modified, then we **SET** them up in the
  staging area and then we commit **(GO)**
  in our local repository.
  Then there is also a remote repository
  where we can push all our work so that
  anyone else (a team member / another
  developer) can access our work.

- **git remote add [remotename]
  [remoteURLAddress]:** Connect
  your local repository to a remote
  repository (example github).
- **git push:** Push the current local
  repository to remote
- **git clone [url]:** Clone the remote
  repository into a local repository

  ***

Commit is adding the work to the
HISTORY of the works you are doing.
You can move back and forward in your
commits

git diff --staged :This will show you the difference
between the last committed file and the
currently staged file

git diff: git diff is very helpful if a developer is
looking at changes made by someone
else in their code since they last worked
on it.
