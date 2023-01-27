Daylen Allen 
CS 2400
Jan 27, 2023


1. git version 2.17.1
2. user.name=Hacked5
   user.email=daylenallen04@gmail.com
3. It show a synopsis of the commands, gives a description of the commands, and has an option at the bottom for a manual page "git-add(2)."

GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working tree, and it
 Manual page git-add(1) line 1 (press h for help or q to quit)



4. The output of the command is:

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)



5. The output is: 

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


6. The output of the  command again is: 

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md



7. The output of the command is:

On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

nothing added to commit but untracked files present (use "git add" to track)

8. The output of the command is:

commit ab17b50e33aef012fa1e5e75d3c6b6bbfa62ee09 (HEAD -> master)
Author: Hacked5 <daylenallen04@gmail.com>
Date:   Fri Jan 27 14:07:53 2023 -0500

    Initial commit

9. Output is:

Username for 'https://github.com': Hacked5
Password for 'https://Hacked5@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Hacked5/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

10. No they were not

11. Nothing was changed. 

Command output:

Username for 'https://github.com': Hacked5   
Password for 'https://Hacked5@github.com': 
To https://github.com/Hacked5/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Hacked5/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12. The file was change and 1 insertion was added.

Readme.md text: 

Daylen Allen Hacked5
CS 2400, Section 109

13. The output is: 
 .  ..  .git  .gitignore  README.md

14. 








