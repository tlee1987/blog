## Python文件操作过程中换行符的知识梳理
- 换行符
    - CR: 回车(Carriage Return) \r
    - LF: 换行(Line Feed) \n

- 目前主流的三种操作系统的换行符：
    - Windows:      \r\n
    - Unix\Linux:   \n
    - Mac OSX:      \r

- Python中是以\n 作为换行符的
    - Python在Window系统下用文本模式读取文件时，会将\r\n 默认转换为 \n;在文本模式下写入文件时，会将\n 转换为\r\n
    - 当以二进制模式读取文件时，是不会进行自动转换的
    - 在Unix\Linux 系统下不会发生转换
    