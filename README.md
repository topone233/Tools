# Tools
我的常用工具分享库
------

## 1. Chrome 插件

#### 1.1 网页代理(免费)

>下载地址：[Hoxx VPN Proxy](https://hoxx.com/)

用了两年的网页代理插件（免费节点推荐选择 印度）

速度上，如果只是加速GitHub、访问Twitter、Youtube、谷歌市场等 足够用的了。

#### 1.2 广告拦截

> 下载地址：[uBlock Origin](https://github.com/gorhill/uBlock)

各大视频网站的广告基本都能拦截，从大一开始用，效果不用多说，还你一个干净清爽的上网环境。

#### 1.3 新标签页

>下载地址：[Infinity](https://www.infinitynewtab.com/)

新标签页 （很好看，每天自动同步Bing的壁纸）

#### 1.4 翻译

>下载地址：[Saladict 沙拉查词](https://saladict.crimx.com/)

聚合了各大翻译源，支持网页翻译、划词翻译、搜索翻译等，超级方便好用，颜值超高，强推！

#### 1.5 阅读

>下载地址：[简阅](https://simpread.pro/)

如杂志般沉浸式阅读体验，提取文章主体，收藏，md格式下载等功能，超好用（贫穷如我 依然支持了一波 开通了终身会员）。

#### 1.6 Tab标签页管理

>下载地址： [OneTab](https://www.one-tab.com/)

对于我来说，我的浏览器日常开几十个标签页（遇到一个问题，往往需要看多个文章相互补充，才能解决我所遇到的问题。另一种情况就是......拖延症，没错，滚进我的收藏夹吃灰，每次看到好的或者需要的文章，总是会舍不得关闭 晚点就有时间把它看完，嗯。。。一晚就是永远。。。），开几十个标签页带来的问题：一是实在太多了，chrome容不下了，对 容不下了。。。二是chrome的每一个标签页都是一个独立的进程，我8G的内存，此时风扇已经开始有噪音了，如果是在家还好，可是办公室里可太尬尴了。

标签页管理的插件完美的解决了我的问题(据说可以节省高达95％的内存！)。

#### 1.7 MEGA云盘

> 下载地址：[MEGA](https://mega.nz/)

虽然是境外的网盘，但是搭配上第一条推荐的代理插件，下载速度丝毫不逊色某度云网盘 doge

#### 1.8 RSS订阅

> 下载地址: [RSS Feed Reader](https://feeder.co/)

很喜欢去发现一些个人博客，他们往往风格各异，内容丰富多彩 涉及各个领域。如果对博主的内容大多都很感兴趣，那么这时候就需要一个订阅功能 以实时查看其最新内容，那么你需要一个RSS订阅插件。

#### 1.9 GitLab Tree

> 下载地址：[SpanTree - GitLab Tree](https://chrome.google.com/webstore/detail/spantree-gitlab-tree/gcjikeldobhnaglcoaejmdlmbienoocg)

此插件可以实现像IDE那样目录展示，很方便，不用再一层一层点开查看。公司用的GitLab私服也可以用。

#### 1.10 Tampermonkey 油猴

> 下载地址：[Tampermonkey](https://www.tampermonkey.net/)

油猴不必多说，久负盛名。不过其本质还是个容器、载体。这里主要推荐下一些有趣的插件（当然 你也可以设计自己的插件工具）。

- `BiliBIli` 港澳台
- 智慧树网课助手（包含考试）
- 超星网课助手（包含考试）
- 百度文库免费下载
- ...... 还有很多有趣的 自行挖掘

------
## 2. IDEA 插件系列
#### 2.1 Jetbrains系列产品无限重置试用

>Jetbrains家的产品有一个很良心的地方，他会允许你试用`30`天（这个数字写死在代码里了）以评估是否你真的需要为它而付费.
>
>有一款插件可以无限重置试用时间。**但切记不要无休止的一直试用，这并不是这个插件的本意！**

##### 如何安装

插件市场搜索 `IDE Eval Reset` 安装即可. [项目地址](https://gitee.com/pengzhile/ide-eval-resetter)    [使用说明](https://zhile.io/2020/11/18/jetbrains-eval-reset-da33a93d.html)

#### 2.2 阿里 Java开发规约插件

插件市场搜索 `Alibaba Java Coding Guidelines` 安装即可.

#### 2.3 官方中文插件

插件市场搜索 `Chinese(Simplified)Language Pack EAP` 安装即可.

#### 2.4 JSON格式化

插件市场搜索 `Json Parser` 安装即可.

#### 2.5 快捷键提示

插件市场搜索 `Key Promoter X` 安装即可.

------

## 3. Markdown写作工具

#### 3.1 写作工具：Typora

> 下载地址（官网）：[Typora](https://typora.io/)

#### 3.2 图片上传工具：Picgo

搭配Typora，效率神器

> 下载地址（官网）：[Picgo](https://molunerfinn.com/PicGo)

#### 3.3 **图床：去不图床**

配置说明：https://dusays.com/241/

**Typora + Picgo + 去不图床 设置：**

Typora：

1. Ctrl + 逗号 进入偏好设置 -> 图像 
2. 插入图片时 -> 上传图片 -> 勾选前两项
3. 上传服务设定 ->  PicGo（app）->  PicGo本地安装路径
4. 打开Picgo -> 打开配置文件 -> 修改server端口号为：36677 
5. 上传区修改图床
6. 重启Picgo
7. 回到第三步Typora页面 -> 验证图片上传路径 -> 验证成功
