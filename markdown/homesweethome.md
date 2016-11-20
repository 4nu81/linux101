#### Unix Command Format


#### Navigating the Command Line (Readline)

```

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
. # Present working directory
.. # Parent directory
```


#### Bash History


#### Files and Text
```bash
cat # Display and concatenate file contents
sort # sort
less # Pager
nano # Edit files
vim  # Edit files
emacs # Edit files
grep # Regex filter
sed  # Line-based text processor
awk  # Process tabular data
```


#### IO Redirection
```bash
> # Redirect to file
< # Consume on stdin
| # Pipe: connect stdout to stdin
```

