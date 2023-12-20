---
title: Linux 101
date: 2023-12-20
description: Linux command referrence and tutorial
draft: false
tags: 
    - linux
    - 101
categories:
    - linux
image: linux.png
---



# Top 10 Linux Commands

This document provides an overview of the first 10 common Linux commands, including explanations, usage, and examples. These commands are fundamental for any Linux user or administrator.

## `ls` - List Directory Contents

**Explanation**: Lists the contents of a directory.

**Usage**:

`ls [options] [file/directory]` 

**Example**:

-   `ls` - Lists files and directories in the current directory.
-   `ls -l` - Lists in long format, showing file permissions, number of links, owner, group, size, and timestamp.

## `cd` - Change Directory

**Explanation**: Changes the current directory.

**Usage**:

`cd [directory]` 

**Example**:

-   `cd /home/user/Documents` - Changes the current directory to `/home/user/Documents`.

## `pwd` - Print Working Directory

**Explanation**: Prints the current working directory.

**Usage**:

`pwd` 

**Example**:

-   `pwd` - Outputs the full pathname of the current directory.

## `mkdir` - Make Directory

**Explanation**: Creates a new directory.

**Usage**:


`mkdir [directory]` 

**Example**:

-   `mkdir new_folder` - Creates a new directory named `new_folder`.

## `rmdir` - Remove Directory

**Explanation**: Removes a directory.

**Usage**:



`rmdir [directory]` 

**Example**:

-   `rmdir old_folder` - Removes the directory named `old_folder`.

## `touch` - Create Empty Files

**Explanation**: Creates a new empty file.

**Usage**:

`touch [file]` 

**Example**:

-   `touch new_file.txt` - Creates a new empty file named `new_file.txt`.

## `rm` - Remove Files or Directories

**Explanation**: Removes files or directories.

**Usage**:

`rm [options] [file/directory]` 

**Example**:

-   `rm file.txt` - Removes the file `file.txt`.
-   `rm -r folder` - Recursively removes the directory `folder` and its contents.

## `cp` - Copy Files or Directories

**Explanation**: Copies files or directories.

**Usage**:

`cp [options] source destination` 

**Example**:

-   `cp file1.txt file2.txt` - Copies `file1.txt` to `file2.txt`.
-   `cp -r folder1 folder2` - Recursively copies `folder1` and its contents to `folder2`.

## `mv` - Move or Rename Files or Directories

**Explanation**: Moves or renames files or directories.

**Usage**:



`mv [options] source destination` 

**Example**:

-   `mv file1.txt file2.txt` - Renames `file1.txt` to `file2.txt`.
-   `mv folder1 folder2` - Moves `folder1` to `folder2`.

## `cat` - Concatenate and Display Files

**Explanation**: Displays the contents of files and concatenates multiple files.

**Usage**:

`cat [options] [file...]` 

**Example**:

-   `cat file.txt` - Displays the contents of `file.txt`.
-   `cat file1.txt file2.txt > combined.txt` - Concatenates `file1.txt` and `file2.txt` and redirects the output to `combined.txt`.
