***0x00. shell, basics**
I started learning to write shell scripts to automate processes on a linux machine:
keywords CWD -> Current Working Directory
0-current_working_directory: prints the absolute path name current working directory.
1-listit: Displays the contents list of current working directory
2-bring_me_home: changes directory to current user's home directory
3-listfile: display all file and directory information in CWD
4-listmorefiles: display CWD's contents including hidden files
5-listfilesdigitonly: display CWD's content including;
    .long format
    .with user and group ID displayed numerically
    .And hidden file (starting with .)
6-firstdirectory: creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile: moves the file "betty" from /tmp/ to /tmp/my_first_directory.
8-firstdelete: Deletes the file betty.
9-firstdirdeletion: Deletes the directory my_first_directory from /tmp directory.
10-back: changes Current Working Directory (CWD) to previous one.
11-lists: lists all files (+ hidden) in CWD, CWD's parent and /boot directory.
12-file_type: prints the type of file of the file named "iamafile"
13-symbolic_link: creates a symbolic link to /bin/ls named __ls__
14-copy_html: copies all the HTML files from CWD to CWD's parent, but only updates.
100-lets_move: moves: moves all files that begin with uppercase letters to /tmp/u.
101-clean_emacs: delete all emacs backup files in the CWD.
102-tree: creates the directory and path welcome/to/school in the CWD. all at once.
103-commas: list all file and directories of the CWD, separated by commas(,);
    .Directory names end with slash(/)
    .Hidden files are also listed.
    .listing is alpha-numerically ordered.
school.mgc: A file that can be used with "file" command to detect School data files. {School data files always contain the string SCHOOL at offset 0}
