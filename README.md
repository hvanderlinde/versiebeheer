dfrsgrgaesgargewrhfgiesuhiguegeugFPEOWGFOIUESBCJ VAK;           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Forward-port local commits to the updated upstream head
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
jelmer.terwal@nvc2234 ~/src/hendrik master $ git terminal --hlep
git: 'terminal' is not a git command. See 'git --help'.
jelmer.terwal@nvc2234 ~/src/hendrik master $ --help
-bash: --help: command not found
jelmer.terwal@nvc2234 ~/src/hendrik master $ git help <concept>
-bash: syntax error near unexpected token `newline'
jelmer.terwal@nvc2234 ~/src/hendrik master $ git init
Reinitialized existing Git repository in /Users/jelmer.terwal/src/hendrik/.git/
jelmer.terwal@nvc2234 ~/src/hendrik master $ vi README.md 
jelmer.terwal@nvc2234 ~/src/hendrik master $ git diff
diff --git a/README.md b/README.md
index 0f97803..3931cdc 100644
--- a/README.md
+++ b/README.md
@@ -2,6 +2,8 @@ flop Version control
 =================
 Changes gonna comet diff
 
+
+POLLEWOPS
 20km ver weg een wolf!
 
 modified
jelmer.terwal@nvc2234 ~/src/hendrik master $ cd ..
jelmer.terwal@nvc2234 ~/src $ mkdir nieuwe_medewerkerportaal
jelmer.terwal@nvc2234 ~/src $ git clone https://github.com/nedap/medewerkerportaal.git
fatal: destination path 'medewerkerportaal' already exists and is not an empty directory.
jelmer.terwal@nvc2234 ~/src $ cd nieuwe_medewerkerportaal/
jelmer.terwal@nvc2234 ~/src/nieuwe_medewerkerportaal $ git clone https://github.com/nedap/medewerkerportaal.git
Cloning into 'medewerkerportaal'...
remote: Counting objects: 73317, done.
remote: Compressing objects: 100% (1304/1304), done.
^Cceiving objects:  81% (59387/73317), 78.89 MiB | 4.22 MiB/s     
jelmer.terwal@nvc2234 ~/src/nieuwe_medewerkerportaal $ cd ..
jelmer.terwal@nvc2234 ~/src $ rm -rf nieuwe_medewerkerportaal/
jelmer.terwal@nvc2234 ~/src $ git status                                              
fatal: Not a git repository (or any of the parent directories): .git
jelmer.terwal@nvc2234 ~/src $ cd source
-bash: cd: source: No such file or directory
jelmer.terwal@nvc2234 ~/src $ cd/hendrik
-bash: cd/hendrik: No such file or directory
jelmer.terwal@nvc2234 ~/src $ cd hendrik\
> hello
-bash: cd: hendrikhello: No such file or directory
jelmer.terwal@nvc2234 ~/src $ mdir hendrik
-bash: mdir: command not found
jelmer.terwal@nvc2234 ~/src $ mkdir hendrik
mkdir: hendrik: File exists
jelmer.terwal@nvc2234 ~/src $ cd hendrik
jelmer.terwal@nvc2234 ~/src/hendrik master $ cd ..
jelmer.terwal@nvc2234 ~/src $ mkdir hendrikvanderlinde
jelmer.terwal@nvc2234 ~/src $ git clone git@github.com:hvanderlinde/versiebeheer.git
Cloning into 'versiebeheer'...
remote: Counting objects: 19, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 19 (delta 6), reused 19 (delta 6), pack-reused 0
Receiving objects: 100% (19/19), done.
Resolving deltas: 100% (6/6), done.
Checking connectivity... done.
jelmer.terwal@nvc2234 ~/src $ vi README.md
jelmer.terwal@nvc2234 ~/src $ cd versiebeheer
jelmer.terwal@nvc2234 ~/src/versiebeheer master $ README.md
-bash: README.md: command not found
jelmer.terwal@nvc2234 ~/src/versiebeheer master $ vi README.md
jelmer.terwal@nvc2234 ~/src/versiebeheer master $ vi README.md

dfrsgrgaesgargewrhfgiesuhiguegeugFPEOWGFOIUESBCJ VAK;:WQ
Version Control
===============

Is about managing source code. And creating backups.

Git
---

We are using Git, it is very powerful. Even on Windows.

GitHub
------

We use GitHub with our team. We'll look at it in a while.




SVN
---

Old stuff.


Met de groeten van
---

Nedap University Lichting 2