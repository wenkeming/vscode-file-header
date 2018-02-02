# vscode-file-header

inspired by [vscode-headerfile](https://github.com/zhaopengme/vscode-fileheader)

基于 [vscode-headerfile](https://github.com/zhaopengme/vscode-fileheader) 修改

## feature

Add notes to the file header, and supports automatic update file modification time.

eg:

```
/*
 * @Author: Kevin
 * @Date: 2018-02-02 13:10:43
 * @Last Modified by: Kevin
 * @Last Modified time: 2018-02-02 13:12:08
 */
```

![fileheader](https://github.com/zhaopengme/vscode-fileheader/raw/master/fileheader.gif)

> Tip: ctrl+alt+i You can insert comments in the head, ctrl+s After you save the file, and automatically update the time and author.

## install 安装

Open Visual Studio Code

Press `Ctrl+P` or `F1` to open the Quick Open dialog

Type `ext install vscode-file-header` to find the extension

Click the `Install` button, then the `Enable` button

&nbsp;

OR

&nbsp;

Press `Ctrl+Shift+X` to open the Extensions tab

Type `vscode-file-header` to find the extension

Click the `Install` button, then the `Enable` button

## Configuration 配置

In the User Settings inside, set and modify the creator's name.

```
"fileheader.Author": "tom",
"fileheader.LastModifiedBy": "jerry"
```

![name config](https://github.com/zhaopengme/vscode-fileheader/raw/master/name.jpg)

## Hotkey 热键

`ctrl+alt+i` You can insert comments in the head. 插入信息到文件头部

## Change log 更新日志

### 1.0.0

1. Support hotkey insert header comments 支持快捷键插入
2. Support Save file, automatically update the time 支持保存文件时自动更新时间
3. Support the configuration and update the creator's name 支持配置更新人和创建者名字
