curl -sL https://rpm.nodesource.com/setup_10.x | bash -
yum install -y nodejs
# [#](#安装) 安装
关于旧版本

Vue CLI 的包名称由 `vue-cli` 改成了 `@vue/cli`。
如果你已经全局安装了旧版本的 `vue-cli` (1.x 或 2.x)，你需要先通过 `npm uninstall vue-cli -g` 或 `yarn global remove vue-cli` 卸载它。
</div> <div class="tip custom-block">

Node 版本要求

Vue CLI 需要 [Node.js<svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg>](https://nodejs.org/) 8.9 或更高版本 (推荐 8.11.0+)。你可以使用 [nvm<svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg>](https://github.com/creationix/nvm) 或 [nvm-windows<svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg>](https://github.com/coreybutler/nvm-windows) 在同一台电脑中管理多个 Node 版本。
</div> 

可以使用下列任一命令安装这个新的包：
 

npm install -g @vue/cli
# OR
yarn global add @vue/cli


    安装之后，你就可以在命令行中访问 `vue` 命令。你可以通过简单运行 `vue`，看看是否展示出了一份所有可用命令的帮助信息，来验证它是否安装成功。

    你还可以用这个命令来检查其版本是否正确 (3.x)：
     vue --version


npm install -g cnpm 配置淘宝镜像

<div class="postBody">

<div id="cnblogs_post_body" class="blogpost-body ">

**一、通过npm全局安装n工具**

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_370573" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`npm install -g n`</div></div></td></tr></tbody></table></div></div>
</div>

**二、使用n安装Node.js**

1. n安装说明

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_258730" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div><div class="line number2 index1 alt1">2</div><div class="line number3 index2 alt2">3</div><div class="line number4 index3 alt1">4</div><div class="line number5 index4 alt2">5</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`n` `#列出已安装的Node.js版本`</div><div class="line number2 index1 alt1">`n latest` `#安装最新版本（包含最新特性的版本，不推荐用于生产环境）`</div><div class="line number3 index2 alt2">`n stable` `#安装最新稳定版（不推荐用于生产环境）`</div><div class="line number4 index3 alt1">`n lts` `#安装最新长期维护版（生产环境推荐）`</div><div class="line number5 index4 alt2">`n &lt;版本号&gt;` `#根据版本号安装对应版本的Node.js`</div></div></td></tr></tbody></table></div></div>
</div>

2. 安装最新长期维护版

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_310147" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`n lts`</div></div></td></tr></tbody></table></div></div>
</div>

3. 使用n切换Node.js版本

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_581569" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div><div class="line number2 index1 alt1">2</div><div class="line number3 index2 alt2">3</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`&gt; n`</div><div class="line number2 index1 alt1">`&nbsp;&nbsp;``ο node/8.9.1`</div><div class="line number3 index2 alt2">`&nbsp;&nbsp;&nbsp;&nbsp;``node/9.2.0`</div></div></td></tr></tbody></table></div></div>
<pre>#通过键盘上下方向键选择对应版本并按下回车</pre>
</div>

三、常见问题

安装完后使用 “node -v” 命令查看版本发现还是原来的，这是因为系统默认使用的是“/bin/”目录下node命令，而n安装的Node.js的node命令是在“/usr/local/bin/”目录下

1.重命名保留“/bin”目录下先前的node命令

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_276623" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div><div class="line number2 index1 alt1">2</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`&gt; cd /bin/`</div><div class="line number2 index1 alt1">`&gt; mv node node_bak`</div></div></td></tr></tbody></table></div></div>
</div>

2.为“/usr/local/bin/”目录下的node建立软连接到“/bin”目录

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_627812" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div><div class="line number2 index1 alt1">2</div><div class="line number3 index2 alt2">3</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`&gt; ln -s /usr/local/bin/node /bin/node`</div><div class="line number2 index1 alt1">`&gt; node -v`</div><div class="line number3 index2 alt2">`v8.9.1`</div></div></td></tr></tbody></table></div></div>
</div>

3.同上为npm命令建立软连接

<div class="cnblogs_Highlighter sh-gutter">
<div><div id="highlighter_898115" class="syntaxhighlighter  javascript"><div class="toolbar"><span>[?](#)</span></div><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="gutter"><div class="line number1 index0 alt2">1</div><div class="line number2 index1 alt1">2</div><div class="line number3 index2 alt2">3</div><div class="line number4 index3 alt1">4</div><div class="line number5 index4 alt2">5</div></td><td class="code"><div class="container"><div class="line number1 index0 alt2">`&gt; cd /bin/`</div><div class="line number2 index1 alt1">`&gt; mv npm npm_bak` `#重命名保留先前的npm`</div><div class="line number3 index2 alt2">`&gt; ln -s /usr/local/bin/npm /bin/npm` `#建立软连接`</div><div class="line number4 index3 alt1">`&gt; npm -v`</div><div class="line number5 index4 alt2">`5.5.1`</div></div></td></tr></tbody></table></div></div>
</div>

