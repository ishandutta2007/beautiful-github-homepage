<p align="center">
    <img width="100px" src="https://res.cloudinary.com/ishandutta2007/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="Beautiful Github Homepage" />
  <h2 align="center">Beautiful Github Homepage</h2>
  <p align="center">Get dynamically generated GitHub stats on your READMEs!</p>
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
      <a href="https://vercel.com?utm\_source=beautiful\_github\_homepage\_team\&utm\_campaign=oss">
          <img src="./powered-by-vercel.svg" />
      </a>
  </p>

  <p align="center">
      <a href="#all-demos">View Demo</a>
      ·
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Report Bug</a>
      ·
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Request Feature</a>
      ·
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/discussions/1770">FAQ</a>
      ·
      <a href="https://github.com/ishandutta2007/beautiful-github-homepage/discussions/new?category=q-a">Ask Question</a>
  </p>
  <p align="center">
      <a href="/docs/readme_fr.md">Français </a>
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
      ·
      <a href="/docs/readme_nl.md">Nederlands</a>
      ·
      <a href="/docs/readme_np.md">नेपाली</a>
      ·
      <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
  </p>

  <p align="center">Please note that documentation translations may be outdated, try to use english documentation if possible.</p>

  <p align="center">Love the project? Please consider <a href="https://www.paypal.me/ishandutta2007">donating</a> to help it improve!</p>
</p>

# Features <!-- omit in toc -->

- [GitHub Stats Card](#github-stats-card)
    - [Hiding individual stats](#hiding-individual-stats)
    - [Showing additional individual stats](#showing-additional-individual-stats)
    - [Showing icons](#showing-icons)
    - [Themes](#themes)
    - [Customization](#customization)
- [GitHub Extra Pins](#github-extra-pins)
    - [Usage](#usage)
    - [Demo](#demo)
- [GitHub Gist Pins](#github-gist-pins)
    - [Usage](#usage-1)
    - [Demo](#demo-1)
- [Top Languages Card](#top-languages-card)
    - [Usage](#usage-2)
    - [Language stats algorithm](#language-stats-algorithm)
    - [Exclude individual repositories](#exclude-individual-repositories)
    - [Hide individual languages](#hide-individual-languages)
    - [Show more languages](#show-more-languages)
    - [Compact Language Card Layout](#compact-language-card-layout)
    - [Donut Chart Language Card Layout](#donut-chart-language-card-layout)
    - [Donut Vertical Chart Language Card Layout](#donut-vertical-chart-language-card-layout)
    - [Pie Chart Language Card Layout](#pie-chart-language-card-layout)
    - [Hide Progress Bars](#hide-progress-bars)
    - [Demo](#demo-2)
- [WakaTime Stats Card](#wakatime-stats-card)
    - [Demo](#demo-3)
- [All Demos](#all-demos)
  - [Quick Tip (Align The Cards)](#quick-tip-align-the-cards)
- [Deploy on your own](#deploy-on-your-own)
  - [On Vercel](#on-vercel)
    - [:film\_projector: Check Out Step By Step Video Tutorial By @codeSTACKr](#film_projector-check-out-step-by-step-video-tutorial-by-codestackr)
  - [On other platforms](#on-other-platforms)
  - [Disable rate limit protections](#disable-rate-limit-protections)
  - [Keep your fork up to date](#keep-your-fork-up-to-date)
- [:sparkling\_heart: Support the project](#sparkling_heart-support-the-project)

# Important Notices <!-- omit in toc -->

> [!IMPORTANT]\
> Since the GitHub API only [allows 5k requests per hour per user account](https://docs.github.com/en/graphql/overview/resource-limitations), the public Vercel instance hosted on `https://beautiful-github-homepage.vercel.app/api` could possibly hit the rate limiter . We use caching to prevent this from happening (see https://github.com/ishandutta2007/beautiful-github-homepage#common-options). You can turn off these rate limit protections by deploying [your own Vercel instance](#disable-rate-limit-protections).

<img alt="Uptime Badge" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fbeautiful-github-homepage-git-monitoring-beautiful-github-homepage-team.vercel.app%2Fapi%2Fstatus%2Fup%3Ftype%3Dshields">

> [!IMPORTANT]\
> We're a small team, and to prioritize, we rely on upvotes :+1:. We use Top issues dashboard for tracking community demand . Do not hesitate to upvote the issues and pull requests you are interested in. We will work on the most upvoted first.

# GitHub Stats Card

Copy-paste this into your markdown content, and that is it. Simple!

Change the `?username=` value to your GitHub username.

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


> [!WARNING]\
> By default, the stats card only shows statistics like stars, commits and pull requests from public repositories. To show private statistics on the stats card, you should [deploy your own instance](#deploy-on-your-own) using your own GitHub API token.

> [!NOTE]\
> Available ranks are S (top 1%), A+ (12.5%), A (25%), A- (37.5%), B+ (50%), B (62.5%), B- (75%), C+ (87.5%) and C (everyone). This ranking scheme is based on the [Japanese academic grading](https://wikipedia.org/wiki/Academic_grading_in_Japan) system. The global percentile is calculated as a weighted sum of percentiles for each statistic (number of commits, pull requests, reviews, issues, stars and followers), based on the cumulative distribution function of the [exponential](https://wikipedia.org/wiki/exponential_distribution) and the [log-normal](https://wikipedia.org/wiki/Log-normal_distribution) distributions. The implementation can be investigated at [src/calculateRank.js](https://github.com/ishandutta2007/beautiful-github-homepage/blob/master/src/calculateRank.js). The circle around the rank shows 100 minus the global percentile.

### Hiding individual stats

You can pass a query parameter `&hide=` to hide any specific stats with comma-separated values.

> Options: `&hide=stars,commits,prs,issues,contribs`

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)
```

![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)


### Showing additional individual stats

You can pass a query parameter `&show=` to show any specific additional stats with comma-separated values.

> Options: `&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage`

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Showing icons

To enable icons, you can pass `&show_icons=true` in the query param, like so:

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Themes

With inbuilt themes, you can customize the look of the card without doing any [manual customization](#customization).

Use `&theme=THEME_NAME` parameter like so :

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)

#### All inbuilt themes

Beautiful Github Homepage comes with several built-in themes (e.g. `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`).

<img src="https://res.cloudinary.com/ishandutta2007/image/upload/v1595174536/grs-themes_l4ynja.png" alt="Beautiful Github Homepage Themes" width="600px"/>

You can look at a preview for [all available themes](themes/README.md) or checkout the [theme config file](themes/index.js). Please note that we paused addition of new themes to decrease maintenance efforts, all pull requests related to new themes will be closed.

#### Responsive Card Theme

```Markdown
[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)


```md
[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)


Since GitHub will re-upload the cards and serve them from their [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), we can not infer the browser/GitHub theme on the server side. There are, however, four methods you can use to create dynamics themes on the client side.

##### Use the transparent theme

We have included a `transparent` theme that has a transparent background. This theme is optimized to look good on GitHub's dark and light default themes. You can enable this theme using the `&theme=transparent` parameter like so:

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=transparent)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=transparent)](https://github.com/ishandutta2007/beautiful-github-homepage)


<details>
<summary>:eyes: Show example</summary>

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=transparent)](https://github.com/ishandutta2007/beautiful-github-homepage)

</details>

##### Add transparent alpha channel to a themes bg\_color

You can use the `bg_color` parameter to make any of [the available themes](themes/README.md) transparent. This is done by setting the `bg_color` to a color with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&bg_color=00000000)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&bg_color=00000000)](https://github.com/ishandutta2007/beautiful-github-homepage)


<details>
<summary>:eyes: Show example</summary>

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&bg_color=00000000)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&bg_color=00000000)](https://github.com/ishandutta2007/beautiful-github-homepage)

</details>

##### Use GitHub's theme context tag

You can use [GitHub's theme context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags to switch the theme based on the user GitHub theme automatically. This is done by appending `#gh-dark-mode-only` or `#gh-light-mode-only` to the end of an image URL. This tag will define whether the image specified in the markdown is only shown to viewers using a light or a dark GitHub theme:

```md
[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)


```md
[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)


<details>
<summary>:eyes: Show example</summary>

```md
[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Dark](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)

```md
[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats-Light](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/ishandutta2007/beautiful-github-homepage)

</details>

##### Use GitHub's new media feature

You can use [GitHub's new media feature](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML to specify whether to display images for light or dark themes. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<picture>
  <source
    srcset="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true" />
</picture>
```

<details>
<summary>:eyes: Show example</summary>

<picture>
  <source
    srcset="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true" />
</picture>

</details>

### Customization

You can customize the appearance of all your cards however you wish with URL parameters.

#### Common Options

*   `title_color` - Card's title color *(hex color)*. Default: `2f80ed`.
*   `text_color` - Body text color *(hex color)*. Default: `434d58`.
*   `icon_color` - Icons color if available *(hex color)*. Default: `4c71f2`.
*   `border_color` - Card's border color *(hex color)*. Default: `e4e2e2` (Does not apply when `hide_border` is enabled).
*   `bg_color` - Card's background color *(hex color)* **or** a gradient in the form of *angle,start,end*. Default: `fffefe`
*   `hide_border` - Hides the card's border *(boolean)*. Default: `false`
*   `theme` - Name of the theme, choose from [all available themes](themes/README.md). Default: `default` theme.
*   `cache_seconds` - Sets the cache header manually *(min: 21600, max: 86400)*. Default: `21600 seconds (6 hours)`.
*   `locale` - Sets the language in the card, you can check full list of available locales [here](#available-locales). Default: `en`.
*   `border_radius` - Corner rounding on the card. Default: `4.5`.

> [!WARNING]\
> We use caching to decrease the load on our servers . Our cards have a default cache of 6 hours (21600 seconds). Also, note that the cache is clamped to a minimum of 6 hours and a maximum of 24 hours. If you want the data on your statistics card to be updated more often you can [deploy your own instance](#deploy-on-your-own) and set [environment variable](#disable-rate-limit-protections) `CACHE_SECONDS` to a value of your choosing.

##### Gradient in bg\_color

You can provide multiple comma-separated values in the bg\_color option to render a gradient with the following format:

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

##### Available locales

Here is a list of all available locales:

<table>
<tr><td>

| Code | Locale |
| --- | --- |
| `cn` | Chinese |
| `zh-tw` | Chinese (Taiwan) |
| `ar` | Arabic |
| `cs` | Czech |
| `de` | German |
| `en` | English |
| `bn` | Bengali |
| `es` | Spanish |
| `fr` | French |
| `hu` | Hungarian |

</td><td>

| Code | Locale |
| --- | --- |
| `it` | Italian |
| `ja` | Japanese |
| `kr` | Korean |
| `nl` | Dutch |
| `pt-pt` | Portuguese (Portugal) |
| `pt-br` | Portuguese (Brazil) |
| `np` | Nepali |
| `el` | Greek |
| `ru` | Russian |
| `uk-ua` | Ukrainian |

</td><td>

| Code | Locale |
| --- | --- |
| `id` | Indonesian |
| `ml` | Malayalam |
| `my` | Burmese |
| `sk` | Slovak |
| `tr` | Turkish |
| `pl` | Polish |
| `uz` | Uzbek |
| `vi` | Vietnamese |
| `se` | Swedish |

</td></tr>
</table>

If we don't support your language, please consider contributing! You can find more information about how to do it in our [contributing guidelines](CONTRIBUTING.md#translations-contribution).

#### Stats Card Exclusive Options

*   `hide` - Hides the [specified items](#hiding-individual-stats) from stats *(Comma-separated values)*. Default: `[] (blank array)`.
*   `hide_title` - *(boolean)*. Default: `false`.
*   `card_width` - Sets the card's width manually *(number)*. Default: `500px  (approx.)`.
*   `hide_rank` - *(boolean)* hides the rank and automatically resizes the card width. Default: `false`.
*   `rank_icon` - Shows alternative rank icon (i.e. `github`, `percentile` or `default`). Default: `default`.
*   `show_icons` - *(boolean)*. Default: `false`.
*   `include_all_commits` - Counts total commits instead of just the current year commits *(boolean)*. Default: `false`.
*   `line_height` - Sets the line height between text *(number)*. Default: `25`.
*   `exclude_repo` - Excludes stars from specified repositories *(Comma-separated values)*. Default: `[] (blank array)`.
*   `custom_title` - Sets a custom title for the card. Default:  `<username> GitHub Stats`.
*   `text_bold` - Uses bold text *(boolean)*. Default: `true`.
*   `disable_animations` - Disables all animations in the card *(boolean)*. Default: `false`.
*   `ring_color` - Color of the rank circle *(hex color)*. Defaults to the theme ring color if it exists and otherwise the title color.
*   `number_format` - Switches between two available formats for displaying the card values `short` (i.e. `6.6k`) and `long` (i.e. `6626`). Default: `short`.
*   `show` - Shows [additional items](#showing-additional-individual-stats) on stats card (i.e. `reviews`, `discussions_started`, `discussions_answered`, `prs_merged` or `prs_merged_percentage`) *(Comma-separated values)*. Default: `[] (blank array)`.

> [!NOTE]\
> When hide\_rank=`true`, the minimum card width is 270 px + the title length and padding.

#### Repo Card Exclusive Options

*   `show_owner` - Shows the repo's owner name *(boolean)*. Default: `false`.

#### Gist Card Exclusive Options

*   `show_owner` - Shows the gist's owner name *(boolean)*. Default: `false`.

#### Language Card Exclusive Options

*   `hide` - Hides the languages specified from the card *(Comma-separated values)*. Default: `[] (blank array)`.
*   `hide_title` - *(boolean)*. Default: `false`.
*   `layout` - Switches between five available layouts `normal` & `compact` & `donut` & `donut-vertical` & `pie`. Default: `normal`.
*   `card_width` - Sets the card's width manually *(number)*. Default `300`.
*   `langs_count` - Shows more languages on the card, between 1-20 *(number)*. Default: `5` for `normal` and `donut`, `6` for other layouts.
*   `exclude_repo` - Excludes specified repositories *(Comma-separated values)*. Default: `[] (blank array)`.
*   `custom_title` - Sets a custom title for the card *(string)*. Default `Most Used Languages`.
*   `disable_animations` - Disables all animations in the card *(boolean)*. Default: `false`.
*   `hide_progress` - Uses the compact layout option, hides percentages, and removes the bars. Default: `false`.
*   `size_weight` - Configures language stats algorithm *(number)* (see [Language stats algorithm](#Language-stats-algorithm)), defaults to 1.
*   `count_weight` - Configures language stats algorithm *(number)* (see [Language stats algorithm](#Language-stats-algorithm)), defaults to 0.

> [!WARNING]\
> Language names should be URI-escaped, as specified in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
> (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) You can use
> [urlencoder.org](https://www.urlencoder.org/) to help you do this automatically.

#### WakaTime Card Exclusive Options

*   `hide` - Hides the languages specified from the card *(Comma-separated values)*. Default: `[] (blank array)`.
*   `hide_title` - *(boolean)*. Default `false`.
*   `line_height` - Sets the line height between text *(number)*. Default `25`.
*   `hide_progress` - Hides the progress bar and percentage *(boolean)*. Default `false`.
*   `custom_title` - Sets a custom title for the card *(string)*. Default `WakaTime Stats`.
*   `layout` - Switches between two available layouts `default` & `compact`.  Default `default`.
*   `langs_count` - Limits the number of languages on the card, defaults to all reported languages *(number)*.
*   `api_domain` - Sets a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi) *(string)*. Default `Waka API`.

***

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=ishandutta2007&repo=beautiful-github-homepage`

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```md
![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007\&repo=beautiful-github-homepage)
```

![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007\&repo=beautiful-github-homepage)

Use [show\_owner](#repo-card-exclusive-options) query option to include the repo's owner username

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007\&repo=beautiful-github-homepage\&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007\&repo=beautiful-github-homepage\&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# GitHub Gist Pins

GitHub gist pins allow you to pin gists in your GitHub profile using a GitHub readme profile.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/gist?id=bbfce31e0217a3689c8d961a356cb10d`

```md
[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```md
[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)

Use [show\_owner](#gist-card-exclusive-options) query option to include the gist's owner username

```md
[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d\&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d\&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# Top Languages Card

The top languages card shows a GitHub user's most frequently used languages.

> [!WARNING]\
> By default, the language card shows language results only from public repositories. To include languages used in private repositories, you should [deploy your own instance](#deploy-on-your-own) using your own GitHub API token.

> [!NOTE]\
> Top Languages does not indicate the user's skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. It is a new feature of beautiful-github-homepage.

> [!WARNING]\
> This card shows languages usage only inside your own non-forked repositories, not depending from who is the author of the commits. It does not include your contributions into another users/organizations repositories. Currently there are no way to get this data from GitHub API. If you want this behavior to be improved you can support [this feature request](https://github.com/orgs/community/discussions/18230) created by [@rickstaa](https://github.com/rickstaa) inside GitHub Community.

> [!WARNING]\
> Currently this card shows data only about first 100 repositories. This is because GitHub API limitations which cause downtimes of public instance . In future this behavior will be improved by releasing GitHub action or providing environment variable for user's own instances.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=ishandutta2007`

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Language stats algorithm

We use the following algorithm to calculate the languages percentages on the language card:

```js
ranking_index = (byte_count ^ size_weight) * (repo_count ^ count_weight)
```

By default, only the byte count is used for determining the languages percentages shown on the language card (i.e. `size_weight=1` and `count_weight=0`). You can, however, use the `&size_weight=` and `&count_weight=` options to weight the language usage calculation. The values must be positive real numbers. [More details about the algorithm can be found here](https://github.com/ishandutta2007/beautiful-github-homepage/issues/1600#issuecomment-1046056305).

*   `&size_weight=1&count_weight=0` - *(default)* Orders by byte count.
*   `&size_weight=0.5&count_weight=0.5` - *(recommended)* Uses both byte and repo count for ranking
*   `&size_weight=0&count_weight=1` - Orders by repo count

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&size_weight=0.5&count_weight=0.5)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&size_weight=0.5&count_weight=0.5)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Exclude individual repositories

You can use the `&exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&exclude_repo=beautiful-github-homepage,ishandutta2007.github.io)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&exclude_repo=beautiful-github-homepage,ishandutta2007.github.io)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Hide individual languages

You can use `&hide=language1,language2` parameter to hide individual languages.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 20 (inclusive). By default it was set to `5` for `normal` & `donut` and `6` for other layouts.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&langs_count=8)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&langs_count=8)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Donut Chart Language Card Layout

You can use the `&layout=donut` option to change the card design.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=donut)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=donut)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Donut Vertical Chart Language Card Layout

You can use the `&layout=donut-vertical` option to change the card design.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=donut-vertical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=donut-vertical)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Pie Chart Language Card Layout

You can use the `&layout=pie` option to change the card design.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=pie)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=pie)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Hide Progress Bars

You can use the `&hide_progress=true` option to hide the percentages and the progress bars (layout will be automatically set to `compact`).

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


*   Compact layout

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)


*   Donut Chart layout

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=donut)](https://github.com/ishandutta2007/beautiful-github-homepage)]
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=donut)](https://github.com/ishandutta2007/beautiful-github-homepage)

*   Donut Vertical Chart layout

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=donut-vertical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=donut-vertical)](https://github.com/ishandutta2007/beautiful-github-homepage)

*   Pie Chart layout

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=pie)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&layout=pie)](https://github.com/ishandutta2007/beautiful-github-homepage)

*   Hidden progress bars

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007\&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


# WakaTime Stats Card

> [!WARNING]\
> Please be aware that we currently only show data from WakaTime profiles that are public. You therefore have to make sure that **BOTH** `Display code time publicly` and `Display languages, editors, os, categories publicly` are enabled.

Change the `?username=` value to your [WakaTime](https://wakatime.com) username.

```md
[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

### Demo

```Markdown
[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)

```Markdown
[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs\&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs\&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Compact layout

```Markdown
[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs\&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Felipe Figueroa's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs\&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

***

# All Demos

### Default

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Hiding specific stats

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Showing additional stats

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Showing icons

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&hide=issues\&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&hide=issues\&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Shows Github logo instead rank level

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&rank_icon=github)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&rank_icon=github)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Shows user rank percentile instead of rank level

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&rank_icon=percentile)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&rank_icon=percentile)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Customize Border Color

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&border_color=2e4058)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&border_color=2e4058)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Include All Commits

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Themes

Choose from any of the [default themes](#themes)

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&show_icons=true\&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Gradient

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&bg_color=30,e96443,904e95\&title_color=fff\&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007\&bg_color=30,e96443,904e95\&title_color=fff\&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Customizing stats card

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&show_icons=true\&title_color=fff\&icon_color=79ff97\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&show_icons=true\&title_color=fff\&icon_color=79ff97\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Setting card locale

```Markdown
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007\&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Customizing repo card

```Markdown
[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007\&repo=beautiful-github-homepage\&title_color=fff\&icon_color=f9f9f9\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007\&repo=beautiful-github-homepage\&title_color=fff\&icon_color=f9f9f9\&text_color=9f9f9f\&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Gist card

```Markdown
[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Customizing gist card

```Markdown
[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d&theme=calm)](https://github.com/ishandutta2007/beautiful-github-homepage)

```

[![Gist Card](https://beautiful-github-homepage.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d&theme=calm)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Top languages

```Markdown
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

### WakaTime card

```Markdown
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)


***

## Quick Tip (Align The Cards)

By default, GitHub does not lay out the cards side by side. To do that, you can use this approach:

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img height=200 align="center" src="https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007" />
</a>
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img height=200 align="center" src="https://beautiful-github-homepage.vercel.app/api/top-langs?username=ishandutta2007&layout=compact&langs_count=8&card_width=320" />
</a>
```

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

<details>
<summary>:eyes: Show example</summary>

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

</details>

# Deploy on your own

## On Vercel

### :film\_projector: [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Since the GitHub API only allows 5k requests per hour, my `https://beautiful-github-homepage.vercel.app/api` could possibly hit the rate limiter. If you host it on your own Vercel server, then you do not have to worry about anything. Click on the deploy button to get started!

> [!NOTE]\
> Since [#58](https://github.com/ishandutta2007/beautiful-github-homepage/pull/58), we should be able to handle more than 5k requests and have fewer issues with downtime :grin:.

> [!NOTE]\
> If you are on the [Pro (i.e. paid)](https://vercel.com/pricing) Vercel plan, the [maxDuration](https://vercel.com/docs/concepts/projects/project-configuration#value-definition) value found in the [vercel.json](https://github.com/ishandutta2007/beautiful-github-homepage/blob/master/vercel.json) can be increased when your Vercel instance frequently times out during the card request. You are advised to keep this value lower than `30` seconds to prevent high memory usage.

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/ishandutta2007/beautiful-github-homepage)

<details>
 <summary><b>:hammer_and_wrench: Step-by-step guide on setting up your own Vercel instance</b></summary>

1.  Go to [vercel.com](https://vercel.com/).
2.  Click on `Log in`.
    ![](https://files.catbox.moe/pcxk33.png)
3.  Sign in with GitHub by pressing `Continue with GitHub`.
    ![](https://files.catbox.moe/b9oxey.png)
4.  Sign in to GitHub and allow access to all repositories if prompted.
5.  Fork this repo.
6.  Go back to your [Vercel dashboard](https://vercel.com/dashboard).
7.  To import a project, click the `Add New...` button and select the `Project` option.
    ![](https://files.catbox.moe/3n76fh.png)
8.  Click the `Continue with GitHub` button, search for the required Git Repository and import it by clicking the `Import` button. Alternatively, you can import a Third-Party Git Repository using the `Import Third-Party Git Repository ->` link at the bottom of the page.
    ![](https://files.catbox.moe/mg5p04.png)
9.  Create a personal access token (PAT) [here](https://github.com/settings/tokens/new) and enable the `repo` and `user` permissions (this allows access to see private repo and user stats).
10. Add the PAT as an environment variable named `PAT_1` (as shown).
    ![](https://files.catbox.moe/0yclio.png)
11. Click deploy, and you're good to go. See your domains to use the API!

</details>

## On other platforms

> [!WARNING]\
> This way of using GRS is not officially supported and was added to cater to some particular use cases where Vercel could not be used (e.g. [#2341](https://github.com/ishandutta2007/beautiful-github-homepage/discussions/2341)). The support for this method, therefore, is limited.

<details>
<summary><b>:hammer_and_wrench: Step-by-step guide for deploying on other platforms</b></summary>

1.  Fork or clone this repo as per your needs
2.  Add `express` to the dependencies section of `package.json`
    <https://github.com/ishandutta2007/beautiful-github-homepage/blob/ba7c2f8b55eac8452e479c8bd38b044d204d0424/package.json#L54-L61>
3.  Run `npm i` if needed (initial setup)
4.  Run `node express.js` to start the server, or set the entry point to `express.js` in `package.json` if you're deploying on a managed service
    <https://github.com/ishandutta2007/beautiful-github-homepage/blob/ba7c2f8b55eac8452e479c8bd38b044d204d0424/package.json#L11>
5.  You're done 🎉
    </details>

## Disable rate limit protections

Beautiful Github Homepage contains several Vercel environment variables that can be used to remove the rate limit protections:

*   `CACHE_SECONDS`: This environment variable takes precedence over our cache minimum and maximum values and can circumvent these values for self Hosted Vercel instances.

See [the Vercel documentation](https://vercel.com/docs/concepts/projects/environment-variables) on adding these environment variables to your Vercel instance.

## Keep your fork up to date

You can keep your fork, and thus your private Vercel instance up to date with the upstream using GitHub's [Sync Fork button](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork). You can also use the [pull](https://github.com/wei/pull) package created by [@wei](https://github.com/wei) to automate this process.

# :sparkling\_heart: Support the project

I open-source almost everything I can and try to reply to everyone needing help using these projects. Obviously,
this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are a few ways you can do it:

*   Giving proper credit when you use beautiful-github-homepage on your readme, linking back to it :D
*   Starring and sharing the project :rocket:
*   You can [Sponsor](https://github.com/sponsors/ishandutta2007) or make one-time donations via [![paypal.me/ishandutta2007](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/ishandutta2007) or if you can't do either as a bare minimum star this repo and follow me as a means to thank me.

Thanks! :heart:

***

Contributions are welcome! <3
