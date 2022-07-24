# bash-cheat-sheet

Various types of Linux/Unix commands that every software engineer should know.

- [bash-cheat-sheet](#bash-cheat-sheet)
  - [Basic Linux Commands](#basic-linux-commands)
  - [File Manipulation Commands](#file-manipulation-commands)
  - [File Permission Commands](#file-permission-commands)
  - [Environment Variable Commands](#environment-variable-commands)
  - [User Management Commands](#user-management-commands)
  - [Networking Commands](#networking-commands)
  - [Process Commands](#process-commands)

## Basic Linux Commands

```bash
ls                      # List all files and directories in the present working directory
```

```bash
ls -R                   # List files in sub-directories as well
```

```bash
ls -al                  # List files and directories with detailed information like permissions, size, owner, etc.
```

```bash
cd or cd ~              # Navigate to HOME directory
```

```bash
cd ..                   # Move one level up
```

```bash
cd foo                  # Move into 'foo' sub-directory
```

```bash
cat > filename          # Create a new file
```

```bash
cat filename            # Display contents of the file
```

```bash
mv file <new_file_path> # Move file/directory from one place to another
```

```bash
mv foo.txt bar.txt      # Rename file from 'foo' to 'bar'
```

```bash
sudo                    # Allows regular users to run commands as superusers
```

```bash
rm filename             # Delete a file
```

```bash
rmdir directoryname     # Delete a directory
```

```bash
rm -rf directory        # Delete a non-empty sub-directory forcefully
```

```bash
man <command>           # See information for a command
```

```bash
history                 # List all past commands typed in the current terminal session
```

```bash
clear                   # Clear the terminal
```

```bash
mkdir directory_name    # Create a new directory in the present working directory or at the specified path
```

```bash
cp <PATH_TO_FILE>/foo.txt <NEW_PATH>    # Copy a file from one place to a new place
```

```bash
cp -R <PATH_TO_DIRECTORY> <NEW_PATH>    # Copy a directory from one place to a new place
```

```bash
apt-get                 # Install and update packages
```

## File Manipulation Commands

```bash
touch foo.txt           # Create a file
```

```bash
echo "foo" > bar.txt    # Overwrite a file with content
```

```bash
echo "foo" >> bar.txt   # Append to a file with content
```

```bash
grep "foo" ./bar.txt    # Search for "foo" in file
```

```bash
ln -s foo bar           # Create a symbolic link 'bar' to the 'foo' folder
```

## File Permission Commands

```bash
ls -l                   # List all files with file type and access persmissions
```

```bash
r                       # read permission
```

```bash
w                       # write permission
```

```bash
x                       # execute permission
```

```bash
chown user              # Change the ownsership of a file/directory
```

```bash
chmod user+x foo.sh     # Give the user execute permission
```

## Environment Variable Commands

```bash
echo $VARIABLE              # Display value of a variable
```

```bash
env                         # Display all environment variables
```

```bash
VARIABLE_NAME=variable_val  # Create a new variable
```

```bash
unset VARIABLE_NAME         # Make variable unavailable to child processes
```

```bash
export VARIABLE=value       # Make variable available to child processes
```

## User Management Commands

```bash
sudo adduser username                   # Add a new user
```

```bash
sudo passwd -l 'username'               # Change password of a user
```

```bash
sudo usermos -a 0G GROUPNAME username   # Add a user to a group
```

```bash
finger username                         # Display information of a particular user
```

## Networking Commands

```bash
ssh user@hostname           # Connect to hostname using the user over SSH port 22
```

```bash
ping hostname               # Make ping requests to analyze connections
```

```bash
host hostname               # Show the IPv4 and IPv6 addresses
```

```bash
quit OR ctrl+D              # Logout
```

## Process Commands

```bash
top                         # List all processes interactively
```

```bash
ps all                      # List all processes
```

```bash
ps PID                      # Show status of a particular process
```

```bash
pidof                       # Show PID of a process
```

```bash
bg                          # Run a process in background
```

```bash
fg                          # Run a process in foreground
```

```bash
kill PID                    # Kill a process
```