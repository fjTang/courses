1. 将**git-completion.bash**和**git-prompt.sh**放置在当前的用户目录下；
2. 将**bash_profile_course**中的内容添加到用户目录下的.bash_profile文件末尾；
3. 关联Git中的编辑器
```bash
git config --global core.editor "'C:/Program Files (x86)/Sublime Text 3/sublime_text.exe' -n -w"
git config --global push.default upstream
git config --global merge.conflictstyle diff3
```
如果要关联其它编辑器，可见[这里](https://help.github.com/articles/associating-text-editors-with-git/).

4. 确保可从 Git Bash 启动编辑器, 如果你使用 Sublime Text，则可通过将以下一行添加到.bash_profile中来这样做：
```bash
alias subl="C:/Program\ Files\ \(x86\)/Sublime\ Text\ 3/sublime_text.exe"
```
5. 重启Git Bash即可使用。
