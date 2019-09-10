# 个人简历展示

此项目开发初衷是为了做一份简致而色彩又不失单调的个人简历主题模板。同时，我发很多求职简历模板对学历都有一个专项来介绍，这对多数专科生并不大友好，反而让自己劣势过于显眼了...

因此，在改写及校调简历主题时，将原有的学历专项置为null，在只在侧边联系栏中写入毕业院校及专业；但也保留了此专项在配置文件，以便荣幸高知的你使用该简历主题，更进一步发挥自己的优势。

主题预览 [hoodieaon/resume](https://hoodiearon.github.io/jsonresume-theme-alon)

开发简历主题，参考项目启发:

* [nuterian/resume](https://github.com/nuterian/resume)
* [github.com/jsonresume](https://github.com/jsonresume)
* [ainsleyc/jsonresume-theme-onepage](https://github.com/ainsleyc/jsonresume-theme-onepage)


## 安装与初始化及部署

**环境：[git](https://git-scm.com/)、[nodejs](https://nodejs.org/zh-cn/)**

1. 安装jsonResume `npm install -g resume-cli`
2. 新建文件夹作为你的简历项目，`resume init`在简历目录进行初始化，填入`name`、`email` 值
3. 使用 `resume serve` 看到此消息jsonResume已经搭建成功了，访问 http://localhost:4000 就行

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

## 个性化定制

* `npm -i jsonresume-theme-alon`下载该主题
* 并使用 `npm install` 安装该主题的相应依赖组件
* 再使用`resume serve`进行部署

**可将resume-cn.json重命名原有的resume.json并替换，进行中字简历的相关配置，也可根据需要对style.css、resume.hbs等进行样式定制。**

# License

[![MIT Licence](https://img.shields.io/badge/mit-license-red.svg)](https://opensource.org/licenses/mit-license.php)
