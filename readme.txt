sh-keygen
Generating public/private rsa key pair.
C:\Users\CL3-PC18/.ssh/id_rsa already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\CL3-PC18/.ssh/id_rsa.
Your public key has been saved in C:\Users\CL3-PC18/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:GwRSt4gIVOeU/6zd1Dkc24MeJ7z6pw9WdlYLEFqNOk8 cl3-pc18@DESKTOP-F1TTDQ7
The key's randomart image is:
+---[RSA 3072]----+
|o....++ .  ++    |
| . .++ + .o...   |
|  . ..o o..  .  .|
|       o o E .. o|
|        S + + *+o|
|         = o @o=.|
|        + o .o* .|
|           .oo+. |
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC/kpyPmG+cr4M/bIl2hChwLY5Qh7ohgNB1UmQICKacerDmlsYzdAoPKR2PPlWsLT89fqeuvomJ6hSmo55Ld8nwZvqw/g7TKMep6Bx3U7BODHalgHnbZx/b9Y8RVsBxw8bCuOy7qkjscNrvuCTFECNg/QbojVinTTEG3qn8umRrdEqbbkzFclW2+n1DgB00FMhhy0Lp0yJQLjd6gCbPhYCQe55OiSuSh/Uetbt/7ee78MKooUrDHwXUCIkGvwvwCAVRz1ZT50h0/neYUHnbAWN5EdC+CgQSvvY80IUNqbLybM5IbMU18lm2U+J9niQvLaWApShD8Rklap9ZNGp35sL1dXdFrNhepG687FYGc1UNspz2/mJLnVCLSA1RstUd81Rr2n5CL1rvcVH+xWD/Z+KJEWjdxSxcVcDpP/f08eV80FN1Qgvvi+OLUdq27zlYJG+3dTl616uRSNajvp/gUPW503Adq68keKhF76us4Gu4YaU2PCGGGwYjfLdXWrMyYtM= cl3-pc18@DESKTOP-F1TTDQ7
PS D:\Tungol\Exam> git remote-list
git: 'remote-list' is not a git command. See 'git --help'.
PS D:\Tungol\Exam> g^C
PS D:\Tungol\Exam> ^C
PS D:\Tungol\Exam> git remote list
error: unknown subcommand: `list'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --[no-]verbose    be verbose; must be placed before a subcommand

PS D:\Tungol\Exam> git remote get-url origin
https://github.com/Z3phyr425/MidtermLongTest.git
PS D:\Tungol\Exam> git remote set-url origin git@github.com:Z3phyr425/MidtermLongTest.git
PS D:\Tungol\Exam> git push -u origin main
Enumerating objects: 4142, done.
Counting objects: 100% (4142/4142), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3957/3957), done.
Writing objects: 100% (4142/4142), 5.54 MiB | 1.17 MiB/s, done.
Total 4142 (delta 858), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (858/858), done.
To github.com:Z3phyr425/MidtermLongTest.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.