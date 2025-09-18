## 🧾 Resume Generator

### To QXX, my love:

### To the world you may be one person, but to one person you are the world. I wish things couldve been different. I love you x2.

在线简历生成器。首先感谢作者visiky的内容，实在是太棒了，哦我的上帝。✨ [在线编辑](https://visiky.github.io/resume)

## 更改了template2的index.tsx，使之更加符合校招的模板格式，其中删除了自我介绍部分，留给你面试的时候和HR掰扯
## 修改了package.json关于script中关于gastby build的字段，方便windows用户部署（逆天版本不兼容）

内置 3 套模板，支持**自定义主题颜色**、**自定义模块标题**、**国际化(中/英)** 等.

|默认模板| 简易模板| 简易模板2（适用于多页）|
| -------------------------------- | --------------------------------------------------|----------------------- |
| <img src="https://user-images.githubusercontent.com/15646325/147406773-d1583d83-b4ed-496a-9b7c-2fca8a5fc624.png" height="280" />|<img src="https://user-images.githubusercontent.com/15646325/147406862-19ac2b2a-6dcf-466f-a0dd-53fd1a6abccd.png" height="280" />| <img src="https://user-images.githubusercontent.com/15646325/147406903-19529fe9-9ef8-4877-8165-b2fad0e3b48a.png" height="280" />|
|[Live Demo](https://visiky.github.io/resume?user=visiky)  |[Live Demo](https://visiky.github.io/resume?user=visiky&template=template2)|[Live Demo](https://visiky.github.io/resume?user=visiky&template=template3) |

## 如何使用（How to use）

**方式 1:**

在线编辑 -> 导出配置 -> 存储“简历信息”在个人 github special 仓库下（例如: [visiky/visiky](https://github.com/visiky/visiky/blob/master/resume.json)）

**方式 2:**

直接创建一个 `resume.json` 文件在自己的 special 仓库下 (内容参考: [visiky/visiky](https://github.com/visiky/visiky/blob/master/resume.json)).

**最后**

访问 https://Lvisxwj.github.io/resume?user={user}&branch={branch}

参数说明:

| 参数   | 描述          | 默认值       |
| ------ | ------------- | ------------ |
| user   | github 用户名 | 必选         |
| template | 模板        | 默认: template1 |
| branch | 分支名        | 默认: master |
| mode | 模式        | 备注: 默认为‘只读’模式，设置为: `mode=edit` 即可进入编辑模式 |
| lang | 语言        | 默认: zh-CN |

## 本地开发（Local develop）

```bash
# pnpm required, to see: https://pnpm.io/installation
# Install dependencies
pnpm install
# Then, start
npm start
```

## ✨ Recommendation

- [resumemaker](https://www.resumemaker.online/es.php)
- [Geek Resume - Pure Markdown, an online resume editor for developer.](https://www.jijian.press/)
