# 一、命令行窗口(小黑屏、CMD窗口、终端、shell)
```
  - 开始菜单 - 运行 - CMD - 回车
  - win+r - CMD - 回车
  - ---------------------------------
  - 常用的指令
    dir         列出当前目录下所有的文件
    cd 目录名   进入到指定的目录
    md 目录名   创建一个文件夹
    rd 目录名   删除一个文件夹

  - 目录
    .           表示当前目录
    ..          表示上一级目录

  - 环境变量（windows系统中变量）
    path
      C:\Program Files (x86)\SSH Communications Security\SSH Secure Shell;C:\Users\Administrator\AppData\Local\Programs\Microsoft VS Code\bin;
      C:\Program Files (x86)\cmder;C:\Users\Administrator\AppData\Roaming\npm;C:\Program Files\MongoDB\Server\4.2\bin;C:\Users\Administrator\Downloads\ffmpeg-4.4-full_build\bin;

      添加：
      C:\Users\Administrator\Desktop\hello
    - 当我们在命令行窗口打开一个文件，或调用一个程序时，系统会首先在当前目录下寻找文件程序，
    如果找到了则直接打开;
    如果没找到则会一次到环境变量path的路径中寻找，直到找到为止
    如果还没找到，则报错
    - 所以我们可以将一些经常需要访问的程序和文件的路径添加到path中，这样我们就可以在任意位置来访问这些文件和程序了
```


