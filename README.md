
# VScode-Markdown-theme-Maserhe
## 前提
你已经安装好 `markdown-preview-enhanced`这个强大的插件了，
没有安装？
**打开 vscode 编辑器，在插件页搜索 `markdown-preview-enhanced`，接着点击 Install 按钮。**
### 1 clone源码
首先将源码`clone`到本地,当然也可以直接预览复制代码,在电脑上新建`txt`文件,把代码复制上去改一下后缀为`css`。
`mystyle.css`存放的是 Markdown 排版样式。
`codeblock.css`存放的是 代码块样式。
当然你可以自己进行自定义修改成你自己喜欢的样式，很多地方我都加上了注释。

### 2 找到vscode Markdown-preview-enhanced 插件主题位置

文件大致位置在 `C:\Users\你的用户名\.vscode\extensions\shd101wyy.markdown-preview-enhanced-0.5.12\node_modules\@shd101wyy\mume\styles`

![QQ截图20200723204205](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/QQ截图20200723204205.png)

preview_theme 这里存放的是 Markdown 排版样式，你把刚刚得到的`mystyle.css`文件放进去就行了。
prism_theme 这里存放的是 代码块 排版样式，你把刚刚得到的`codeblock.css`文件放进去就行了。

### 3 配置json文件。

打开vscode , 输入 `Ctrl-shift-p`然后打开 Open Settings(json)文件

![20200723231108](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/20200723231108.png)

修改 红框圈起来的两项,第一项为 Markdown 的排版样式。
第二项为 代码块的样式。

![QQ截图20200723204013](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/QQ截图20200723204013.png)

配置好之后再打开 Markdown 预览看一下，是不是美观很多？

### 4 导出pdf文件
光自己看可不行啊，最终还是要导出pdf呢！

![20200723231648](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/20200723231648.png)

在预览界面 右键》HTML》HTML(offline) 生成html文件后，找到html文件我们用谷歌浏览打开html文件。我们可以使用谷歌浏览器的HTML打印功能生成干干净净的pdf。

![13](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/13.png)

**注意选择Goolge浏览器打印时，**

![456](https://picgo-1259138584.cos.ap-beijing.myqcloud.com/Markdown/456.png)

把背景图形哪一项给勾选上，然后就能生成好看的pdf文件了。
