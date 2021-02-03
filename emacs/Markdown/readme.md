# emacs中配置markdown-mode

## 参考资料 ##

1. [Markdown Mode for Emacs](https://jblevins.org/projects/markdown-mode/)

## 配置步骤 ##

1. 新建文件~/.emacs.d/init.el;
2. 在文件init.el中输入一下代码：

   ```
   (require 'package)
   (add-to-list 'package-archives
	            '("melpa-stable" . "https://stable.melpa.org/packages/"))
   (package-initialize)
   ```
   
3. 在emacs中输入`M-x package-install RET markdown-mode RET`;注意“RET”代表的是回车；
4. 在步骤3中按下回车后会出现443状态码，不要担心，这是emacs在自动下载相关东西；
5. C-c C-c p:在浏览器中预览。

## 简单快捷键 ##


