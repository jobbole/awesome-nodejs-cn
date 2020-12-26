# Node.js 资源大全中文版

【导读】：Node.js 是一个开源、跨平台的，用于编写服务器和命令行的 JavaScript 运行时工具。

[awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) 是`sindresorhus`发起维护的 Node.js 资源列表，内容包括：命令行工具、日志、调试、HTTP、构建工具、文件系统、模板、Web 框架、流程控制、文本、图片和数据校验等。

这个列表堪称最全面的 Node.js 资源汇总，在 GitHub 已接近 `4 万 Star`。

中文版由`开源前哨`和`前端大全`微信公号团队维护更新，欢迎在 Github 上关注。这个中文版的资源库会定期同步更新到这里。

### 本项目的参与者

- 维护者：「开源前哨」和「前端大全」微信公号团队。 「开源前哨」会定期在知乎专栏分享最新、有趣和热门的开源项目，每个项目都有详细的介绍和示例。传送门：<https://www.zhihu.com/column/c_1317124962785062912>
- 贡献者：[cooperw991](https://github.com/cooperw991)


# 资源列表

- [包](#包) 
  - [黑科技](#黑科技)
  - [命令行程序](#命令行程序)
  - [函数式编程](#函数式编程)
  - [HTTP](#HTTP)
  - [调试&nbsp;/&nbsp;分析](#调试&nbsp;/&nbsp;分析)
  - [日志](#日志)
  - [命令行工具](#命令行工具)
  - [构建工具](#构建工具)
  - [硬件](#硬件)
  - [模板](#模板)
  - [Web&nbsp;框架](#Web&nbsp;框架)
  - [文档相关](#文档相关)
  - [文件系统](#文件系统)
  - [流程控制](#流程控制)
  - [文件流](#文件流)
  - [实时](#实时)
  - [图片](#图片)
  - [文本](#文本)
  - [数字](#数字)
  - [数学](#数学)
  - [日期](#日期)
  - [URL](#URL)
  - [数据校验](#数据校验)
  - [解析](#解析)
  - [人性化](#人性化)
  - [压缩](#压缩)
  - [网络](#网络)
  - [数据库](#数据库)
  - [测试](#测试)
  - [安全](#安全)
  - [基准化分析](#基准化分析)
  - [代码压缩](#代码压缩)
  - [认证](#认证)
  - [授权](#授权)
  - [电子邮件](#电子邮件)
  - [任务队列](#任务队列)
  - [Node.js&nbsp;管理](#Node.js&nbsp;管理)
  - [自然语言处理](#自然语言处理)
  - [进程管理](#进程管理)
  - [自动化](#自动化)
  - [AST](#AST)
  - [静态网站生成](#静态网站生成)
  - [内容管理系统](#内容管理系统)
  - [论坛](#论坛)
  - [写博客](#博客)
  - [怪诞的](#怪诞的)
  - [序列化](#序列化)
  - [其他](#其他)


# 资源列表
----

## 包


### 黑科技

- [webtorrent](https://github.com/webtorrent/webtorrent) - Node.js 和浏览器端洪流客户端
- [peerflix](https://github.com/mafintosh/peerflix) - 洪流客户端
- [dat](https://github.com/datproject/dat-node) - 对数据集的实时复制和版本控制
- [ipfs](https://github.com/ipfs/js-ipfs) - 探索使用相同系统文件连接所有计算设备的分布式文件系统
- [stackgl](https://github.com/stackgl) - 建立在 browserify 和 npm 之上的 WebGL 开放软件生态系统
- [peerwiki](https://github.com/mafintosh/peerwiki) - 所有 BitTorrent 上的维基百科
- [peercast](https://github.com/mafintosh/peercast) - Chromecast 上的视频种子播放软件
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - 简洁，可读性强的，可靠的比特币库
- [Bitcore](https://github.com/bitpay/bitcore) - 纯净强大的比特币库
- [PDFKit](https://github.com/foliojs/pdfkit) - PDF 生成库
- [turf](https://github.com/Turfjs/turf) - 模块化地理空间处理和分析引擎
- [webcat](https://github.com/mafintosh/webcat) - 使用你的 GitHub 私/公钥利用点对点网页即时通信进行跨网络鉴权
- [NodeOS](https://github.com/NodeOS/NodeOS) - 第一个基于 npm 的操作系统
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI 操作系统
- [Brain.js](https://github.com/BrainJS/brain.js) - 机器学习框架
- [Pipcook](https://github.com/alibaba/pipcook) - 用于创建机器学习管道的前端算法框架
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - 图论（a.k.a. 网络）建模和分析
- [Kadence](https://gitlab.com/deadcanaries/kadence) - KAD 算法分布式哈希表
- [Seedshot](https://github.com/twobucks/seedshot) - 临时点对点分享浏览器截屏
- [js-git](https://github.com/creationix/js-git) - 用 JavaScript 实现的 Git
- [skale](https://github.com/skale-me/skale-engine) - 高性能分布式数据处理引擎
- [xlsx](https://github.com/SheetJS/sheetjs) - 纯 JS 的 Excel 表格读写工具
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - 纯 JavaScript 实现的 Git

### 命令行程序

- [np](https://github.com/sindresorhus/np) - 更好的 ``` npm publish```
- [npm-name](https://github.com/sindresorhus/npm-name) - 检查包名在 npm 上是否可用 
- [gh-home](https://github.com/sindresorhus/gh-home) - 打开当前目录下项目的 GitHub 主页 
- [npm-home](https://github.com/sindresorhus/npm-home) - 打开一个包的 npm 主页 
- [trash](https://github.com/sindresorhus/trash) - 比 ```rm``` 更安全的选择
- [speed-test](https://github.com/sindresorhus/speed-test) - 测试你的互联网连接速度和 ping 值
- [emoj](https://github.com/sindresorhus/emoj) - 命令行下从文本中查找相关的 emoji
- [pageres](https://github.com/sindresorhus/pageres) - 获取网站的截图
- [cpy](https://github.com/sindresorhus/cpy) - 复制文件 
- [vtop](https://github.com/MrRio/vtop) - 有漂亮图表的更好用的 top 
- [empty-trash](https://github.com/sindresorhus/empty-trash) - 清空文件夹
- [is-up](https://github.com/sindresorhus/is-up) - 检测网站是否可以正常访问
- [is-online](https://github.com/sindresorhus/is-online) - 检测网络连接是否正常
- [public-ip](https://github.com/sindresorhus/public-ip) - 获取你的公网 IP 地址
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 在终端里复制粘贴
- [XO](https://github.com/xojs/xo) - 使用 JavaScript happiness 风格强制执行严格代码风格
- [Standard](https://github.com/feross/standard) - JavaScript 标准样式 - 规范所有样式的样式
- [ESLint](https://github.com/eslint/eslint) - JavaScript 可插式的代码规范检查工具
- [dev-time](https://github.com/samverschueren/dev-time-cli) - 获取 GitHub 用户当前的本地时间
- [David](https://github.com/alanshaw/david) - 当 npm 软件包中的依赖过时通知你
- [http-server](https://github.com/indexzero/http-server) - 简单、零配置的命令行 HTTP 服务器
- [Live Server](https://github.com/tapio/live-server) - 具有热重启功能的开发环境 HTTP 服务器
- [bcat](https://github.com/kessler/node-bcat) -将命令管道输出到 Web 浏览器
- [normit](https://github.com/pawurb/normit) - 在您的终端中使用语音合成功能进行 Google 翻译
- [fkill](https://github.com/sindresorhus/fkill-cli) - 跨平台的进程强杀命令
- [pjs](https://github.com/danielstjules/pjs) - 用 JavaScript 实现的快速过滤、映射和累加器的管道命令
- [license-checker](https://github.com/davglass/license-checker) - 对你应用中的依赖进行许可证检查
- [browser-run](https://github.com/juliangruber/browser-run) - 在浏览器环境中轻松运行代码
- [tmpin](https://github.com/sindresorhus/tmpin) - 对所有允许文件输入的 CLI 程序添加 stdin 支持
- [wifi-password](https://github.com/kevva/wifi-password-cli) - 获取当前 wifi 的密码
- [wallpaper](https://github.com/sindresorhus/wallpaper) - 更换桌面壁纸
- [brightness](https://github.com/kevva/brightness-cli) - 更改屏幕亮度
- [torrent](https://github.com/maxogden/torrent) - 下载种子
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - 关闭所有 Chrome 标签来提升性能、降低功耗以及节省内存占用
- [alex](https://github.com/wooorm/alex) - 捕捉写作中出现的不当表达
- [pen](https://github.com/noraesae/pen) - 用你喜爱的编辑器编写 Markdown，在浏览器中提供实时预览
- [subdownloader](https://github.com/beatfreaker/subdownloader) - 电影和电视剧的字幕下载器
- [dark-mode](https://github.com/sindresorhus/dark-mode) - 开关 macOS 暗黑模式
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP 地址查找器
- [Jsome](https://github.com/Javascipt/Jsome) - 使用自定义颜色和缩进打印漂亮的 JSON
- [itunes-remote](https://github.com/mischah/itunes-remote) - 交互式控制 iTunes
- [mobicon](https://github.com/samverschueren/mobicon-cli) - 移动端应用图标生成器
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - 移动端应用启动页生成器
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - 生成漂亮的 HTML 展示 git diff 命令的结果
- [Cash](https://github.com/dthree/cash) - 用纯 JavaScript 编写的跨平台类 Unix Shell
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - 在终端中使用 npm 软件包
- [jscpd](https://github.com/kucherenko/jscpd) - 源代码重复代码检测
- [atmo](https://github.com/Raathigesh/Atmo) - 模拟服务器端 API
- [auto-install](https://github.com/siddharthkp/auto-install) - 编写代码时自动安装依赖
- [lessmd](https://github.com/linuxenko/lessmd) - 终端环境下的 Markdown 预览器
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - 查找使性能降低的依赖
- [localtunnel](https://github.com/localtunnel/localtunnel) - 向公网开放你的 localhost
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - 基于 SVG 分享终端会话
- [gtop](https://github.com/aksakalli/gtop) - 终端下的系统监控仪表板
- [themer](https://github.com/mjswensen/themer) - 为您的编辑器、终端、壁纸、Slack等生成主题
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 为你的代码生成精美的图片
- [cash-cli](https://github.com/xxczaki/cash-cli) - 170 种货币汇率转换
- [taskbook](https://github.com/klauscfhq/taskbook) - 命令行环境下的任务、板块和笔记管理器
- [discharge](https://github.com/brandonweiss/discharge) - 轻松将静态网站部署到 Amazon S3
- [npkill](https://github.com/voidcosmos/npkill) - 轻松查找和删除过时且臃肿的 node_modules 文件夹

### 函数式编程

- [lodash](https://github.com/lodash/lodash) - 更好更快的Underscore.js，提供兼容性，灵活性，高性能和其他功能的实用工具库
- [immutable](https://github.com/facebook/immutable-js) - 不可变数据集
- [Ramda](https://github.com/ramda/ramda) - 专注于数据不变性和纯粹的函数式风格的工具集，利用将参数后置和自动柯里化实现灵活的函数组合。
- [Folktale](https://github.com/origamitower/folktale) - 一套用于 JavaScript 中的通用函数编程的库，它允许你编写bug更少，重用性更强的优雅的、模块化的应用程序
- [Mout](https://github.com/mout/mout) - 该库与其他现有解决方案之间最大的区别是，您可以选择只加载需要的模块/函数，而不需要额外开销
- [Bacon.js](https://github.com/baconjs/bacon.js) - 函数式的响应式编程
- [RxJS](https://github.com/reactivex/rxjs) - 用于转换、组合和查询各种类型数据的函数式响应式库
- [Lazy.js](https://github.com/dtao/lazy.js) - 惰性求值的类似于 lodash/Underscore 的工具库，在许多情况下可以提供卓越的性能.
- [Kefir.js](https://github.com/kefirjs/kefir) - 专注于高性能和低内存消耗的响应式库

### HTTP

- [got](https://github.com/sindresorhus/got) - 为内置的 ```http``` 模块提供更好的接口
- [gh-got](https://github.com/sindresorhus/gh-got) - 为 ```got``` 和 GitHub API 交互提供更方便的封装
- [axios](https://github.com/mzabriskie/axios) - 基于 Promise 的 HTTP 客户端（也可以在浏览器中工作）
- [wreck](https://github.com/hapijs/wreck) - HTTP 客户端工具.
- [download](https://github.com/kevva/download) - 使下载和提取文件变得轻松
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP 代理
- [superagent](https://github.com/visionmedia/superagent) - HTTP 请求库
- [node-fetch](https://github.com/bitinn/node-fetch) - Node.js 的```window.fetch``` 
- [flashheart](https://github.com/bbc/flashheart) - REST 客户端
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - 使用 JSON 文件或者 JavaScript 对象 建立一个伪装的可自定义路由的后端服务
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - 使用符合 RFC 的缓存支持封装原始的 HTTP 请求.
- [gotql](https://github.com/khaosdoctor/gotql) - 基于 [got](https://github.com/sindresorhus/got) 构建的 GraphQL 请求库
- [global-agent](https://github.com/gajus/global-agent) - 可以使用环境变量配置的全局 HTTP / HTTPS 代理
- [smoke](https://github.com/sinedied/smoke) - 可记录的基于文件的模拟 HTTP 服务 

### 调试 / 分析

- [ndb](https://github.com/GoogleChromeLabs/ndb) - 增强 Chrome DevTools 调试体验的工具
- [ironNode](https://github.com/s-a/iron-node) - 支持 ES2015 的 Node.js 开箱即用的调试器
- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于 Blink 开发者工具的调试器
- [debug](https://github.com/visionmedia/debug) - 轻量级调试工具
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - 当你不知道为何 Node.js 没有正确退出时...
- [njsTrace](https://github.com/valyouw/njstrace) - 检测并跟踪代码，查看所有函数调用、参数、返回值以及在每个函数中花费的时间 
- [vstream](https://github.com/joyent/node-vstream) - 检查数据流并且通过管道展示
- [stackman](https://github.com/watson/stackman) - 增强抛出异常的错误栈追踪
- [locus](https://github.com/alidavut/locus) - 在运行时启动所有可访问变量的REPL
- [0x](https://github.com/davidmarkclements/0x) - 一个火焰图分析工具
- [ctrace](https://github.com/automation-stack/ctrace) - 对系统调用和信号的追踪进行格式优化和增强
- [leakage](https://github.com/andywer/leakage) - 编写内存泄露测试
- [llnode](https://github.com/nodejs/llnode) - 一个用于 “解剖” 崩溃的 Node.js 进程，检视其对象的工具
- [thetool](https://github.com/sfninja/thetool) - 以 Chrome DevTools 友好格式为你的应用捕获不同的 CPU，内存和其他资源的使用情况
- [swagger-stats](https://github.com/slanatech/swagger-stats) - 追踪 API 调用并监视 API 表现、运行状况和使用度量
- [NiM](https://github.com/june07/nim) - 管理 DevTools 调试工作流

### 日志

- [pino](https://github.com/pinojs/pino) - 受 `Bunyan` 启发的超快速日志记录器
- [winston](https://github.com/winstonjs/winston) - 支持多种记录格式的异步日志记录库
- [console-log-level](https://github.com/watson/console-log-level) - 可以想象的最简单的记录器，支持日志级别和自定义前缀
- [storyboard](https://github.com/guigrpa/storyboard) -端到端，分层，实时，丰富多彩的日志和描述
- [signale](https://github.com/klauscfhq/signale) - Console 日志记录器
- [consola](https://github.com/nuxt/consola) - Console 日志记录器

### 命令行工具

- [chalk](https://github.com/chalk/chalk) - 美化终端字符串样式
- [meow](https://github.com/sindresorhus/meow) - CLI app 帮助
- [yargs](https://github.com/yargs/yargs) - 自动生成优雅用户界面的命令行分析程序
- [ora](https://github.com/sindresorhus/ora) - 优雅的终端旋转进度条
- [get-stdin](https://github.com/sindresorhus/get-stdin) - 简单的 stdin
- [log-update](https://github.com/sindresorhus/log-update) - 在终端里以覆盖前一个输出的方式打印日志，用于制作进度条或者动画等
- [Ink](https://github.com/vadimdemedes/ink) - 基于 React 的命令行交互程序
- [listr](https://github.com/samverschueren/listr) - 终端任务列表
- [conf](https://github.com/sindresorhus/conf) - 一个简单的用于程序或模块配置管理的工具
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - 操作终端的 ANSI 转义代码
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 用不同颜色的符号记录不同级别的日志
- [figures](https://github.com/sindresorhus/figures) - 支援 Windows CMD 回退方案的 Unicode 符号
- [boxen](https://github.com/sindresorhus/boxen) - 在终端中创建方框
- [terminal-link](https://github.com/sindresorhus/terminal-link) - 在终端中创建可点击的链接
- [terminal-image](https://github.com/sindresorhus/terminal-image) - 在终端里展示图片
- [string-width](https://github.com/sindresorhus/string-width) - 获取字符串的可视宽度 - 显示字符串所需的列数
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - 在终端中将字符串截断为特定宽度
- [first-run](https://github.com/sindresorhus/first-run) - 检查是否是第一次运行该进程
- [blessed](https://github.com/chjj/blessed) - 类似于 Curses 的库
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 交互式的命令行提示工具
- [yn](https://github.com/sindresorhus/yn) - 将包含 yes/no 语义的字符串解析为布尔值
- [cli-table3](https://github.com/cli-table/cli-table3) - 漂亮的 Unicode 表
- [drawille](https://github.com/madbence/node-drawille) - 使用 Unicode 盲文字符在终端上绘图
- [update-notifier](https://github.com/yeoman/update-notifier) - 升级 CLI 应用程序的通知
- [ascii-charts](https://github.com/jstrace/chart) - 终端下的 ASCII 柱状图
- [progress](https://github.com/tj/node-progress) - 灵活的 ASCII 进度条
- [insight](https://github.com/yeoman/insight) - 使用 metrics 向 Google Analytics 发送匿名报告来帮助你理解你的工具是怎样被使用的
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - 显示或关闭 CLI 光标
- [columnify](https://github.com/timoxley/columnify) - 将控制台文本打印按列输出，支持单元格修饰
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - 列式输出 Unicode 和 Ansi-safe
- [cfonts](https://github.com/dominikwilkowski/cfonts) - 控制台下的性感 ASCII 字体
- [multispinner](https://github.com/codekirei/node-multispinner) - 多样的、可同时独立控制的 CLI 旋转指示器
- [omelette](https://github.com/f/omelette) - Shell 下的自动补全
- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台的环境变量设置
- [shelljs](https://github.com/shelljs/shelljs) - 可移植的 Unix shell 命令
- [sudo-block](https://github.com/sindresorhus/sudo-block) - 禁止用户用 root 权限使用你的程序
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - 强制对未加处理的 promise rejections 错误给出提示
- [sparkly](https://github.com/sindresorhus/sparkly) - 生成迷你图 `▁▂▃▅▂▇`
- [Bit](https://github.com/teambit/bit) - 在存储库中创建、维护、查找和使用小型模块和组件
- [gradient-string](https://github.com/bokub/gradient-string) - 为终端输出添加漂亮的色彩渐变
- [oclif](https://github.com/oclif/oclif) - CLI框架，包括解析器、自动文档、测试和插件
- [term-size](https://github.com/sindresorhus/term-size) - 准确地获得终端窗口大小
- [Cliffy](https://github.com/drew-y/cliffy) - CLI 的交互式框架

### 构建工具

- [parcel](https://github.com/parcel-bundler/parcel) - 快速，零配置的Web应用构建工具
- [webpack](https://github.com/webpack/webpack) - 面向浏览器的打包工具
- [rollup](https://github.com/rollup/rollup) - 新一代 ES2015 打包构建工具
- [gulp](https://github.com/gulpjs/gulp) - 编程式、流式快速构建系统
- [Broccoli](https://github.com/broccolijs/broccoli) - 快速、可靠的资源管道，支持固定时间重新编译和紧凑的构建定义
- [Brunch](https://github.com/brunch/brunch) - 前端 web 应用程序构建工具，具有简单的声明性配置、快速的增量编译和自定的工作流
- [Start](https://github.com/deepsweet/start) - 具有可共享预设的函数式任务管理器
- [ygor](https://github.com/shannonmoeller/ygor) - 一个基于 Promise 的任务执行工具 —— 当需要执行的工作太多 ```npm run``` 不足以完成任务时
- [FuseBox](https://github.com/fuse-box/fuse-box) - 首选支持 TypeScript 的结合了 webpack，JSPM 和 SystemJS 强大功能的快速构建系统
- [pkg](https://github.com/zeit/pkg) - 将你的 Node.js 项目打包成可执行文件

### 硬件

- [johnny-five](https://github.com/rwaldron/johnny-five) - 基于 Firmata 的 Arduino 框架
- [serialport](https://github.com/voodootikigod/node-serialport) - 读写串口
- [usb](https://github.com/nonolith/node-usb) - USB 库
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C 串行总线访问
- [onoff](https://github.com/fivdi/onoff) - GPIO 访问和中断检测
- [spi-device](https://github.com/fivdi/spi-device) - SPI 串行总线访问
- [pigpio](https://github.com/fivdi/pigpio) - 树莓派上的快速 GPIO、PWM、伺服控制、状态更改通知和中断处理
- [gps](https://github.com/infusion/GPS.js) - NMEA 解析器，用于处理 GPS 接收

### 模板

- [marko](https://github.com/marko-js/marko) - 基于 HTML 的模板引擎，可将模板编译为 CommonJS 模块，并支持流、异步渲染和自定义标签
- [nunjucks](https://github.com/mozilla/nunjucks) - 灵感来自于 Jinja2 的具有继承、异步控制等功能的模板引擎
- [handlebars.js](https://github.com/wycats/handlebars.js) - Mustache 模板的超集，其中添加了强大的功能，如 helpers 和更高级的 blocks
- [EJS](https://github.com/mde/ejs) - 超级简单的模板语言.
- [Pug](https://github.com/pugjs/pug) - 受Haml影响的高性能模板引擎.

### Web 框架

- [Hapi](https://github.com/hapijs/hapi) - 用于创建应用和服务的框架
- [Koa](https://github.com/koajs/koa) - 由 Express 幕后团队设计的框架，旨在为 Web 应用程序和 API 提供更小、更富表现力和更健壮的基础
- [Express](https://github.com/expressjs/express) - 一个为构建单页、多页以及混合 Web 应用程序提供强大的功能的 Web 应用程序框架
- [Feathers](https://github.com/feathersjs/feathers) - 受 Express 启发的微服务框架
- [LoopBack](https://github.com/strongloop/loopback) - 用于创建 REST API并轻松连接到后端数据源的强大框架
- [Meteor](https://github.com/meteor/meteor) - 一个超简单、位于程序数据库和用户界面之间、保持二者之间数据同步更新的纯 Javascript Web 框架。 *（你可能会喜欢 [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](https://github.com/restify/node-restify) - 帮助你构建正确的REST Web 服务
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持 ES2015+ 的WebSockets REST API 框架
- [ActionHero](https://github.com/actionhero/actionhero) - 用于为 TCP sockets，WebSocket 和 HTTP 客户端创建可重用、可扩展 API 的框架 
- [Next.js](https://github.com/zeit/next.js) - 极简化的  JavaScript 服务端渲染框架
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue.js 服务端渲染框架
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包
- [AdonisJs](http://adonisjs.com) - 基于依赖注入和 IoC 容器技术的 Node.js 的真正 MVC 框架.
- [Hemera](https://github.com/hemerajs/hemera) - 基于 [NATS](https://nats.io) 编写的可靠且容错的微服务
- [Micro](https://github.com/zeit/micro) - 使用异步实现的极简微服务框架
- [Moleculer](https://moleculer.services) - 快速而强大的微服务框架
- [Fastify](https://github.com/fastify/fastify) - 快速和低开销的 Web 框架
- [Nest](https://github.com/nestjs/nest) -受 Angular 启发的框架，用于构建高效且可扩展的服务器端应用程序
- [Zeronode](https://github.com/sfast/zeronode) - 用于 Node.js 微服务的最小化构建块
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - 使用类和装饰器的，用 TypeScript 编写 GraphQL API 的现代框架
- [TinyHttp](https://github.com/talentlessguy/tinyhttp) - 类似于 Express 的现代、快速的 Web 框架
- [Marble.js](https://github.com/marblejs/marble) - 基于 TypeScript 和 RxJS 的，用于构建服务端应用的函数式编程框架

### 文档相关

- [documentation.js](https://github.com/documentationjs/documentation) - 支持 ES2015+ 和流程注释的 API 文档生成器
- [ESDoc](https://github.com/esdoc/esdoc) - 面向 ES2015 的文档生成器，附加测试代码并评估文档覆盖范围
- [Docco](https://github.com/jashkenas/docco) - 生成一个在代码中混合注释的 HTML 的文档生成器
- [JSDoc](https://github.com/jsdoc3/jsdoc) - 类似于 JavaDoc 或 PHPDoc 的 API 文档生成器
- [Docusaurus](https://github.com/facebook/docusaurus) - 基于 React 和 Markdown 的文档生成器，具有多语言和版本控制功能

### 文件系统

- [del](https://github.com/sindresorhus/del) - 使用 globs 删除文件/文件夹
- [globby](https://github.com/sindresorhus/globby) - 支持多种模式的 Glob 文件
- [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝
- [rimraf](https://github.com/isaacs/rimraf) - 像 ```rm -rf``` 一样的递归删除
- [make-dir](https://github.com/sindresorhus/make-dir) - 像 ```mkdir -p``` 一样的递归创建目录
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - 功能增强版的 ```fs``` 模块
- [chokidar](https://github.com/paulmillr/chokidar) - 像 macOS 上使用原生 ```fsevents``` 一样监听 ```fs.watch``` 和 ```fs.watchFile``` 的文件系统监听器
- [find-up](https://github.com/sindresorhus/find-up) - 沿父目录向上查找文件
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - 进程间和机器间 lockfile 工具
- [load-json-file](https://github.com/sindresorhus/load-json-file) - 读取、解析 JSON 文件
- [write-json-file](https://github.com/sindresorhus/write-json-file) - 自动将 JSON 序列化写入到文件
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - 类似 ```fs.createWriteStream()``` 的原子操作
- [filenamify](https://github.com/sindresorhus/filenamify) - 将字符串转换为有效的文件名
- [lnfs](https://github.com/kevva/lnfs) - 像 ```ln -fs``` 一样，强制创建符号链接
- [istextorbinary](https://github.com/bevry/istextorbinary) - 检查文件是文本还是二进制
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - 完全重新设计的、方便日常使用的文件系统 API
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - 增加额外方法的 ```fs``` 模块
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - 查找 npm 包的根目录
- [filehound](https://github.com/nspragg/filehound) - 灵活、流畅的用于文件系统搜索的接口
- [move-file](https://github.com/sindresorhus/move-file) - 甚至可以跨设备使用的移动文件工具
- [tempy](https://github.com/sindresorhus/tempy) - 随机获取临时文件或目录的路径

### 流程控制

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - 致力于创新功能和性能的 Promise 库
	- [pify](https://github.com/sindresorhus/pify) - 将 callback 风格的函数转化为 Promise 风格
	- [delay](https://github.com/sindresorhus/delay) - 延迟执行 Promise
  - [promise-memoize](https://github.com/nodeca/promise-memoize) - 拥有过期时间和预加载功能的 Promise 返回值缓存工具
  - [valvelet](https://github.com/lpinca/valvelet) - 限制 Promise 访问频率的工具
  - [p-map](https://github.com/sindresorhus/p-map) - 可以使用 Promise 的 Map 方法
	- [更多](https://github.com/sindresorhus/promise-fun)
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Observables 的实现
	- [RxJS](https://github.com/ReactiveX/RxJS) - 响应式编程
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - 将 Observable 转换为 Promise
	- [更多…](https://github.com/sindresorhus/awesome-observables)
- Streams
	- [Highland.js](https://github.com/caolan/highland) - 仅使用标准JavaScript 和类似 Node 的流，即可轻松管理同步和异步代码
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - 异步并发迭代器，如 forEach
	- [async](https://github.com/caolan/async) - 提供简单，强大的功能来处理异步问题
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - 为 JavaScript 提供连续的通信（例如 Clojurescript core.async 或 Go）

### 文件流

- [through2](https://github.com/rvagg/through2) - 基于 streams2 的轻量流转换器，避免显示子类噪声
- [from2](https://github.com/hughsk/from2) - 方便使用的对 ReadableStream 的封装，灵感来自于 `through2`
- [get-stream](https://github.com/sindresorhus/get-stream) - 以字符串或 Buffer 的形式获取流
- [into-stream](https://github.com/sindresorhus/into-stream) - 将 buffer/string/array/object 转化为流
- [duplexify](https://github.com/mafintosh/duplexify) - 将可写和可读流转换为单个stream2 双工流
- [pumpify](https://github.com/mafintosh/pumpify) - 将一系列流合并为单个双工流
- [peek-stream](https://github.com/mafintosh/peek-stream) - 转换流，让你可预览第一行再决定如何解析它
- [binary-split](https://github.com/maxogden/binary-split) - 换行符（或任何定界符）分隔符流
- [byline](https://github.com/jahewson/node-byline) - 超简单的逐行流读取器
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - 转换流中的第一个块
- [pad-stream](https://github.com/sindresorhus/pad-stream) - 填充流中的每一行
- [multistream](https://github.com/feross/multistream) - 
将多个流合并为一个流
- [stream-combiner2](https://github.com/substack/stream-combiner2) - 从管道输出流
- [readable-stream](https://github.com/nodejs/readable-stream) - Streams2 and Streams3 核心实现镜像
- [through2-concurrent](https://github.com/almost/through2-concurrent) - 同时转换对象流

### 实时

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - 高可扩展度的 WebSocket 服务器和客户端库
- [Socket.io](https://github.com/socketio/socket.io) - 实现基于事件的实时双向通信
- [Faye](https://github.com/faye/faye) - 基于 Bayeux 协议的实时客户端-服务器消息总线
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - 可运行多 CPU 核心的可扩展的 HTTP + WebSocket 引擎
- [Primus](https://github.com/primus/primus) - 实时框架的抽象层，用于防止模块锁定
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - 可扩展的实时微服务框架
- [Kalm](https://github.com/kalm/kalm.js) - 低层级 socket 路由和中间件框架
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - MQTT 客户端——构建在 TCP/IP 协议上的基于 Pub-sub 的消息协议
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 基于 WebSocket 实现的 JSON-RPC 2.0
- [Aedes](https://github.com/mcollina/aedes) - 可以在任何流服务器上运行的 MQTT 准系统

### 图像

- [sharp](https://github.com/lovell/sharp) - 超快速的用于调整 JPEG，PNG，WebP 和 TIFF 图像大小的模块
- [image-type](https://github.com/sindresorhus/image-type) - 检测 Buffer / Uint8Array 的图像类型
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick 和 ImageMagick 的封装
- [lwip](https://github.com/EyalAr/lwip) - 不需要 ImageMagick 的轻量级图像处理器
- [pica](https://github.com/nodeca/pica) -
轻量级、高性能的纯 JS 实现的图片尺寸调整器（lanczos3）, 当不允许像素化时用 `canvas drawImage()` 替代 
- [jimp](https://github.com/oliver-moran/jimp) - 纯 JavaScript 中的图像处理
- [probe-image-size](https://github.com/nodeca/probe-image-size) - 无需完全下载即可获取大多数图像格式的大小
- [qrcode](https://github.com/soldair/node-qrcode) - 二维码和条形码生成器

### 文本

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码.
- [string-length](https://github.com/sindresorhus/string-length) - 获取字符串的真实长度-通过正确计算星号并忽略ansi转义码.
- [camelcase](https://github.com/sindresorhus/camelcase) - 将破折号/点号/下划线/空格分隔的字符串转换为驼峰式,案例：foo-bar→fooBar.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义RegExp特殊字符.
- [execall](https://github.com/sindresorhus/execall) - 在字符串中查找多个RegExp匹配项.
- [splice-string](https://github.com/sindresorhus/splice-string) - 移除或替换字符串的一部分`Array#splice`.
- [indent-string](https://github.com/sindresorhus/indent-string) - 缩进字符串中的每一行.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - 从字符串的每一行中除去前导空格.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - 检测代码缩进.
- [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器.
- [i18n-node](https://github.com/mashpie/i18n-node) - 具有动态JSON存储的简单翻译模块.
- [babelfish](https://github.com/nodeca/babelfish) - i18n，复数的语法非常简单.
- [matcher](https://github.com/sindresorhus/matcher) - 简单通配符匹配.
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 规范化视觉上相似的unicode字符.
- [i18next](https://github.com/i18next/i18next) - 国际化框架.
- [nanoid](https://github.com/ai/nanoid) - 小巧、安全、URL友好、唯一的字符串ID生成器.

### 数字

- [random-int](https://github.com/sindresorhus/random-int) - 生成随机整数
- [random-float](https://github.com/sindresorhus/random-float) - 生成随机浮点数
- [unique-random](https://github.com/sindresorhus/unique-random) - 生成连续唯一的随机数
- [round-to](https://github.com/sindresorhus/round-to) - 将数字四舍五入到指定的小数位数：```1.234``` → ```1.2```

### 数学

- [ndarray](https://github.com/scijs/ndarray) - 多维数组
- [mathjs](https://github.com/josdejong/mathjs) - 庞大的数学公式库
- [math-clamp](https://github.com/sindresorhus/math-clamp) - 三个数中取出中间值
- [algebra](https://github.com/fibo/algebra) - 代数
- [multimath](https://github.com/nodeca/multimath) - 使用 WebAssembly 和 JS 创建快速图像数学的核心

### 日期

- [Luxon](https://github.com/moment/luxon) - 用于处理日期和时间的库
- [date-fns](https://github.com/date-fns/date-fns) - 现代日期工具
- [Moment.js](http://momentjs.com) - 分析、验证、操作和显示日期
- [Day.js](https://github.com/iamkun/dayjs) - Moment.js 之外可选的使用 Immutable 的日期库
- [dateformat](https://github.com/felixge/node-dateformat) - 日期格式化
- [tz-format](https://github.com/samverschueren/tz-format) - 带时区格式化时间: ```2015-11-30T10:40:35+01:00```
- [cctz](https://github.com/floatdrop/node-cctz) - 快速解析, 格式化, 和时区转化工具

### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - 规范化 URL
- [humanize-url](https://github.com/sindresorhus/humanize-url) - 可读化 URL: ```http://sindresorhus.com``` → ```sindresorhus.com```
- [url-unshort](https://github.com/nodeca/url-unshort) - 将短地址还原
- [speakingurl](https://github.com/pid/speakingurl) - 通过音译从字符串生成子段
- [linkify-it](https://github.com/markdown-it/linkify-it) - 具有完整 Unicode 支持的链接模式检测器
- [url-pattern](https://github.com/snd/url-pattern) - 比 regex 字符串更简单的 URLs 和其他字符串的模式匹配
- [embedza](https://github.com/nodeca/embedza) - 使用 oEmbed、Open Graph、meta 标记中的信息从 url 创建 HTML 片段/嵌入

### 数据校验

- [joi](https://github.com/hapijs/joi) - JavaScript 对象的对象模式描述语言和验证器
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 极速 JSON 格式校验工具
- [property-validator](https://github.com/nettofarah/property-validator) - 用于 Express 的属性校验工具
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API 清理和验证
- [ajv](https://github.com/epoberezkin/ajv) - 最快的 JSON 概要验证器，支持 v5、v6 和v7 方案
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - 简单基础的 JavaScript 和 TypeScript 数据验证器

### 解析

- [remark](https://github.com/wooorm/remark) - 插件化的 Markdown 处理器
- [markdown-it](https://github.com/markdown-it/markdown-it) - 100% 支持 CommonMark、扩展和语法插件的 Markdown 解析器
- [parse5](https://github.com/inikulin/parse5) - 快速全功能规范兼容的 HTML 解析器
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - JSON 去除注释
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - CSS 去除注释
- [parse-json](https://github.com/sindresorhus/parse-json) - 有更多错误提示的 JSON 处理工具
- [URI.js](https://github.com/medialize/URI.js) - URL 转化工具
- [PostCSS](https://github.com/postcss/postcss) - CSS 解析、压缩工具
- [JSONStream](https://github.com/dominictarr/JSONStream) - 流式处理 JSON.parse 和 stringify
- [csv-parser](https://github.com/mafintosh/csv-parser) - 旨在比其他任何工具都快的流式 CSV 解析器
- [PEG.js](https://github.com/pegjs/pegjs) - 简单的具有出色错误报告功能的语法分析器生成器
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web 爬虫工具
- [nearley](https://github.com/Hardmath123/nearley) - 简单，快速，强大的 JavaScript 解析器
- [binary-extract](https://github.com/juliangruber/binary-extract) - 无需解析整个对象就可以从 JSON 缓冲区中提取一个值的工具
- [Stylecow](https://github.com/stylecow/stylecow) - 可扩展插件的，用于解析，操纵和转换现代 CSS 的工具，使其与所有浏览器兼容
- [js-yaml](https://github.com/nodeca/js-yaml) - 快速的 YAML 解析器
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML 到 JavaScript 对象的转换器
- [Jison](https://github.com/zaach/jison) - 友好的 JavaScript 解析程序生成器. 与 Bison, Yacc 和 family 一样的思路
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - 解析、格式化、存储和验证电话号码
- [ref](https://github.com/TooTallNate/ref) - 读/写缓冲区中的结构化二进制数据
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - 读/写 Excel XLSX
- [Chevrotain](https://github.com/SAP/chevrotain) - 非常快速且功能丰富的 JavaScript 解析程序构建工具包
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 验证和解析 XML

### 人性化

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - 将字节数转换成可读的字符串: ```1337``` → ```1.34 kB```
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - 将毫秒数转化为可读时间字符串: ```1337000000``` → ```15d 11h 23m 20s```
- [ms](https://github.com/rauchg/ms.js) - 小巧的毫秒转换工具
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - 简化的错误信息
- [read-art](https://github.com/Tjatse/node-readability) - 从任何页面提取可读内容

### 压缩

- [yazl](https://github.com/thejoshwolfe/yazl) - 压缩
- [yauzl](https://github.com/thejoshwolfe/yauzl) - 解压缩
- [Archiver](https://github.com/archiverjs/node-archiver) - 流式接口的文件归档工具，支持 ZIP 和 TAR 格式
- [pako](https://github.com/nodeca/pako) - javascript 的高速 zlib 端口（deflate, inflate, gzip）
- [tar-stream](https://github.com/mafintosh/tar-stream) - 流式 tar 解析器和生成器，另见[tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - 解压模块，支持 `tar`、```tar.gz``` 和 ```zip``` 文件开箱即用

### 网络

- [get-port](https://github.com/sindresorhus/get-port) - 获取一个空闲的端口
- [ipify](https://github.com/sindresorhus/ipify) - 获取你的公网 IP 地址
- [getmac](https://github.com/bevry/getmac) - 获取电脑的 MAC 地址 
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP 客户端和服务器
- [netcat](https://github.com/roccomuso/netcat) - 纯 JS 实现的 Netcat 端口

### 数据库

- 数据库驱动
	- [PostgreSQL](https://github.com/brianc/node-postgres) - 使用纯 JavaScript 和原生 libpq 实现的 PostgreSQL 客户端
	- [Redis](https://github.com/luin/ioredis) - Redis 客户端
	- [LevelUP](https://github.com/Level/levelup) - LevelDB
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL 客户端
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB 客户端
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike 客户端
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase 客户端
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB 驱动
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - 支持 PostgreSQL，SQLite，MySQL 以及更多数据库的 ORM
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - Backbone.js 风格的PostgreSQL，MySQL 和 SQLite3 的 ORM
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL 数据访问工具
	- [Mongoose](https://github.com/Automattic/mongoose) - 优雅的 MongoDB 对象建模
	- [Waterline](https://github.com/balderdashy/waterline) - 与数据存储区无关的工具，可大大简化与一个或多个数据库的交互
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - 类似于 ActiveRecord 的，用于 PostgreSQL，MySQL，SQLite3 和 RESTful 数据存储的 ORM
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - 基于 Promise 的使用原生 SQL 的 PostgreSQL框架
	- [slonik](https://github.com/gajus/slonik) - 具有严格类型，详细日志记录和断言的 PostgreSQL 客户端
	- [Objection.js](https://github.com/Vincit/objection.js) - 基于 SQL 查询生成器 Knex 的轻量级 ORM
	- [TypeORM](https://github.com/typeorm/typeorm) - 支持 PostgreSQL，MariaDB，MySQL，SQLite 等数据库的 ORM
	- [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript 的基于数据映射的 ORM，使用工作单元和身份映射模式，支持 MongoDB，PostgreSQL，MySQL 和 SQLite
	- [Prisma](https://github.com/prisma/prisma) - TypeScript 的自动生成类型并且类型安全的查询构建器，可用于替代 ORM 的现代数据库接入方式，支持 PostgreSQL, MySQL 和 SQLite
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - 旨在灵活，可移植且易于使用的 PostgreSQL，MySQL 和 SQLite3 的查询构建器
- 其他
	- [NeDB](https://github.com/louischatriot/nedb) - 用 JavaScript 编写的嵌入式持久化数据库
	- [Lowdb](https://github.com/typicode/lowdb) - 由 Lodash 支持的小型 JavaScript 数据库.
	- [Keyv](https://github.com/lukechilds/keyv) - 支持多后端的简单键值存储
	- [Finale](https://github.com/tommybananas/finale) - 基于 Sequelize 模型生成 RESTful 末端
	- [database-js](https://github.com/mlaanderson/database-js) - 对多种数据库支持的具有类似 JDBC 数据库连接的封装
	- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - 使用 JavaScript 和 JSON 文件填充 MongoDB 数据库
	- [@databases](https://github.com/ForbesLindesay/atdatabases) - 避免 SQL 注入风险的纯 SQL 查询方式，支持 PostgreSQL, MySQL 和 SQLite3

### 测试

- [AVA](https://github.com/avajs/ava) - 面向未来的测试运行程序
- [Mocha](https://github.com/mochajs/mocha) - 功能丰富的测试框架，使得异步测试简单而又有趣
- [nyc](https://github.com/bcoe/nyc) - 基于 istanbul 构建的代码覆盖工具，可用于子流程.
- [tap](https://github.com/isaacs/node-tap) - TAP 测试框架
- [tape](https://github.com/substack/tape) - TAP 生产测试
- [power-assert](https://github.com/power-assert-js/power-assert) - 通过标准的 assert 接口提供描述性断言消息
- [Mochify](https://github.com/mantoni/mochify.js) - 基于 Browserify，Mocha，PhantomJS 和 WebDriver 的测试驱动开发
- [trevor](https://github.com/vdemedes/trevor) - 针对多个版本的 Node.js 运行测试，而无需手动切换版本或推送至 Travis CI
- [loadtest](https://github.com/alexfernandez/loadtest) - 使用自动化 API 为 Web 应用程序运行负载测试
- [Sinon.JS](https://github.com/sinonjs/sinon) - 测试数据模拟
- [navit](https://github.com/nodeca/navit) - PhantomJS/SlimerJS 封装，用于简化浏览器测试脚本
- [Nock](https://github.com/pgte/nock) - 模拟 HTTP 请求和异常
- [intern](https://github.com/theintern/intern) - 代码测试栈
- [toxy](https://github.com/h2non/toxy) - 可追踪的 HTTP 代理，用于模拟故障场景和网络状况
- [hook-std](https://github.com/sindresorhus/hook-std) - stdout/stderr 的钩子和修饰
- [testen](https://github.com/egoist/testen) - 使用 NVM 针对多个版本的 Node.js 运行本地测试
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于 Selenium WebDriver 的自动化 UI 测试框架
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - 基于 WebDriver 协议的自动化测试
- [Jest](https://github.com/facebook/jest) - 简单的 JavaScript 测试
- [TestCafe](https://github.com/DevExpress/testcafe) - 自动化的浏览器测试
- [abstruse](https://github.com/bleenco/abstruse) - 持续集成服务器
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - 端到端测试
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - 无头 Chrome
- [Playwright](https://github.com/microsoft/playwright) - 用单一 API 实现 Chromium, WebKit 和 Firefox 内核的无头浏览器
- [nve](https://github.com/ehmicky/nve) - 在本地多个版本的Node.js上运行任何命令
- [axe-core](https://github.com/dequelabs/axe-core) - 自动化 Web UI 测试引擎
- [testcontainers-node](https://github.com/testcontainers/testcontainers-node) - 提供轻量级的，即用即停的常规数据库、Web 浏览器或者其他任何可以运行在 Docker 容器里的实例

### 安全

- [upash](https://github.com/simonepri/upash) - 为所有密码散列算法提供统一的 API
- [themis](https://github.com/cossacklabs/themis) - 使典型加密方案易于使用的多语言框架：静态数据、已验证的数据交换、传输保护、身份验证等
- [GuardRails](https://github.com/apps/guardrails) - 在请求中提供安全反馈的 GitHub 应用程序
- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - 暴力攻击和 DDoS 攻击防御
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - 异步非阻塞哈希
- [jose-simple](https://github.com/davesag/jose-simple) - 使用 JOSE（ JSON 对象签名和加密）标准对数据进行加密和解密

### 基准化分析

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking 库，支持高分辨率计数器并且返回有意的统计结果
- [matcha](https://github.com/logicalparadox/matcha) - 简化的 Benchmarking 实现方案

### 代码压缩

- [babili](https://github.com/babel/babili) - 基于 Babel 工具链的 ES2015+ 压缩库
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript 压缩工具
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS 压缩工具
- [minimize](https://github.com/Swaagie/minimize) - HTML 压缩工具
- [imagemin](https://github.com/imagemin/imagemin) - Image 压缩工具

### 认证

- [Passport](https://github.com/jaredhanson/passport) - 简单, 无感的身份验证
- [Grant](https://github.com/simov/grant) - 支持 Express, Koa, Hapi, Fastify, AWS Lambda, Azure, Google Cloud, Vercel以及其他库的权限校验中间件

### 授权

- [CASL](https://github.com/stalniy/casl) - UI 和 API 的同构授权
- [node-casbin](https://github.com/casbin/node-casbin) - 支持访问控制模型（如 ACL、RBAC 和 ABAC ）的授权库

### 电子邮件

- [Nodemailer](https://github.com/andris9/Nodemailer) - 处理电子邮件的最快方式
- [emailjs](https://github.com/eleith/emailjs) - 向任何 SMTP 服务器发送带有附件的文本 / HTML 电子邮件
- [email-templates](https://github.com/niftylettuce/email-templates) - 创建、预览和发送自定义电子邮件
- [MJML](https://github.com/mjmlio/mjml) - 旨在减少创建响应式电子邮件困难的一种标记语言

### 任务队列

- [bull](https://github.com/OptimalBits/bull) - 持续作业和消息队列
- [agenda](https://github.com/rschmukler/agenda) - 基于 MongoDB 的作业调度工具
- [idoit](https://github.com/nodeca/idoit) - 基于 Redis 的具有高级作业控制的队列引擎
- [node-resque](https://github.com/taskrabbit/node-resque) - 基于 Redis 的作业队列
- [rsmq](https://github.com/smrchy/rsmq) - 基于 Redis 的消息队列
- [bee-queue](https://github.com/bee-queue/bee-queue) - 高性能的基于 Redis 的任务队列
- [RedisSMQ](https://github.com/weyoss/redis-smq) - 具有实时监控功能的简单高性能 edis 消息队列
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - 在没有样板文件的情况下构建基于 Amazon 简单队列服务（SQS）的应用程序
- [better-queue](https://github.com/diamondio/better-queue) - 不需要 Redis 的简单高效的作业队列

### Node.js&nbsp;管理

- [n](https://github.com/tj/n) - Node.js 版本控制
- [nave](https://github.com/isaacs/nave) - Node.js 虚拟环境 
- [nodeenv](https://github.com/ekalinin/nodeenv) - 与 Python virtualenv 兼容的Node.js 虚拟环境
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Windows node 版本控制工具
- [nodenv](https://github.com/nodenv/nodenv) - 类似于 Ruby rbenv 的版本管理器，支持自动版本切换

### 自然语言处理

- [retext](https://github.com/wooorm/retext) - 一个可扩展的自然语言系统
- [franc](https://github.com/wooorm/franc) - 检测文本语言
- [leven](https://github.com/sindresorhus/leven) - 使用 Levenshtein 距离算法检测两个字符串之间的差异
- [natural](https://github.com/NaturalNode/natural) - 自然语言设施
- [nlp.js](https://github.com/axa-group/nlp.js) - 构建机器人，具有实体提取、情感分析、自动语言识别等功能

### 进程管理

- [PM2](https://github.com/Unitech/pm2) - 高级进程管理工具
- [nodemon](https://github.com/remy/nodemon) - 监听代码变动并自动重新启动服务器
- [node-mac](https://github.com/coreybutler/node-mac) - 将脚本作为 Mac 守护进程运行并把日志输出到控制台
- [node-linux](https://github.com/coreybutler/node-linux) - 将脚本作为本机系统服务运行并输出日志到 syslog
- [node-windows](https://github.com/coreybutler/node-windows) - 将脚本作为 Windows 服务运行并输出日志到事件查看器
- [supervisor](https://github.com/petruisfan/node-supervisor) - 当脚本崩溃时或者当```*.js``` 文件更改时重新启动脚本
- [Phusion Passenger](https://github.com/phusion/passenger) - 直接嵌入 Nginx 的易用的进程管理工具

### 自动化

- [robotjs](https://github.com/octalmage/robotjs) - 桌面自动化：控制鼠标、键盘和阅读屏幕
- [nut.js](https://github.com/nut-tree/nut.js) - 集成 Jest 的具有图像匹配的跨平台原生 GUI 自动化 / 测试框架

### AST

- [Acorn](https://github.com/ternjs/acorn) - 轻量、快速的 JavaScript 解析器
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - 用于 babel 的 JavaScript 解析工具
- [cherow](https://github.com/cherow/cherow) - 专注于性能和稳定性的 Javascript 解析器

### 静态网站生成

- [Wintersmith](https://github.com/jnordberg/wintersmith) - 灵活、简约、多平台的静态站点生成器
- [Assemble](https://github.com/assemble/assemble/) - 使用 Node.js、Grunt.js 和Yeoman 的静态站点生成器
- [DocPad](https://github.com/docpad/docpad) - 具有动态能力和巨大插件生态系统的静态站点生成器
- [Phenomic](https://github.com/phenomic/phenomic) - 基于 React 和 Webpack 生态系统的现代静态网站生成器
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown 文站点生成器
- [Charge](https://github.com/brandonweiss/charge) - 使用 JSX 和 MDX 的零配置静态站点生成器

### 内容管理系统

- [KeystoneJS](https://github.com/keystonejs/keystone) -基于 Express 和 MongoDB 的 CMS 和 web 应用平台
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - 基于 Express 和 MongoDB 的，强调直观的前端内容编辑和管理的内容管理系统
- [Strapi](https://github.com/strapi/strapi) - 用于构建强大 APIs 的内容管理框架（headless-CMS）
- [Tipe](https://github.com/tipeio/tipe) - 使用 schema 文件构建基于 GraphQL 和 REST API 的面向开发人员的内容管理系统
- [Factor](https://github.com/fiction-com/factor) - 基于 Vue.js 的仪表盘框架和无头 CMS
- [AdminBro](https://github.com/SoftwareBrothers/admin-bro) - 为你所有的资源自动生成管理员界面

### 论坛

- [nodeBB](https://github.com/NodeBB/NodeBB) - 面向现代 web 的论坛平台

### 写博客

- [Ghost](https://github.com/TryGhost/Ghost) - 简单强大的发布平台
- [Hexo](https://github.com/hexojs/hexo) - 快速、简单而强大的博客框架

### 怪诞的

- [cows](https://github.com/sindresorhus/cows) - ASCII cows
- [superb](https://github.com/sindresorhus/superb) - 获取表达 “极好的” 意思的词汇
- [cat-names](https://github.com/sindresorhus/cat-names) - 获取流行的猫名字
- [dog-names](https://github.com/sindresorhus/dog-names) - 获取流行的狗名字
- [superheroes](https://github.com/sindresorhus/superheroes) - 获取超级英雄的名字
- [supervillains](https://github.com/sindresorhus/supervillains) - 获取超级大反派的名字
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - 获取酷炫的 ascii 颜文字
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ```₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”```
- [nerds](https://github.com/SkyHacks/nerds) - 获取宅男话题的数据，例如哈利波特，星战，宝可梦

### 序列化

- [snappy](https://github.com/kesla/node-snappy) - Google Snappy 压缩库的绑定
- [protobuf](https://github.com/dcodeIO/protobuf.js) - 协议缓冲区
- [compactr](https://github.com/compactr/compactr.js) - Compactr 协议

### 其他

- [execa](https://github.com/sindresorhus/execa) - 比 `child_process` 更好
- [cheerio](https://github.com/cheeriojs/cheerio) - 快速, 灵活, 为服务端设计的借鉴了 jQuery 设计的操作工具
- [Electron](https://github.com/atom/electron) - 使用 Web 技术开发跨平台桌面应用 *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [open](https://github.com/sindresorhus/open) - 打开网站、文件、可执行文件等
- [hasha](https://github.com/sindresorhus/hasha) - 使散列变得简单，获取缓冲区/字符串/流/文件的哈希
- [dot-prop](https://github.com/sindresorhus/dot-prop) - 使用 ```.``` 路径方式获取一个套嵌对象的属性
- [onetime](https://github.com/sindresorhus/onetime) - 执行一次性函数
- [mem](https://github.com/sindresorhus/mem) - 记忆函数——一种优化技术，通过缓存相同输入函数的执行结果来加速连续函数调用
- [import-fresh](https://github.com/sindresorhus/import-fresh) - 调用模块时绕开缓存
- [strip-bom](https://github.com/sindresorhus/strip-bom) - 从字符串 / Buffer / Stream中解除 UTF-8 BOM 问题 
- [os-locale](https://github.com/sindresorhus/os-locale) - 获取系统 locale
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 客户端和服务端模块
- [adit](https://github.com/markelog/adit) - SSH 相关工具
- [import-lazy](https://github.com/sindresorhus/import-lazy) - 懒加载一个模块
- [file-type](https://github.com/sindresorhus/file-type) - 获得一个 Buffer 的文件类型
- [Bottleneck](https://github.com/SGrondin/bottleneck) - 速率限制器，使流量控制变得容易
- [ow](https://github.com/sindresorhus/ow) - 函数参数验证
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - 使用原生线程的轻量级 Web Worker API
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 访问系统的剪贴板 (复制和粘贴)
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - 使从二进制发布安装 Node.js C++ 插件更简单的工具
- [opencv](https://github.com/peterbraden/node-opencv) - Javascript 的 OpenCV 封装,计算机图形处理库
- [dotenv](https://github.com/motdotla/dotenv) - 从 .env 文件加载环境变量.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - 从 git 远程仓库获取 tags
- [semver](https://github.com/npm/node-semver) - 语义版本分析器
- [Faker.js](https://github.com/Marak/Faker.js) - 测试数据批量生成工具 （推荐阅读：《[2.8 万 Star！生成虚假内容的神器：faker.js](https://mp.weixin.qq.com/s/DiPDVAUONDb_9DH-gUClVQ)》）
- [nodegit](https://github.com/nodegit/nodegit) - 原生 Node 封装的 Git 工具
- [json-strictify](https://github.com/pigulla/json-strictify) - 安全地将值序列化为 JSON ，不丢失数据或进入无限循环
- [resolve-from](https://github.com/sindresorhus/resolve-from) - 从一个给定的路径执行某个模块的 resolve 方法
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 事件驱动的 web 爬虫程序
- [jsdom](https://github.com/tmpvar/jsdom) - HTML 和 DOM 的 JavaScript 实现
- [hypernova](https://github.com/airbnb/hypernova) - 服务端渲染 JavascSript 视图
- [@sindresorhus/is](https://github.com/sindresorhus/is) - 检查值和类型是否匹配
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - 使用 ```.``` 路径获取、设置或删除 process.env 的嵌套属性
- [emittery](https://github.com/sindresorhus/emittery) - 简单而现代的异步事件发生器
- [node-video-lib](https://github.com/gkozlenko/node-video-lib) - 纯 JavaScript 编写的，用于处理 MP4 和 FLV 视频文件并为 HLS 流创建 MPEG-TS 块的视频工具库
- [basic-ftp](https://github.com/patrickjuchli/basic-ftp) - FTP/FTPS 客户端
- [cashify](https://github.com/xxczaki/cashify) - 汇率转换
- [genepi](https://github.com/Geode-solutions/genepi) - 自动从 C++ 代码中生成 Node.js addon
- [husky](https://github.com/typicode/husky) - 创建 Git 钩子脚本
- [patch-package](https://github.com/ds300/patch-package) - 对 npm 依赖进行修复和保持
- [editly](https://github.com/mifi/editly) - 声明式视频编辑 API
