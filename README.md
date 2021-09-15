# Batch

中文 | [English](en_US/README.md)

一份 Batch 帮助文档。

## 生成

可在 CMD 程序中执行下面的命令生成文档。

```Batch
help > temp_File

grep -o -E "^[A-Z]*" temp_File > filter_File

for /f %i in (filter_File) do cmd /c %i /? > Command\%i

del /q temp_File && del /q filter_File
```

## 引索

|     命令     |     描述     |
| :----------- | :----------- |
| [ASSOC](zh_CN/Command/ASSOC) |  显示或修改文件扩展名关联。 |
| [ATTRIB](zh_CN/Command/ATTRIB) |  显示或更改文件属性。 |
| [BREAK](zh_CN/Command/BREAK) |  设置或清除扩展式 CTRL+C 检查。 |
| [BCDEDIT](zh_CN/Command/BCDEDIT) |  设置启动数据库中的属性以控制启动加载。 |
| [CACLS](zh_CN/Command/CACLS) |  显示或修改文件的访问控制列表(ACL)。 |
| [CALL](zh_CN/Command/CALL) |  从另一个批处理程序调用这一个。 |
| [CD](zh_CN/Command/CD) |  显示当前目录的名称或将其更改。 |
| [CHCP](zh_CN/Command/CHCP) |  显示或设置活动代码页数。 |
| [CHDIR](zh_CN/Command/CHDIR) |  显示当前目录的名称或将其更改。 |
| [CHKDSK](zh_CN/Command/CHKDSK) |  检查磁盘并显示状态报告。 |
| [CHKNTFS](zh_CN/Command/CHKNTFS) |  显示或修改启动时间磁盘检查。 |
| [CLS](zh_CN/Command/CLS) |  清除屏幕。 |
| [CMD](zh_CN/Command/CMD) |  打开另一个 Windows 命令解释程序窗口。 |
| [COLOR](zh_CN/Command/COLOR) |  设置默认控制台前景和背景颜色。 |
| [COMP](zh_CN/Command/COMP) |  比较两个或两套文件的内容。 |
| [COMPACT](zh_CN/Command/COMPACT) |  显示或更改 NTFS 分区上文件的压缩。 |
| [CONVERT](zh_CN/Command/CONVERT) |  将 FAT 卷转换成 NTFS。你不能转换当前驱动器。 |
| [COPY](zh_CN/Command/COPY) |  将至少一个文件复制到另一个位置。 |
| [DATE](zh_CN/Command/DATE) |  显示或设置日期。 |
| [DEL](zh_CN/Command/DEL) |  删除至少一个文件。 |
| [DIR](zh_CN/Command/DIR) |  显示一个目录中的文件和子目录。 |
| [DISKPART](zh_CN/Command/DISKPART) |  显示或配置磁盘分区属性。 |
| [DOSKEY](zh_CN/Command/DOSKEY) |  编辑命令行、撤回 Windows 命令并创建宏。 |
| [DRIVERQUERY](zh_CN/Command/DRIVERQUERY) |  显示当前设备驱动程序状态和属性。 |
| [ECHO](zh_CN/Command/ECHO) |  显示消息，或将命令回显打开或关闭。 |
| [ENDLOCAL](zh_CN/Command/ENDLOCAL) |  结束批文件中环境更改的本地化。 |
| [ERASE](zh_CN/Command/ERASE) |  删除一个或多个文件。 |
| [EXIT](zh_CN/Command/EXIT) |  退出 CMD.EXE 程序(命令解释程序)。 |
| [FC](zh_CN/Command/FC) |  比较两个文件或两个文件集并显示它们之间的不同。 |
| [FIND](zh_CN/Command/FIND) |  在一个或多个文件中搜索一个文本字符串。 |
| [FINDSTR](zh_CN/Command/FINDSTR) |  在多个文件中搜索字符串。 |
| [FOR](zh_CN/Command/FOR) |  为一组文件中的每个文件运行一个指定的命令。 |
| [FORMAT](zh_CN/Command/FORMAT) |  格式化磁盘，以便用于 Windows。 |
| [FSUTIL](zh_CN/Command/FSUTIL) |  显示或配置文件系统属性。 |
| [FTYPE](zh_CN/Command/FTYPE) |  显示或修改在文件扩展名关联中使用的文件类型。 |
| [GOTO](zh_CN/Command/GOTO) |  将 Windows 命令解释程序定向到批处理程序中某个带标签的行。 |
| [GPRESULT](zh_CN/Command/GPRESULT) |  显示计算机或用户的组策略信息。 |
| [GRAFTABL](zh_CN/Command/GRAFTABL) |  使 Windows 在图形模式下显示扩展字符集。 |
| [HELP](zh_CN/Command/HELP) |  提供 Windows 命令的帮助信息。 |
| [ICACLS](zh_CN/Command/ICACLS) |  显示、修改、备份或还原文件和目录的 ACL。 |
| [IF](zh_CN/Command/IF) |  在批处理程序中执行有条件的处理操作。 |
| [LABEL](zh_CN/Command/LABEL) |  创建、更改或删除磁盘的卷标。 |
| [MD](zh_CN/Command/MD) |  创建一个目录。 |
| [MKDIR](zh_CN/Command/MKDIR) |  创建一个目录。 |
| [MKLINK](zh_CN/Command/MKLINK) |  创建符号链接和硬链接 |
| [MODE](zh_CN/Command/MODE) |  配置系统设备。 |
| [MORE](zh_CN/Command/MORE) |  逐屏显示输出。 |
| [MOVE](zh_CN/Command/MOVE) |  将一个或多个文件从一个目录移动到另一个目录。 |
| [OPENFILES](zh_CN/Command/OPENFILES) |  显示远程用户为了文件共享而打开的文件。 |
| [PATH](zh_CN/Command/PATH) |  为可执行文件显示或设置搜索路径。 |
| [PAUSE](zh_CN/Command/PAUSE) |  暂停批处理文件的处理并显示消息。 |
| [POPD](zh_CN/Command/POPD) |  还原通过 PUSHD 保存的当前目录的上一个值。 |
| [PRINT](zh_CN/Command/PRINT) |  打印一个文本文件。 |
| [PROMPT](zh_CN/Command/PROMPT) |  更改 Windows 命令提示。 |
| [PUSHD](zh_CN/Command/PUSHD) |  保存当前目录，然后对其进行更改。 |
| [RD](zh_CN/Command/RD) |  删除目录。 |
| [RECOVER](zh_CN/Command/RECOVER) |  从损坏的或有缺陷的磁盘中恢复可读信息。 |
| [REM](zh_CN/Command/REM) |  记录批处理文件或 CONFIG.SYS 中的注释(批注)。 |
| [REN](zh_CN/Command/REN) |  重命名文件。 |
| [RENAME](zh_CN/Command/RENAME) |  重命名文件。 |
| [REPLACE](zh_CN/Command/REPLACE) |  替换文件。 |
| [RMDIR](zh_CN/Command/RMDIR) |  删除目录。 |
| [ROBOCOPY](zh_CN/Command/ROBOCOPY) |  复制文件和目录树的高级实用工具 |
| [SET](zh_CN/Command/SET) |  显示、设置或删除 Windows 环境变量。 |
| [SETLOCAL](zh_CN/Command/SETLOCAL) |  开始本地化批处理文件中的环境更改。 |
| [SC](zh_CN/Command/SC) |  显示或配置服务(后台进程)。 |
| [SCHTASKS](zh_CN/Command/SCHTASKS) |  安排在一台计算机上运行命令和程序。 |
| [SHIFT](zh_CN/Command/SHIFT) |  调整批处理文件中可替换参数的位置。 |
| [SHUTDOWN](zh_CN/Command/SHUTDOWN) |  允许通过本地或远程方式正确关闭计算机。 |
| [SORT](zh_CN/Command/SORT) |  对输入排序。 |
| [START](zh_CN/Command/START) |  启动单独的窗口以运行指定的程序或命令。 |
| [SUBST](zh_CN/Command/SUBST) |  将路径与驱动器号关联。 |
| [SYSTEMINFO](zh_CN/Command/SYSTEMINFO) |  显示计算机的特定属性和配置。 |
| [TASKLIST](zh_CN/Command/TASKLIST) |  显示包括服务在内的所有当前运行的任务。 |
| [TASKKILL](zh_CN/Command/TASKKILL) |  中止或停止正在运行的进程或应用程序。 |
| [TIME](zh_CN/Command/TIME) |  显示或设置系统时间。 |
| [TITLE](zh_CN/Command/TITLE) |  设置 CMD.EXE 会话的窗口标题。 |
| [TREE](zh_CN/Command/TREE) |  以图形方式显示驱动程序或路径的目录结构。 |
| [TYPE](zh_CN/Command/TYPE) |  显示文本文件的内容。 |
| [VER](zh_CN/Command/VER) |  显示 Windows 的版本。 |
| [VERIFY](zh_CN/Command/VERIFY) |  告诉 Windows 是否进行验证，以确保文件正确写入磁盘。 |
| [VOL](zh_CN/Command/VOL) |  显示磁盘卷标和序列号。 |
| [XCOPY](zh_CN/Command/XCOPY) |  复制文件和目录树。 |
| [WMIC](zh_CN/Command/WMIC) |  在交互式命令 shell 中显示 WMI 信息。 |
