# backup-tool

文件备份小工具，将某文件夹中的文件备份到目标文件夹中，控制台程序。

usage:
    backup srcDir dstDir [/?] [/help] [/c] [/C] [/a] [/A] [/!=] [/>]
    
      /? or /help: 帮助
	  /c or /C:    遍历子文件夹，默认忽略子文件夹
	  /a or /A:    全部复制，不比较文件的修改时间，默认小于则复制
	  /!=:         比较文件的修改时间，两者不相等则复制, 默认小于则复制
	  "/>:          比较文件的修改时间，如果目标文件的修改时间小于源文件则复制，默认此项
