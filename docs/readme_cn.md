<p align="center">
 <img width="100px" src="https://res.cloudinary.com/ishandutta2007/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="Beautiful Github Homepage" />
 <h2 align="center">Beautiful Github Homepage</h2>
 <p align="center">在你的 README 中获取动态生成的 GitHub 统计信息！</p>
</p>
  <p align="center">
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/actions">
          <img alt="Tests Passing" src="https://github.com/ishandutta2007/beautiful-github-homepage/workflows/Test/badge.svg" />
      </a>
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/graphs/contributors">
          <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/ishandutta2007/beautiful-github-homepage" />
      </a>
      <a href="https://codecov.io/gh/ishandutta2007/beautiful-github-homepage">
          <img alt="Tests Coverage" src="https://codecov.io/gh/ishandutta2007/beautiful-github-homepage/branch/master/graph/badge.svg" />
      </a>
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues">
          <img alt="Issues" src="https://img.shields.io/github/issues/ishandutta2007/beautiful-github-homepage?color=0088ff" />
      </a>
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/pulls">
          <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/ishandutta2007/beautiful-github-homepage?color=0088ff" />
      </a>
      <a href="https://securityscorecards.dev/viewer/?uri=github.com/ishandutta2007/beautiful-github-homepage">
          <img alt="OpenSSF Scorecard" src="https://api.securityscorecards.dev/projects/github.com/ishandutta2007/beautiful-github-homepage/badge" />
      </a>
      <br />
      <br />
      <a href="https://vercel.com?utm\_source=github\_readme\_stats\_team\&utm\_campaign=oss">
          <img src="./powered-by-vercel.svg" />
      </a>
 </p>

  <p align="center">
    <a href="#全部-demos">查看 Demo</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">报告 Bug</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">请求增加功能</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/discussions/1770">常问问题</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/discussions/new?category=q-a">问问题</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français</a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>
<p align="center">喜欢这个项目？请考虑<a href="https://www.paypal.me/ishandutta2007">捐赠</a>来帮助它完善！

# 特性 <!-- omit in toc -->

- [GitHub 统计卡片](#github-统计卡片)
    - [隐藏指定统计](#隐藏指定统计)
    - [将私人项目贡献添加到总提交计数中](#将私人项目贡献添加到总提交计数中)
    - [显示图标](#显示图标)
    - [主题](#主题)
    - [自定义](#自定义)
- [GitHub 更多置顶](#github-更多置顶)
    - [使用细则](#使用细则)
    - [Demo](#demo)
- [热门语言卡片](#热门语言卡片)
    - [使用细则](#使用细则-1)
    - [隐藏指定语言](#隐藏指定语言)
    - [紧凑的语言卡片布局](#紧凑的语言卡片布局)
    - [Demo](#demo-1)
    - [全部 Demos](#全部-demos)
    - [快速提示 (对齐 Repo 卡片)](#快速提示-对齐-repo-卡片)
  - [自己部署](#自己部署)
  - [:sparkling\_heart: 支持这个项目](#sparkling_heart-支持这个项目)

# GitHub 统计卡片

将这行代码复制到你的 markdown 文件中，就是如此简单！

更改 `?username=` 的值为你的 GitHub 用户名。

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

_注: 等级基于用户的统计信息计算得出，详见 [src/calculateRank.js](../src/calculateRank.js)_

### 隐藏指定统计

想要隐藏指定统计信息，你可以调用参数 `?hide=`，其值用 `,` 分隔。

> 选项：`&hide=stars,commits,prs,issues,contribs`

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)


### 将私人项目贡献添加到总提交计数中

你可以使用参数 `?count_private=true` 把私人贡献计数添加到总提交计数中。

_注：如果你是自己部署本项目，私人贡献将会默认被计数，如果不是自己部署，你需要分享你的私人贡献计数。_

> 选项: `&count_private=true`

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&count_private=true)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&count_private=true)

### 显示图标

如果想要显示图标，你可以调用 `show_icons=true` 参数，像这样：

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)

### 主题

你可以通过现有的主题进行卡片个性化，省去[手动自定义](#自定义)的麻烦。

通过调用 `?theme=THEME_NAME` 参数，像这样：

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)


#### 所有现有主题

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/ishandutta2007/image/upload/v1595174536/grs-themes_l4ynja.png" alt="Beautiful Github Homepage Themes" width="600px"/>

你可以预览[所有可用主题](../themes/README.md)或者签出[主题配置文件](../themes/index.js), 而且如果你喜欢, **你也可以贡献新的主题** :D

### 自定义

你可以通过使用 URL 参数的方式，为你的 `Stats Card` 或 `Repo Card` 自定义样式。

常用选项：

- `title_color` - 卡片标题颜色 _（十六进制色码）_
- `text_color` - 内容文本颜色 _（十六进制色码）_
- `icon_color` - 图标颜色（如果可用）_（十六进制色码）_
- `bg_color` - 卡片背景颜色 _（十六进制色码）_ **或者** 以 _angle,start,end_ 的形式渐变
- `hide_border` - 隐藏卡的边框 _(布尔值)_
- `theme` - 主题名称，从[所有可用主题](../themes/README.md)中选择
- `cache_seconds` - 手动设置缓存头 _（最小值: 14400，最大值: 86400）_
- `locale` - 在卡片中设置语言 _(例如 cn, de, es, 等等)_

##### bg_color 渐变

你可以在 bg_color 选项中提供多个逗号分隔的值来呈现渐变，渐变的格式是 :-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> 缓存的注意事项: 如果 fork 数和 star 数 少于 1k , Repo 卡片默认缓存是 4 小时 （14400 秒） ，否则是 2 小时（7200）。另请注意缓存被限制为最短 2 小时，最长 24 小时。

#### 统计卡片专属选项:

- `hide` - 隐藏特定统计信息 _(以逗号分隔)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_
- `show_icons` - _(boolean)_
- `include_all_commits` - 统计总提交次数而不是仅统计今年的提交次数 _(boolean)_
- `count_private` - 统计私人提交 _(boolean)_
- `line_height` - 设置文本之间的行高 _(number)_

#### Repo 卡片专属选项:

- `show_owner` - 显示 Repo 的所有者名字 _(boolean)_

#### 语言卡片专属选项:

- `hide` - 从卡片中隐藏指定语言 _(Comma seperated values)_
- `hide_title` - _(boolean)_
- `layout` - 提供五种布局 `normal` & `compact` & `donut` & `donut-vertical` & `pie` 间切换
- `card_width` - 手动设置卡片的宽度 _(number)_

> :warning: **重要:**
> 如 [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) 所指定，语言名称应使用 uri 转义。
> (例: `c++` 应该是 `c%2B%2B`, `jupyter notebook` 应该是 `jupyter%20notebook`, 等.)

---

# GitHub 更多置顶

GitHub 更多置顶 允许你在使用 GitHub readme profile 时，在个人资料中置顶多于 6 个 repo 。

是的！你不再受限于置顶最多 6 个存储库了。

### 使用细则

复制粘贴这段代码到你的 README 文件中，并更改链接。

端点: `api/pin?username=ishandutta2007&repo=beautiful-github-homepage`

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Demo

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)


使用 [show_owner](#自定义) 变量将 Repo 所有者的用户名包含在内。

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# 热门语言卡片

热门语言卡片显示了 GitHub 用户常用的编程语言。

_注意：热门语言并不表示我的技能水平或类似的水平，它是用来衡量用户在 github 上拥有最多代码的语言的一项指标，它是 beautiful-github-homepage 的新特性_

### 使用细则

将此代码复制粘贴到您的 `README.md` 文件中，并修改链接。

端点: `api/top-langs?username=ishandutta2007`

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

### 隐藏指定语言

可以使用 `?hide=language1,language2` 参数来隐藏指定的语言。

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)

### 紧凑的语言卡片布局

你可以使用 `&layout=compact` 参数来改变卡片的样式。

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Demo

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

- 紧凑布局

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### 全部 Demos

- 默认

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)

- 隐藏指定统计

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)

- 显示图标

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)

- 包含全部提交

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)

- 主题

从[默认主题](#主题)中进行选择

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)

- 渐变

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

- 自定义统计卡片

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)


- 自定义 repo 卡片

```Markdown
[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007\&repo=beautiful-github-homepage\&title_color=fff\&icon_color=f9f9f9\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007\&repo=beautiful-github-homepage\&title_color=fff\&icon_color=f9f9f9\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)


- 热门语言

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### 快速提示 (对齐 Repo 卡片)

你通常无法将图片靠边显示。为此，您可以使用以下方法：

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

<details>
<summary>:eyes: 显示示例</summary>

<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img height=200 align="center" src="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007" />
</a>
<a href="https://github.com/ishandutta2007/convoychat">
  <img height=200 align="center" src="https://beautiful-github-homepage.vercel.app/api/top-langs?username=ishandutta2007&layout=compact&langs_count=8&card_width=320" />
</a>

***

<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/convoychat">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

## 自己部署

#### [查看分步视频教程 作者：@codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

因为 GitHub 的 API 每个小时只允许 5 千次请求，我的 `https://beautiful-github-homepage.vercel.app/api` 很有可能会触发限制。如果你将其托管在自己的 Vercel 服务器上，那么你就不必为此担心。点击 deploy 按钮来开始你的部署！

注意: 从 [#58](https://github.com/ishandutta2007/beautiful-github-homepage/pull/58) 开始，我们应该能够处理超过 5 千次的请求，并且不会出现宕机问题 :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/ishandutta2007/beautiful-github-homepage)

<details>
 <summary>设置 Vercel 的指导</summary>

1. 前往 [vercel.com](https://vercel.com/)
1. 点击 `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. 点击 `Continue with GitHub` 通过 GitHub 进行登录
   ![](https://files.catbox.moe/btd78j.jpeg)
1. 登录 GitHub 并允许访问所有存储库（如果系统这样提示）
1. Fork 这个仓库
1. 返回到你的 [Vercel dashboard](https://vercel.com/dashboard)
1. 选择 `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. 选择 `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. 选择 root 并将所有内容保持不变，并且只需添加名为 PAT_1 的环境变量（如图所示），其中将包含一个个人访问令牌（PAT），你可以在[这里](https://github.com/settings/tokens/new)轻松创建（保留默认，并且只需要命名下，名字随便）
   ![](https://files.catbox.moe/0ez4g7.png)
1. 点击 deploy，这就完成了，查看你的域名就可使用 API 了！

</details>

## :sparkling_heart: 支持这个项目

我尽己所能地进行开源，并且我尽量回复每个在使用项目时需要帮助的人。很明显，这需要时间，但你可以免费享受这些。

然而, 如果你正在使用这个项目并感觉良好，或只是想要支持我继续开发，你可以通过如下方式：

- 在你的 readme 中使用 beautiful-github-homepage 时，链接指向这里 :D
- Star 并 分享这个项目 :rocket:
- [![paypal.me/ishandutta2007](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/ishandutta2007) - 你可以通过 PayPal 一次性捐款. 我多半会买一杯 ~~咖啡~~ 茶. :tea:

谢谢！ :heart:

---

```Markdown
[![https://vercel.com?utm\_source=github\_readme\_stats\_team\&utm\_campaign=oss](powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team\&utm_campaign=oss)
```

[![https://vercel.com?utm\_source=github\_readme\_stats\_team\&utm\_campaign=oss](powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team\&utm_campaign=oss)

欢迎贡献！ <3

用 :heart: 发电，用 JavaScript 制作。
