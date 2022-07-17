# bash-cheat-sheet

Various types of Linux/Unix commands that every software engineer should know.

- [Basic Linux Commands](#basic-linux-commands)
- [File Permission Commands](#file-permission-commands)
- [Environment Variables Commands](#environment-variables-commands)
- [User Management Commands](#user-management-commands)
- [Networking Coomnds](#networking-commands)
- [Process Commands](#process-commands)
- [Vi Editing Commands](#vi-editing-commands)

## Basic Linux Commands

```bash
ls                      # List all files and directories in the present working directory
```
```bash
ls -R                   # List files in sub-directories as well
```
```bash
ls -al                  # List files and directories with detailed information like permissions, size, owner, etc.

cd or cd ~              # Navigate to HOME directory

cd ..                   # Move one level up

cd foo                  # Move into 'foo' sub-directory

cat > filename          # Create a new file

cat filename            # Display contents of the file

mv file <new_file_path> # Move file/directory from one place to another

mv foo.txt bar.txt      # Rename file from 'foo' to 'bar'

sudo                    # Allows regular users to run commands as superusers

rm filename             # Delete a file

rmdir directoryname     # Delete a directory

rm -rf directory        # Delete a non-empty sub-directory forcefully

man <command>           # See information for a command

history                 # List all past commands typed in the current terminal session

clear                   # Clear the terminal

mkdir directory_name    # Create a new directory in the present working directory or at the specified path

apt-get                 # Install and update packages
```
