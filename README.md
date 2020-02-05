# 个人简历展示

此项目开发初衷是为了做一份简致而色彩又不失单调的个人简历主题模板。同时，我发现很多求职简历模板对学历都有一个专项来介绍，这对多数专科生并不大友好，反而让自己劣势过于显眼了...

因此，在改写及校调简历主题时，将原有的学历专项置为null，在只在侧边联系栏中写入毕业院校及专业；但也保留了此专项在配置文件，若是高知的你使用该简历主题，更进一步发挥自己的优势。

主题预览 [hoochanlon/resume](https://hoochanlon.github.io/jsonresume-theme-mix)

## 安装与初始化及部署

**环境：[git](https://git-scm.com/)、[nodejs](https://nodejs.org/zh-cn/)**

1. 安装jsonResume `npm install -g resume-cli`
2. 新建文件夹作为你的简历项目，`resume init`在简历目录进行初始化，填入`name`、`email` 值
3. `npm install`（不安装node module依赖主题效果将会失效）
4. 使用 `resume serve` 看到此消息jsonResume已经搭建成功了，访问 http://localhost:4000 就行

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

## 个性化定制

* `npm i jsonresume-theme-mix`下载该主题
* 在 node_modules模块中，找到`jsonresume-theme-mix`并进入
* 最后在主题目录中使用`resume serve`进行部署即可

可在resume.json字段中填入符合自身的简历介绍文字，也可根据需要对style.css、resume.hbs等进行样式定制。

注：若主题脱离node_modules环境，则需要`npm install`重新安装依赖模块呈现效果

[npm/jsonresume-theme-mix/readme](https://www.npmjs.com/package/jsonresume-theme-mix)

## 希望对初涉社会求职的朋友们能有所帮助

* [如何写一份优秀的前端简历](https://github.com/nzbin/resume-boilerplate)
* [apachecn/TI-Analysis](https://github.com/apachecn/TI-Analysis) 
* [同济大学-博士-王荣昌 给初涉社会年轻人的忠告](http://blog.sciencenet.cn/blog-348492-375365.html)
* [知乎-有什么是你面试很多次都失败后才知道的？](https://www.zhihu.com/question/290543744/answer/620486019?utm_source=qq&utm_medium=social&utm_oi=1155092701455159296)

# License

[![MIT Licence](https://img.shields.io/badge/mit-license-red.svg)](https://opensource.org/licenses/mit-license.php)

<!-- 
## 碰壁及失业走所过来的话

就业相对来说并不是易事，何况还有招转培等各方面的陷阱，这大大增加了找工作的难度；总结下自己所能，概述出自己所能占职业需求技能的总占比，再结合搜索、问答论坛对自己所长的一个专业方向定位的相关回答，分析出自己的所能优势的所在职业定位。

分析出自己的所能优势的所在职业定位，并求职投递该方向。简历展示的技能呈现的效果，是否符合了对方的用人需求，不知道该写什么，用企业网站所示的成功案例，以彼之道还施彼身；当然前提是需要有这方面的知识原理储备。不了解的知识原理的话，不过 —— 还可以学习啊！学着学着自然就会了。

期望职位是否满足该职位的实际需求，又存在多少落差值
通过事件展示自己所长解决了该企业存在的需求难题
尝试工作基层职位，体会一段社会生活、多接触人和事，认真体会感悟，这样就不会太过理想化

太过理想化，不考虑实际情况，只会越来越荒诞 
-->
