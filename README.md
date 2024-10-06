# CLI(command line interface)2

### __IO redirection__

__Standard Output__: by default, standard output is screen
 * \> after a command to create and save the output in a file
 * cat displays the content of a text file
 * \>\> appends output to an existing file or create and write to a nes file 

__Standard Input__: by default, standard input is from keyboard
  * /< can redirect input from a file, also can mix \< \> in single line

__pipelines |__: pipeline feed output of previous command to input of next commnad
  * command1 | command2 | command3 |...

__Special characters__: expadn its meaning when given to shell commands
  * echo text: print text
  * echo *: print file in this driectory
  * echo ~: print home driectory

  * \\: backslah can be used to ignore line change in coomand

__Permissions__: linux is multi-user sys, so have a permission assigned owner, group, others
  * - rwx rwx rwx: -is file type -is file d is driectory, first rwx is permission for owner, next permission for the group owner, last permissions for all other users, and r-- only read like this read write ans execute
  * chmod nnn file: change permissions, n transrate to binary then if 111 can rwe 000 is ---
  * sudo: superuser is admin, sudo can use command in superuser

__Text Editors__: you can shoose cli or gui based text editors. vim, emacs, nano, gedit, kwrite ect.

__wget__: download files from the internet

__curl__: fetching, uploading, and managing data over the internet

__grep__: Global Regular Expression Print for searching text within files.
  * -i: Case-insensitive search (finds "apple" and "Apple").
  * -v: Invert the match (finds lines *not* containing the search term).
  * -n: Display line numbers along with matching lines.
  * -r`: Recursive search (searches through all files in a directory and its subdirectories).
  * .*: Matches any character (`.`) zero or more times (`*`).
  * \d: Matches any digit (0-9).
  * [abc]: Matches any single character within the brackets.
  * ^: Matches the beginning of a line.
  * `$: Matches the end of a line.
