# 可以在windows10 下 CMD 命令终端运行的文本查找工具

---

## 包含如下工具套件

- [fzf](https://github.com/junegunn/fzf.git) 是一个通用的命令行模糊查找器。
- [grep for windows](http://gnuwin32.sourceforge.net/packages/grep.htm)在一个或多个输入文件中搜索包含与指定模式匹配的行
- [Ag](https://github.com/ggreer/the_silver_searcher
)类似于 ack 的代码搜索工具，但速度更快。
- [Ack](https://github.com/petdance/ack3) - 比 grep 更好。没有 Ack，Ag 就不会存在。
- [Rg [ripgrep](https://github.com/BurntSushi/ripgrep)](https://github.com/BurntSushi/ripgrep/releases/tag/12.1.1)  是一个面向行的搜索工具，它递归地搜索当前目录以查找正则表达式模式可替代grep的工具
- [VIM](https://www.vim.org/) 文件编辑器
- [bat](https://github.com/sharkdp/bat) 比cat 更好用. bat 支持大量编程和标记语言的语法高亮

```bash
sudo apt-get install fzf fzy silversearcher-ag ripgrep
```
---

- [ack.vim](https://github.com/mileszs/ack.vim)
- [Exuberant Ctags](http://ctags.sourceforge.net/) - 比 Ag 快，但它事先建立了索引。适用于*非常*大的代码库。
- [Git-grep](http://git-scm.com/docs/git-grep) - 与 Ag 一样快，但仅适用于 git 存储库。
- [Sack](https://github.com/sampson-chen/sack) - 包装 Ack 和 Ag 的实用程序。它消除了搜索和打开匹配文件的大量重复。

>> 对提供如上软件工具的开发及维护者表示感谢!
>> 此仓库仅自用
