#### Unix Command Format

```bash
<command> -f param --flag param   [operand1, operand2...]

ls -l /usr/local
cp /etc/passwd /tmp/
mv /tmp/passwd /tmp/passwd.bak
wc (input on STDIN, end with <CTRL-d>)
```


#### Navigating the Command Line (Readline)

```
<TAB> - command completion (Bash)
<CTRL-l> - clear screen
<CTRL-f> - forward
<CTRL-h> - backwards
<CTRL-d> - delete
<CTRL-a> - jump to line beginning
<CTRL-e> - jump to line end
```


#### `ls` - list files and directories

```bash
ls -a # Show hidden files
ls -l # Show metadata
ls -R # Recursive
ls -d # Show directory information
ls -t # Order by modification time (newest first)
ls -tr # Order by modification time (newest last)
```


#### Who and where am I?

```bash
whoami # Display (effective) User
id <user> # Display user id and group membership
pwd # Display current directory
su # Switch user
sudo # Execute a command as user
```


#### Navigating the Filesystem

```bash
cd # Change working directory
pushd # save a directory
popd  # move to a saved directory
## File path expansion ##
~ # Home Directory
- # Previous pwd
. # Present working directory
.. # Parent directory
```

[Linux Filesystem Hierarchy Standard](https://de.wikipedia.org/wiki/Filesystem_Hierarchy_Standard)


#### Bash History

```bash
[arrow up]/[arrow down] # previous/next command
history # Display previous command
!<x> # repeat command x
!! repeat last command
<CTL>-r # Search history
```


#### Files and Text
```bash
cp # copy files
mv # move (rename) files
cat # Display and concatenate file contents
sort # sort
less # Pager
nano # Edit files
vim  # Edit files
emacs # Edit files
grep # Regex filter
sed  # Line-based text processor
awk  # Process tabular data
find # recursively search directories
```

#### IO Redirection
```bash
SDTIN = 0
STDOUT = 1
STDERR = 2
> # Redirect to 
< # Consume on stdin
| # Pipe: connect stdout to stdin
```

#### Command Substitution
```bash
$(command)  # evaluate output of command
$(<file) # same as cat file
```

