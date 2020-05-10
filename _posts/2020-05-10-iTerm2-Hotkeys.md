---
layout: post
---



> Last Update: 05/10/2020
>
> Note: 不太常用的注释掉了，不定时更新



### CTRL

```bash
光标移至行首 : ctrl + A
光标移至行末 : ctrl + E
# 光标左移 : ctrl + B
# 光标右移 : ctrl + F

删除光标前的单个字符 : ctrl + H
删除光标位置单个字符 : ctrl + D
删除当前行 : ctrl + U
删除到文本末尾 : ctrl + K
删除光标前的单词 : ctrl + W
# 交换光标位置字符和前一字符 : ctrl + T

撤回操作 : ctrl + -
搜索之前用过的命令 : ctrl + R
# 粘贴上次剪切的命令 : ctrl + Y
# 上/下翻之前用过的命令 : ctrl + P/N
```



### ALT

```bash
https://paradisehell.org/2019/04/26/how-to-use-command-line-well/
https://yugasun.com/post/iterm2-shortcut-key.html
https://cnbin.github.io/blog/2015/06/20/iterm2-kuai-jie-jian-da-quan/
```



```bash
# 错误信息
/System/Library/Frameworks/Ruby.framework/Versions/2.6/usr/lib/ruby/2.6.0/logger.rb:227: warning: already initialized constant Logger::VERSION
/Library/Ruby/Gems/2.6.0/gems/logger-1.4.2/lib/logger/version.rb:4: warning: previous definition of VERSION was here
# 解决办法
$ gem uninstall fileutils
$ gem update --default

$ gem list | grep strscan
> strscan (1.0.3, default: 1.0.0)

在 Gemfile 添加版本要求

# 设为原来的 default
$ gem list | grep logger
> logger (default: 1.4.2, default: 1.3.0)
# 删除 /Library/Ruby/Gems/2.6.0/specifications/default/ 下对应的 1.4.2 版本
$ gem update
$ gem list | grep logger
> logger (1.4.2, default: 1.3.0)
```



> // TODO
>
> // 分成两篇