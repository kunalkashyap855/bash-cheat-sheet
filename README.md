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
apt-get                 # Install and update packages
```
