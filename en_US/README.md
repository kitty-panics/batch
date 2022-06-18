# Batch

[中文](../README.md) | English

Batch help documentation.

## Generate

Open the CMD program and execute the following command.

```Batch
help > temp_File

grep -oE "^[A-Z]*" temp_File > filter_File

for /f %i in (filter_File) do cmd /c %i /? > en_US\%i

del /q temp_File && del /q filter_File
```

**P.S.**

`GRAFTABL` command failed to generate help documentation.

## Index

| Command       | Description                                                |
|:--------------|:-----------------------------------------------------------|
| [ASSOC]       | Displays or modifies file extension associations.
| [ATTRIB]      | Displays or changes file attributes.
| [BREAK]       | Sets or clears extended CTRL+C checking.
| [BCDEDIT]     | Sets properties in boot database to control boot loading.
| [CACLS]       | Displays or modifies access control lists (ACLs) of files.
| [CALL]        | Calls one batch program from another.
| [CD]          | Displays the name of or changes the current directory.
| [CHCP]        | Displays or sets the active code page number.
| [CHDIR]       | Displays the name of or changes the current directory.
| [CHKDSK]      | Checks a disk and displays a status report.
| [CHKNTFS]     | Displays or modifies the checking of disk at boot time.
| [CLS]         | Clears the screen.
| [CMD]         | Starts a new instance of the Windows command interpreter.
| [COLOR]       | Sets the default console foreground and background colors.
| [COMP]        | Compares the contents of two files or sets of files.
| [COMPACT]     | Displays or alters the compression of files on NTFS partitions.
| [CONVERT]     | Converts FAT volumes to NTFS.  You cannot convert the current drive.
| [COPY]        | Copies one or more files to another location.
| [DATE]        | Displays or sets the date.
| [DEL]         | Deletes one or more files.
| [DIR]         | Displays a list of files and subdirectories in a directory.
| [DISKCOMP]    | Compares the contents of two floppy disks.
| [DISKCOPY]    | Copies the contents of one floppy disk to another.
| [DISKPART]    | Displays or configures Disk Partition properties.
| [DOSKEY]      | Edits command lines, recalls Windows commands, and creates macros.
| [DRIVERQUERY] | Displays current device driver status and properties.
| [ECHO]        | Displays messages, or turns command echoing on or off.
| [ENDLOCAL]    | Ends localization of environment changes in a batch file.
| [ERASE]       | Deletes one or more files.
| [EXIT]        | Quits the CMD.EXE program (command interpreter).
| [FC]          | Compares two files or sets of files, and displays the differences between them.
| [FIND]        | Searches for a text string in a file or files.
| [FINDSTR]     | Searches for strings in files.
| [FOR]         | Runs a specified command for each file in a set of files.
| [FORMAT]      | Formats a disk for use with Windows.
| [FSUTIL]      | Displays or configures the file system properties.
| [FTYPE]       | Displays or modifies file types used in file extension associations.
| [GOTO]        | Directs the Windows command interpreter to a labeled line in a batch program.
| [GPRESULT]    | Displays Group Policy information for machine or user.
| [HELP]        | Provides Help information for Windows commands.
| [ICACLS]      | Display, modify, backup, or restore ACLs for files and directories.
| [IF]          | Performs conditional processing in batch programs.
| [LABEL]       | Creates, changes, or deletes the volume label of a disk.
| [MD]          | Creates a directory.
| [MKDIR]       | Creates a directory.
| [MKLINK]      | Creates Symbolic Links and Hard Links
| [MODE]        | Configures a system device.
| [MORE]        | Displays output one screen at a time.
| [MOVE]        | Moves one or more files from one directory to another directory.
| [OPENFILES]   | Displays files opened by remote users for a file share.
| [PATH]        | Displays or sets a search path for executable files.
| [PAUSE]       | Suspends processing of a batch file and displays a message.
| [POPD]        | Restores the previous value of the current directory saved by PUSHD.
| [PRINT]       | Prints a text file.
| [PROMPT]      | Changes the Windows command prompt.
| [PUSHD]       | Saves the current directory then changes it.
| [RD]          | Removes a directory.
| [RECOVER]     | Recovers readable information from a bad or defective disk.
| [REM]         | Records comments (remarks) in batch files or CONFIG.SYS.
| [REN]         | Renames a file or files.
| [RENAME]      | Renames a file or files.
| [REPLACE]     | Replaces files.
| [RMDIR]       | Removes a directory.
| [ROBOCOPY]    | Advanced utility to copy files and directory trees
| [SET]         | Displays, sets, or removes Windows environment variables.
| [SETLOCAL]    | Begins localization of environment changes in a batch file.
| [SC]          | Displays or configures services (background processes).
| [SCHTASKS]    | Schedules commands and programs to run on a computer.
| [SHIFT]       | Shifts the position of replaceable parameters in batch files.
| [SHUTDOWN]    | Allows proper local or remote shutdown of machine.
| [SORT]        | Sorts input.
| [START]       | Starts a separate window to run a specified program or command.
| [SUBST]       | Associates a path with a drive letter.
| [SYSTEMINFO]  | Displays machine specific properties and configuration.
| [TASKLIST]    | Displays all currently running tasks including services.
| [TASKKILL]    | Kill or stop a running process or application.
| [TIME]        | Displays or sets the system time.
| [TITLE]       | Sets the window title for a CMD.EXE session.
| [TREE]        | Graphically displays the directory structure of a drive or path.
| [TYPE]        | Displays the contents of a text file.
| [VER]         | Displays the Windows version.
| [VERIFY]      | Tells Windows whether to verify that your files are written correctly to a disk.
| [VOL]         | Displays a disk volume label and serial number.
| [XCOPY]       | Copies files and directory trees.
| [WMIC]        | Displays WMI information inside interactive command shell.

[ASSOC]: Command/ASSOC
[ATTRIB]: Command/ATTRIB
[BREAK]: Command/BREAK
[BCDEDIT]: Command/BCDEDIT
[CACLS]: Command/CACLS
[CALL]: Command/CALL
[CD]: Command/CD
[CHCP]: Command/CHCP
[CHDIR]: Command/CHDIR
[CHKDSK]: Command/CHKDSK
[CHKNTFS]: Command/CHKNTFS
[CLS]: Command/CLS
[CMD]: Command/CMD
[COLOR]: Command/COLOR
[COMP]: Command/COMP
[COMPACT]: Command/COMPACT
[CONVERT]: Command/CONVERT
[COPY]: Command/COPY
[DATE]: Command/DATE
[DEL]: Command/DEL
[DIR]: Command/DIR
[DISKCOMP]: Command/DISKCOMP
[DISKCOPY]: Command/DISKCOPY
[DISKPART]: Command/DISKPART
[DOSKEY]: Command/DOSKEY
[DRIVERQUERY]: Command/DRIVERQUERY
[ECHO]: Command/ECHO
[ENDLOCAL]: Command/ENDLOCAL
[ERASE]: Command/ERASE
[EXIT]: Command/EXIT
[FC]: Command/FC
[FIND]: Command/FIND
[FINDSTR]: Command/FINDSTR
[FOR]: Command/FOR
[FORMAT]: Command/FORMAT
[FSUTIL]: Command/FSUTIL
[FTYPE]: Command/FTYPE
[GOTO]: Command/GOTO
[GPRESULT]: Command/GPRESULT
[HELP]: Command/HELP
[ICACLS]: Command/ICACLS
[IF]: Command/IF
[LABEL]: Command/LABEL
[MD]: Command/MD
[MKDIR]: Command/MKDIR
[MKLINK]: Command/MKLINK
[MODE]: Command/MODE
[MORE]: Command/MORE
[MOVE]: Command/MOVE
[OPENFILES]: Command/OPENFILES
[PATH]: Command/PATH
[PAUSE]: Command/PAUSE
[POPD]: Command/POPD
[PRINT]: Command/PRINT
[PROMPT]: Command/PROMPT
[PUSHD]: Command/PUSHD
[RD]: Command/RD
[RECOVER]: Command/RECOVER
[REM]: Command/REM
[REN]: Command/REN
[RENAME]: Command/RENAME
[REPLACE]: Command/REPLACE
[RMDIR]: Command/RMDIR
[ROBOCOPY]: Command/ROBOCOPY
[SET]: Command/SET
[SETLOCAL]: Command/SETLOCAL
[SC]: Command/SC
[SCHTASKS]: Command/SCHTASKS
[SHIFT]: Command/SHIFT
[SHUTDOWN]: Command/SHUTDOWN
[SORT]: Command/SORT
[START]: Command/START
[SUBST]: Command/SUBST
[SYSTEMINFO]: Command/SYSTEMINFO
[TASKLIST]: Command/TASKLIST
[TASKKILL]: Command/TASKKILL
[TIME]: Command/TIME
[TITLE]: Command/TITLE
[TREE]: Command/TREE
[TYPE]: Command/TYPE
[VER]: Command/VER
[VERIFY]: Command/VERIFY
[VOL]: Command/VOL
[XCOPY]: Command/XCOPY
[WMIC]: Command/WMIC
