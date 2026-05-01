
دستور `cp` برای **کپی کردن فایل‌ها و دایرکتوری‌ها** در لینوکس استفاده می‌شود.


cp [OPTION] SOURCE DEST

**Common Options:**
- `-r` : Copy directories recursively.
- `-a` : Archive mode (preserves permissions, ownership, timestamps, links).
- `-v` : Verbose output (shows what's being copied).
- `-i` : Interactive — asks before overwriting files.
- `-u` : Only copy when the source is newer than the destination.

cd change directory
To use `cd` on a directory, you must have execute (`x`) permission on that directory.

useradd
useradd is a low-level Linux command used to create a new user account.

useradd [options] username
Common options

-m : create the user’s home directory

-d : specify a custom home directory

-s : set the user’s login shell

-c : add a comment or full name

-g : set the primary group

-G : add supplementary groups

-u : set a custom UID

-e : set an account expiration date 

forexm:
useradd -m -s /bin/bash ali  

This creates a new user named ali with a home directory and Bash shell. 

usermod
usermod is used to modify an existing user account.
While useradd creates users, usermod edits and updates their propertis

usermod [options] username
-c  
Change user comment (full name)

-d   Change home directory

-m   Move home directory content (used with -d)

-s   Change login shell

-g   Change primary group

-G   Set supplementary groups

-a   Append user to groups (used with -G)

-l   Change username (login name) 
usermod -l newname oldname


-u   Change UID

-e   Set account expiration date

-L   Lock the user account

-U   Unlock the user account









