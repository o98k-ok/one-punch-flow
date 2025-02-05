# one-punch

一个命令行工具，用于快速执行一些常用的命令。

## 安装

```bash
go install github.com/o98k-ok/one-punch@latest
```

## 编辑

```bash
one-punch edit "key: value"

one-punch edit "自定义命令: http://baidu.com"
```

## 搜索

```bash
one-punch search "自定义命令"

one-punch search "zdy"
```

# alfred workflow

## 安装

1. 下载 [one-punch-flow](https://github.com/o98k-ok/one-punch-flow/releases/latest)
2. 打开 alfred workflow
3. 安装

## 使用
![使用demo](assets/image.png)

1. 关键词输入
    1. 支持中文
    2. 支持拼音
    3. 支持首字母
2. 回车搜索
3. 选择结果

## 编辑

![编辑demo](assets/image_edit.png)

> `Commnd+Enter`编辑


# URL列表

```json
{
    "命令面板": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"workbench.action.showCommands\"}]",
    "固定标签": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"workbench.action.pinEditor\"}]",
    "打开终端": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"workbench.action.terminal.toggleTerminal\"}]",
    "换换主题": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"workbench.action.selectTheme\"}]",
    "接口调试": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"thunder-client-sidebar.focus\"}]",
    "收起文件列表": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"workbench.files.action.collapseExplorerFolders\"}]",
    "罗列仓库": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"projectManager.listProjects\"}]",
    "跳转到定义": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"editor.action.goToImplementation\"}]",
    "重命名": "cursor://ionutvmi.vscode-commands-executor/runCommands?data=[{\"id\":\"editor.action.rename\"}]"
  }
```