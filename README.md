# Nidalee（vscode plugin）

> - Nidalee(LOL狂野女猎手)，她人类形态的W技能（丛林伏击）使得陷阱呈隐形状态。
> - `console`打印日志方便前端定位问题，但前端小学生编程时滥用`console debug`大法。
> - 滥用就是隐藏的陷阱。

## Features

✨ 为所选择代码段添加`console`

- 快捷键 `windows: ctr+l` `mac: command+shift+l`
- 插入到下一行 `obj.i`
- 替换当前选中字符 `obj.r`
- 打印代码耗时 `obj.t`

✨ 删除当前页面所有`console`

- 在当前页面点击右键选择`Delete All Logs`
  ```js
  const logRegexp = /console.(log|debug|info|warn|error|assert|dir|dirxml|trace|group|groupEnd|time|timeEnd|profile|profileEnd|count)\((.*)\);?/g;
  ```

## ChangeLog

### 0.3.0

- ✨  删除当前页面所有`console`

### 0.2.0

- ✨  为所选择代码段添加`console`
