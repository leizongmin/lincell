# LinCell 
[![Build Status](https://travis-ci.org/sumory/lincell.png?branch=master)](https://travis-ci.org/sumory/lincell)

**LinCell** [List all in Cell] 是一个编辑器, 只需执行一条命令即可将文件夹变成一个工作空间.

## 介绍

LinCell是用 **Node.js** 开发的轻型文件编辑器(也可以作为简单的IDE使用). 它有以下特性(包括change log)：

* 编辑器自定义(目前支持自定义tab宽度)
* 目录树添加右键操作支持
* 多tab页显示文件
* 对文件夹或文件的CRUD操作
* 基于ACE Editor，支持各种文件的预览和编辑(修复输入中文时的Bug)
* 移除自动保存，使用Ctrl + S 手动保存文件更改、可自定义快捷键(基于Kibo)
* 文件夹、文件查询(按名称)

![lincell](https://raw.github.com/sumory/lincell/master/examples/lincell.png)


## 安装

```bash
$ npm install -g lincell
```

## 使用

    Usage: lincell [options]

    Options:

      -h, --help           output usage information
      -V, --version        output the version number
      -p, --port <number>  use a custom http port(default port is 8222)
      -d, --dir <string>   use a custom path to show(default is current path)

    Examples:

      lincell                          # use default port and current path
      lincell -p 9234                  # custom port
      lincell -d /home/sumory          # custom path
      lincell -p 8726 -d /home/sumory  # absolute path is supported
      lincell -p 8843 -d ../path       # relative path is also supported


## Contributors

    $ git summary

     project  : lincell
     repo age : 7 weeks
     active   : 9 days
     commits  : 20
     files    : 210
     authors  :
        16  sumory                  80.0%
         2  午夜                    10.0%
         1  Zongmin Lei             5.0%
         1  william                 5.0%


## License

LinCell is released under a **MIT License**:

    Copyright (C) 2013 by Sumory Wu <sumory.wu@gmail.com>

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.