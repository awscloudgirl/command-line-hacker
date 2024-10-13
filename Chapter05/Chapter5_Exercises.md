# Chapter 5: Exercises

## Exercise 1: Viewing Permissions

- **Objective**: Practice viewing file and directory permissions.
- **Tasks**:
  1. Use `ls -l` to list the permissions of files in your home directory.
  2. Identify the owner, group, and permission settings for each file.
  3. Explain the meaning of the permission string for a specific file.

## Exercise 2: Changing Permissions

- **Objective**: Learn to change file and directory permissions.
- **Tasks**:
  1. Create a new file named `testfile.txt` and set its permissions to `rw-r--r--` using symbolic mode.
  2. Change the permissions of `testfile.txt` to `rwxr-xr-x` using numeric mode.
  3. Verify the changes using `ls -l`.

## Exercise 3: Managing Ownership

- **Objective**: Practice changing file and directory ownership.
- **Tasks**:
  1. Use `chown` to change the owner of `testfile.txt` to another user (if possible).
  2. Use `chgrp` to change the group of `testfile.txt` to a different group.
  3. Verify the ownership changes using `ls -l`.

## Exercise 4: Applying Special Permissions

- **Objective**: Understand and apply special permissions.
- **Tasks**:
  1. Set the setuid permission on an executable file and observe its effect.
  2. Set the setgid permission on a directory and create files within it to see the group inheritance.
  3. Apply the sticky bit to a shared directory and test its impact on file deletion by different users.
