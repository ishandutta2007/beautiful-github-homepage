<p align="center">
 <img width="100px" src="https://res.cloudinary.com/ishandutta2007/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="Beautiful Github Homepage" />
 <h2 align="center">Beautiful Github Homepage</h2>
 <p align="center">Readme'lerinizde dinamik olarak oluşturulmuş GitHub istatistikleri alın!</p>
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
  </p>

  <p align="center">
    <a href="#demo">Demo</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Hata İlet</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Özellik Talep Et</a>
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
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>
<p align="center">Projeyi sevdiniz mi? Daha da gelişmesi için lütfen <a href="https://www.paypal.me/ishandutta2007">bağış</a> yapın!

# Features <!-- omit in toc -->

- [GitHub İstatistikler Kartı](#github-i̇statistikler-kartı)
    - [Bazı İstatitistikleri Gizleme](#bazı-i̇statitistikleri-gizleme)
    - [Özel Katkı Sayısını Toplam Commit Sayısına Ekleme](#özel-katkı-sayısını-toplam-commit-sayısına-ekleme)
    - [İkonları Göstermek](#i̇konları-göstermek)
    - [Temalar](#temalar)
    - [Özelleştirmeler](#özelleştirmeler)
- [GitHub Ekstra Pinler](#github-ekstra-pinler)
    - [Kullanım](#kullanım)
    - [Demo](#demo)
- [En Çok Kullanılan Diller](#en-çok-kullanılan-diller)
    - [Kullanım](#kullanım-1)
    - [Belirli Repoları Çıkartın](#belirli-repoları-çıkartın)
    - [Belirli Dilleri Çıkartın](#belirli-dilleri-çıkartın)
    - [Daha Fazla Dil Gösterin](#daha-fazla-dil-gösterin)
    - [Kompakt Dil Kartı Düzeni](#kompakt-dil-kartı-düzeni)
    - [Demo](#demo-1)
- [WakaTime Haftalık İstatistikler](#wakatime-haftalık-i̇statistikler)
    - [Demo](#demo-2)
    - [Tüm Demolar](#tüm-demolar)
    - [Hızlı İpucu (Repo Kartları Hizlayın)](#hızlı-i̇pucu-repo-kartları-hizlayın)
  - [Kendi Vercel Örneğinizde Yayınlayın](#kendi-vercel-örneğinizde-yayınlayın)
  - [:sparkling\_heart: Projeyi Destekleyin](#sparkling_heart-projeyi-destekleyin)

# GitHub İstatistikler Kartı

Alt kısımdaki kodu Kopyalayın ve yapıştırın. İşte bu kadar. Çok basit!

`?username=` değerini kendi GitHub kullanıcı adınız ile değiştirin.

```md
[![Ishan'nın GitHub İstatistikleri](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

_Not: Şu sıralamalar mevcut: S+ (en üst 1%), S (en üst 25%), A++ (en üst 45%), A+ (en üst 60%), and B+ (herkes).
Buradaki değerler [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) ile hesaplanırken; commitler, katkılar, hatalar, yıldızlar, çekme istekleri, takipçiler ve sahip olunan depolar (repository) göz önünde bulundurulamaktadır.
Uygulamanın yapısı [src/calculateRank.js](./src/calculateRank.js)'te daha detaylı incelenebilir._

### Bazı İstatitistikleri Gizleme

Bazı belirli istatistikleri gizlemek için `?hide=` paremetresi içerisinde virgülle ayırarak gönderebilirsiniz.

> Örnek: `&hide=stars,commits,prs,issues,contribs`

```md
[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&hide=contribs,prs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&hide=contribs,prs)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Özel Katkı Sayısını Toplam Commit Sayısına Ekleme

Özel (private) olarak geliştirdiğiniz depolardaki commit sayınızı toplam commit sayınız içerisinde göstermek istiyorsanız `?count_private=true` parametresini gönderebilirsiniz.


> Örnek: `&count_private=true`

```md
[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&count_private=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&count_private=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### İkonları Göstermek

Eğer ikonları göstermek istiyorsanız, `show_icons=true` parametresini göndermeniz gerekmektedir. Örnek olarak:

```md
[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Temalar

Dahili olarak gelen temalarla, herhangi bir [manuel özelleştirme](#özelleştirmeler) yapmadan kartın görünümünü özelleştirebilirsiniz.

`?theme=THEME_NAME` parametresini kullanabilirsiniz:

```md
[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![mustafacagri's github stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)


#### Tüm Dahili Temalar :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/ishandutta2007/image/upload/v1595174536/grs-themes_l4ynja.png" alt="Beautiful Github Homepage Temaları" width="600px"/>

Önizleme yapmak için şuralara göz atabilirsiniz: [tüm dahili temalar](./themes/README.md) veya [tema ayar dosyası](./themes/index.js) & **ayrıca siz de yeni bir tema oluşturarak katkı sağlayabilirsiniz** elbette isterseniz :D

### Özelleştirmeler


`Stats Card` ya da `Repo Card` görüntünüzü istediğiniz gibi şu parametreler ile değiştirebilirsiniz:

#### Yaygın Seçenekler:

- `title_color` - Kart başlığı rengi _(hex color / hex rengi)_
- `text_color` - İçerik rengi _(hex color / hex rengi)_
- `icon_color` - Mümkünse ikon rengi _(hex color / hex rengi)_
- `bg_color` - Kartın arkaplan rengi _(hex color / hex rengi)_ **ya da** gradient şeklinde _açı,başlangıç,bitiş_
- `hide_border` - Kartın çerçevelerini gizler _(boolean)_
- `theme` - Temanın rengi [tüm temalar](./themes/README.md)
- `cache_seconds` - Manuel olarak cache'i belirleyebilirsiniz _(en az: 14400, en fazla: 86400)_
- `locale` - Karttaki dili seçebilirsiniz _(örneğin; tr, cn, de, es, vb.)_

##### bg_color'da Gradient

bg_color içerisinde birden fazla rengi gradient olarak göstermek için virgülle ayırarak kullanabilirsiniz. Gradient kullanımı için örnek format:

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Cache Hakkında: Repo kartında fork ve yıldız sayısı 1.000'den küçükse varsayılan cache süresi 4 saat yani 14400 saniyedir. 1.000'den büyükse 2 saat yani 7200 saniyedir. Ayrıca, önbelleğin minimum 2 ve maksimum 24 saate sabitlendiğini unutmayın.

#### İstatistik Karları Exclusive Özellikler:

- `hide` - Spesifik özellikleri istatistiklerden gizleyebilirsiniz.  _(Virgül ile ayırılmış değerlerle)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ Sıralamayı gizler ve kartın genişliğini otomatik olarak tekrar düzenler
- `show_icons` - _(boolean)_
- `include_all_commits` - _(boolean)_ Sadece bu yılın değil tüm zamanlarda yaptığınız commit sayısını gösterir
- `count_private` - _(boolean)_ Özel depolarda yaptığınız commitleri gösterir
- `line_height` - _(number)_ Satır arası yüksekliği belirler
- `custom_title` - Kart için istediğiniz bir başlığı belirler
- `disable_animations` - _(boolean)_ Kart içerisindeki tüm animasyonları kapatır

#### Repo Kartları Exclusive Özellikler:

- `show_owner` - _(boolean)_ Reponun sahibinin ismini gösterir

#### Dil Kartları Exclusive Özellikler:

- `hide` - Belirli bir dili listede gizler _(Virgül ile ayırılmış değerlerle)_
- `hide_title` - _(boolean)_
- `layout` - Beş uygun tasarım / düzen arasında geçiş yapın `normal` & `compact` & `donut` & `donut-vertical` & `pie`
- `card_width` - Kartın genişliğini manuel olarak belirler _(number)_
- `langs_count` - 1-10 arasında istediğiniz kadar dil gösterebilirsiniz. Varsayılan: 5 _(number)_
- `exclude_repo` - Belirli repoları listeden çıkartır _(Virgül ile ayırılmış değerlerle)_
- `custom_title` - Kart için istediğiniz bir başlığı belirler

> :warning: **Önemli:**
> Dİl isimleri [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)'te belirtildiği üzere uri-escaped olarak belirtilmelidir.
> (ör: `c++` yerine `c%2B%2B`, `jupyter notebook` yerine `jupyter%20notebook`, vb.)
> [urlencoder.org](https://www.urlencoder.org/) adresini kullanarak otomatik olarak değerleri bu şekle çevirebilirsiniz.

#### WakaTime Kart Exclusive Özellikler:

- `hide_title` - _(boolean)_
- `line_height` - Satır aralığı yüksekliği _(number)_
- `hide_progress` - Progresbarı ve yüzdeyi gizler _(boolean)_
- `custom_title` - Kart için istediğiniz bir başlığı belirler
- `layout` - Uygun olan iki tasarım / layout arasında değişiklik yapar `default` & `compact`

---

# GitHub Ekstra Pinler

GitHub ekstra pinler profilinize 6'dan fazla repoyu / depoyu profilinizde pinleyebilirsiniz.

Hey! Artık 6 pin ile kısıtlı kalmayacaksınız!

### Kullanım

Alttaki kodu kopyalayıp readme dosyanıza urlleri değiştirerek yapıştırın.

Endpoint: `api/pin?username=mustafacagri&repo=beautiful-github-homepage`

```md
[![ReadMe Kartı](https://beautiful-github-homepage.vercel.app/api/pin/?username=mustafacagri&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

### Demo

```md
[![ReadMe Kartı](https://beautiful-github-homepage.vercel.app/api/pin/?username=mustafacagri&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![ReadMe Kartı](https://beautiful-github-homepage.vercel.app/api/pin/?username=mustafacagri&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)


[show_owner](#özelleştirmeler) ile reponun sahibini gösterebilirsiniz.

```md
[![ReadMe Kartı](https://beautiful-github-homepage.vercel.app/api/pin/?username=mustafacagri&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![ReadMe Kartı](https://beautiful-github-homepage.vercel.app/api/pin/?username=mustafacagri&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# En Çok Kullanılan Diller

En çok kullanılan diller kartı kullanıcının en çok kullandığı dilleri gösterir.

### Kullanım

Alttaki kodu kopyalayıp readme dosyanıza urlleri değiştirerek yapıştırın.

Endpoint: `api/top-langs?username=mustafacagri`

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Belirli Repoları Çıkartın

`?exclude_repo=repo1,repo2` parametresini kullanarak istediğiniz repoları çıkartabilirsiniz.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&exclude_repo=beautiful-github-homepage,ishandutta2007.github.io)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&exclude_repo=beautiful-github-homepage,ishandutta2007.github.io)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Belirli Dilleri Çıkartın

`?hide=language1,language2` parametresini kullanarak istediğiniz dilleri çıkartabilirsiniz.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Daha Fazla Dil Gösterin

`&langs_count=` parametresini kullanarak kartınızda gösterilen dil sayısını azaltabilir ya da artırabilirsiniz. Varsayılan değeri 5, kullanılabilir sayı aralığı ise 1-10'dur.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&langs_count=8)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&langs_count=8)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Kompakt Dil Kartı Düzeni

`&layout=compact` parametresiyle kart tasarımınızı değiştirebilirsiniz.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Kompakt Düzen / Layout

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=mustafacagri&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

# WakaTime Haftalık İstatistikler

`?username=` değerini [WakaTime](https://wakatime.com)'daki kullanıcı adınızla değiştirin.

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)


```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Kompakt Düzen

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### Tüm Demolar

- Varsayılan

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Belirli istatistikler gizli

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)

- İkonlar gösteriliyor

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Tüm commitler dahil

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Temalar

[default themes](#themes) adresinden istediğiniz temayı seçin.

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=mustafacagri&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Gradient

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)

- İstatistik Kartını Düzenleyin

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Kartın dilini seçin

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&locale=es)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Repo kartı düzenleyin

```md
[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

- En çok kullanılan diller

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

- WakaTime kart

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### Hızlı İpucu (Repo Kartları Hizlayın)

Genellikle resimleri yan yana düzenleyemezsiniz. Bunu yapmak için şu yaklaşımı kullanabilirsiniz:

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/convoychat">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

## Kendi Vercel Örneğinizde Yayınlayın


#### [@codeSTACKr'ın Yayınladığı Video Eğitimine Göz Atın](https://youtu.be/n6d4KHSKqGk?t=107)

GitHub API saatte sadece 5.000 isteğe izin verdiği için `https://beautiful-github-homepage.vercel.app/api` adresindeki API'm bu limite muhtemelen takılmış olabilir. Eğer projeyi kendi Vercel sunucunuzda yayınlarsanız, böyle bir sorun yaşamayabilirsiniz. Deploy butonuna tıkla ve deploy başlasın!


NOT: [#58](https://github.com/ishandutta2007/beautiful-github-homepage/pull/58) geliştirmesi sonrasında anlamadığımız bir şekilde 5.000 istek limitine takılmıyoruz :)

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/ishandutta2007/beautiful-github-homepage)

<details>
 <summary><strong> Vercel Kurulum Rehberi  🔨 </strong></summary>

1. [vercel.com](https://vercel.com/) adresine gidin
1. `Log in`'e tıklayın
   ![](https://files.catbox.moe/tct1wg.png)
1. `Continue with GitHub`'e basarak GitHub ile giriş yapın
   ![](https://files.catbox.moe/btd78j.jpeg)
1. GitHub'a giriş yapın ve eğer çıkarsa tüm repolara izin verin.
1. Bu repoyu fork'layın
1. [Vercel dashboard](https://vercel.com/dashboard)'unuza geri dönün.
1. `Import Project`'i seçin.
   ![](https://files.catbox.moe/qckos0.png)
1. `Import Git Repository`'yi seçin.
   ![](https://files.catbox.moe/pqub9q.png)
1. Root'u seçin ve her şeyi olduğu gibi bırakın, [burada](https://github.com/settings/tokens/new) kolayca oluşturabileceğiniz kişisel bir erişim belirteci (personal access token) (PAT) içerecek olan PAT_1 adlı ortam değişkeninizi (gösterildiği gibi) ekleyin. (istediğiniz bir isim verin, çok da mühim değil açıkçası)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Deploy'u tıklayın ve hazırsınız. 
Click deploy, and you're good to go. API'ı kullanmak için alanlarınızı (domainlerinizi) görün!

</details>

## :sparkling_heart: Projeyi Destekleyin

Neredeyse yapabildiğim her şeyi açık kaynak yapıyorum ve bu projeleri kullanırken yardıma ihtiyacı olan herkese cevap vermeye çalışıyorum. Açıkçası,
bu zaman alıyor. Destekleriniz sayesinde bu hizmeti ücretsiz olarak kullanabilirsiniz.

Ayrıca, bu projeyi kullanıyor ve memnunsanız veya sadece bir şeyler yaratmaya devam etmem için beni teşvik etmek istiyorsanız, bunu yapmanın birkaç yolu var: -

- Readme'nizde beautiful-github-homepage'ı kullanırken bu projeye uygun bir link verebilirsiniz.
- Projeye yıldız verebilir ve paylaşabilirsiniz :rocket:
- [![paypal.me/ishandutta2007](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/ishandutta2007) - PayPal ile tek seferlik bağış yapabilirsiniz. Muhtemelen bir ~~kahve~~ ya da çay :tea: alacağım. 

Teşekkürler! :heart:

---

[![https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss](../powered-by-vercel.svg)](https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss)


Katkılara açığız! <3

:heart: ve JavaScript ile hazırlandı.
