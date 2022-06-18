# Batch

中文 | [English](en_US/README.md)

Batch 帮助文档。

## 生成

可在 CMD 程序中执行下面的命令生成文档。

```Batch
help > temp_File

grep -oE "^[A-Z]*" temp_File > filter_File

for /f %i in (filter_File) do cmd /c %i /? > zh_CN\%i

del /q temp_File && del /q filter_File
```

**注：**

`GRAFTABL` 命令的帮助文档生成失败。

## 引索

| 命令          | 描述                                   |
|:--------------|:---------------------------------------|
| [ASSOC]       | 显示或修改文件扩展名关联。 |
| [ATTRIB]      | 显示或更改文件属性。 |
| [BREAK]       | 设置或清除扩展式 CTRL+C 检查。 |
| [BCDEDIT]     | 设置启动数据库中的属性以控制启动加载。 |
| [CACLS]       | 显示或修改文件的访问控制列表(ACL)。 |
| [CALL]        | 从另一个批处理程序调用这一个。 |
| [CD]          | 显示当前目录的名称或将其更改。 |
| [CHCP]        | 显示或设置活动代码页数。 |
| [CHDIR]       | 显示当前目录的名称或将其更改。 |
| [CHKDSK]      | 检查磁盘并显示状态报告。 |
| [CHKNTFS]     | 显示或修改启动时间磁盘检查。 |
| [CLS]         | 清除屏幕。 |
| [CMD]         | 打开另一个 Windows 命令解释程序窗口。 |
| [COLOR]       | 设置默认控制台前景和背景颜色。 |
| [COMP]        | 比较两个或两套文件的内容。 |
| [COMPACT]     | 显示或更改 NTFS 分区上文件的压缩。 |
| [CONVERT]     | 将 FAT 卷转换成 NTFS。您不能转换当前驱动器。 |
| [COPY]        | 将至少一个文件复制到另一个位置。 |
| [DATE]        | 显示或设置日期。 |
| [DEL]         | 删除至少一个文件。 |
| [DIR]         | 显示一个目录中的文件和子目录。 |
| [DISKCOMP]    | 比较两个软盘的内容。 |
| [DISKCOPY]    | 将一个软盘的内容复制到另一个软盘。 |
| [DISKPART]    | 显示或配置磁盘分区属性。 |
| [DOSKEY]      | 编辑命令行、调用 Windows 命令并创建宏。 |
| [DRIVERQUERY] | 显示当前设备驱动程序状态和属性。 |
| [ECHO]        | 显示消息，或将命令回显打开或关上。 |
| [ENDLOCAL]    | 结束批文件中环境更改的本地化。 |
| [ERASE]       | 删除一个或多个文件。 |
| [EXIT]        | 退出 CMD.EXE 程序(命令解释程序)。 |
| [FC]          | 比较两个文件或两个文件集并显示它们之间的不同。 |
| [FIND]        | 在一个或多个文件中搜索一个文本字符串。 |
| [FINDSTR]     | 在多个文件中搜索字符串。 |
| [FOR]         | 为一套文件中的每个文件运行一个指定的命令。 |
| [FORMAT]      | 格式化磁盘，以便跟 Windows 使用。 |
| [FSUTIL]      | 显示或配置文件系统的属性。 |
| [FTYPE]       | 显示或修改用在文件扩展名关联的文件类型。 |
| [GOTO]        | 将 Windows 命令解释程序指向批处理程序中某个带标签的行。 |
| [GPRESULT]    | 显示机器或用户的组策略信息。 |
| [HELP]        | 提供 Windows 命令的帮助信息。 |
| [ICACLS]      | 显示、修改、备份或还原文件和目录的 ACL。 |
| [IF]          | 在批处理程序中执行有条件的处理过程。 |
| [LABEL]       | 创建、更改或删除磁盘的卷标。 |
| [MD]          | 创建一个目录。 |
| [MKDIR]       | 创建一个目录。 |
| [MKLINK]      | 创建符号链接和硬链接 |
| [MODE]        | 配置系统设备。 |
| [MORE]        | 逐屏显示输出。 |
| [MOVE]        | 将一个或多个文件从一个目录移动到另一个目录。 |
| [OPENFILES]   | 显示远程用户为了文件共享而打开的文件。 |
| [PATH]        | 为可执行文件显示或设置搜索路径。 |
| [PAUSE]       | 停止批处理文件的处理并显示信息。 |
| [POPD]        | 还原由 PUSHD 保存的当前目录上一次的值。 |
| [PRINT]       | 打印一个文本文件。 |
| [PROMPT]      | 改变 Windows 命令提示。 |
| [PUSHD]       | 保存当前目录，然后对其进行更改。 |
| [RD]          | 删除目录。 |
| [RECOVER]     | 从损坏的磁盘中恢复可读取的信息。 |
| [REM]         | 记录批处理文件或 CONFIG.SYS 中的注释。 |
| [REN]         | 重新命名文件。 |
| [RENAME]      | 重新命名文件。 |
| [REPLACE]     | 替换文件。 |
| [RMDIR]       | 删除目录。 |
| [ROBOCOPY]    | 复制文件和目录树的高级实用程序 |
| [SET]         | 显示、设置或删除 Windows 环境变量。 |
| [SETLOCAL]    | 开始用批文件改变环境的本地化。 |
| [SC]          | 显示或配置服务(后台处理)。 |
| [SCHTASKS]    | 安排命令和程序在一部计算机上按计划运行。 |
| [SHIFT]       | 调整批处理文件中可替换参数的位置。 |
| [SHUTDOWN]    | 让机器在本地或远程正确关闭。 |
| [SORT]        | 将输入排序。 |
| [START]       | 打开单独视窗运行指定程序或命令。 |
| [SUBST]       | 将驱动器号与路径关联。 |
| [SYSTEMINFO]  | 显示机器的具体的属性和配置。 |
| [TASKLIST]    | 显示包括服务的所有当前运行的任务。 |
| [TASKKILL]    | 终止正在运行的进程或应用程序。 |
| [TIME]        | 显示或设置系统时间。 |
| [TITLE]       | 设置 CMD.EXE 会话的窗口标题。 |
| [TREE]        | 以图形显示启动器或路径的目录结构。 |
| [TYPE]        | 显示文本文件的内容。 |
| [VER]         | 显示 Windows 的版本。 |
| [VERIFY]      | 告诉 Windows 验证文件是否正确写入磁盘。 |
| [VOL]         | 显示磁盘卷标和序列号。 |
| [XCOPY]       | 复制文件和目录树。 |
| [WMIC]        | 在交互命令外壳里显示 WMI 信息。 |

[ASSOC]: zh_CN/Command/ASSOC
[ATTRIB]: zh_CN/Command/ATTRIB
[BREAK]: zh_CN/Command/BREAK
[BCDEDIT]: zh_CN/Command/BCDEDIT
[CACLS]: zh_CN/Command/CACLS
[CALL]: zh_CN/Command/CALL
[CD]: zh_CN/Command/CD
[CHCP]: zh_CN/Command/CHCP
[CHDIR]: zh_CN/Command/CHDIR
[CHKDSK]: zh_CN/Command/CHKDSK
[CHKNTFS]: zh_CN/Command/CHKNTFS
[CLS]: zh_CN/Command/CLS
[CMD]: zh_CN/Command/CMD
[COLOR]: zh_CN/Command/COLOR
[COMP]: zh_CN/Command/COMP
[COMPACT]: zh_CN/Command/COMPACT
[CONVERT]: zh_CN/Command/CONVERT
[COPY]: zh_CN/Command/COPY
[DATE]: zh_CN/Command/DATE
[DEL]: zh_CN/Command/DEL
[DIR]: zh_CN/Command/DIR
[DISKCOMP]: zh_CN/Command/DISKCOMP
[DISKCOPY]: zh_CN/Command/DISKCOPY
[DISKPART]: zh_CN/Command/DISKPART
[DOSKEY]: zh_CN/Command/DOSKEY
[DRIVERQUERY]: zh_CN/Command/DRIVERQUERY
[ECHO]: zh_CN/Command/ECHO
[ENDLOCAL]: zh_CN/Command/ENDLOCAL
[ERASE]: zh_CN/Command/ERASE
[EXIT]: zh_CN/Command/EXIT
[FC]: zh_CN/Command/FC
[FIND]: zh_CN/Command/FIND
[FINDSTR]: zh_CN/Command/FINDSTR
[FOR]: zh_CN/Command/FOR
[FORMAT]: zh_CN/Command/FORMAT
[FSUTIL]: zh_CN/Command/FSUTIL
[FTYPE]: zh_CN/Command/FTYPE
[GOTO]: zh_CN/Command/GOTO
[GPRESULT]: zh_CN/Command/GPRESULT
[HELP]: zh_CN/Command/HELP
[ICACLS]: zh_CN/Command/ICACLS
[IF]: zh_CN/Command/IF
[LABEL]: zh_CN/Command/LABEL
[MD]: zh_CN/Command/MD
[MKDIR]: zh_CN/Command/MKDIR
[MKLINK]: zh_CN/Command/MKLINK
[MODE]: zh_CN/Command/MODE
[MORE]: zh_CN/Command/MORE
[MOVE]: zh_CN/Command/MOVE
[OPENFILES]: zh_CN/Command/OPENFILES
[PATH]: zh_CN/Command/PATH
[PAUSE]: zh_CN/Command/PAUSE
[POPD]: zh_CN/Command/POPD
[PRINT]: zh_CN/Command/PRINT
[PROMPT]: zh_CN/Command/PROMPT
[PUSHD]: zh_CN/Command/PUSHD
[RD]: zh_CN/Command/RD
[RECOVER]: zh_CN/Command/RECOVER
[REM]: zh_CN/Command/REM
[REN]: zh_CN/Command/REN
[RENAME]: zh_CN/Command/RENAME
[REPLACE]: zh_CN/Command/REPLACE
[RMDIR]: zh_CN/Command/RMDIR
[ROBOCOPY]: zh_CN/Command/ROBOCOPY
[SET]: zh_CN/Command/SET
[SETLOCAL]: zh_CN/Command/SETLOCAL
[SC]: zh_CN/Command/SC
[SCHTASKS]: zh_CN/Command/SCHTASKS
[SHIFT]: zh_CN/Command/SHIFT
[SHUTDOWN]: zh_CN/Command/SHUTDOWN
[SORT]: zh_CN/Command/SORT
[START]: zh_CN/Command/START
[SUBST]: zh_CN/Command/SUBST
[SYSTEMINFO]: zh_CN/Command/SYSTEMINFO
[TASKLIST]: zh_CN/Command/TASKLIST
[TASKKILL]: zh_CN/Command/TASKKILL
[TIME]: zh_CN/Command/TIME
[TITLE]: zh_CN/Command/TITLE
[TREE]: zh_CN/Command/TREE
[TYPE]: zh_CN/Command/TYPE
[VER]: zh_CN/Command/VER
[VERIFY]: zh_CN/Command/VERIFY
[VOL]: zh_CN/Command/VOL
[XCOPY]: zh_CN/Command/XCOPY
[WMIC]: zh_CN/Command/WMIC
