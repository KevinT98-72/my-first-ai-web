# my-first-ai-web

我的第一个 AI 辅助网页项目。页面标题为 **A little change.**，点击 **Change the message ↗** 按钮会循环显示四条消息。新增的 **Reset message** 按钮可恢复初始消息，并将循环位置重置。

## 文件

- `index.html`：完整网页，包含 HTML、CSS 和 JavaScript，无外部依赖。
- `README.md`：项目说明、运行方法和检查步骤。

## 本地运行

直接用浏览器打开 `index.html`，或在安装 Python 3 后，在仓库目录运行：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

然后访问 <http://127.0.0.1:8765/>。服务器运行时该地址才有效，按 `Ctrl+C` 停止服务器。

`127.0.0.1` 仅指向访问者自己的电脑，不是公开网站地址。此仓库保存网页源文件；上传源文件不会自动启用网站托管。

## 使用与检查

1. 打开页面，确认显示标题和初始消息：`Hello! A new message is just a click away.`
2. 点击按钮，确认消息变为：`You clicked it! Small actions can make a difference.`
3. 继续点击，确认四条消息循环显示。
4. 刷新页面，确认恢复初始消息。
5. 使用 Tab 聚焦按钮，再用 Enter 或空格激活，确认消息更新。

6. 切换到任意消息后点击 **Reset message**，确认恢复初始消息；连续点击重置应保持初始消息。
7. 重置后再点击切换按钮，确认显示第二条消息，说明循环位置也已重置。

## AI 辅助说明

网页由 AI 根据“创建一个带标题和消息切换按钮的本地页面”的要求生成；此仓库在原页面基础上添加重置功能，并补充运行与检查说明。
