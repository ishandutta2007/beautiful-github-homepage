<p align="center">
 <img width="100px" src="https://res.cloudinary.com/ishandutta2007/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="Beautiful Github Homepage" />
 <h2 align="center">Beautiful Github Homepage</h2>
 <p align="center">Mostra nei tuoi README file le statistiche GitHub generate dinamicamente!</p>
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
    <a href="#demo">Anteprima</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Segnala un errore</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Richiedi una nuova funzionalità</a>
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
<p align="center">Se ti piace questo progetto, considera la possibilità di <a href="https://www.paypal.me/ishandutta2007">donare</a> per aiutare a renderlo migliore!

# Caratteristiche <!-- omit in toc -->

- [GitHub Stats Card](#github-stats-card)
    - [Nascondere statistiche individuali](#nascondere-statistiche-individuali)
    - [Includere i contributi privati nel computo totale](#includere-i-contributi-privati-nel-computo-totale)
    - [Mostrare le icone](#mostrare-le-icone)
    - [Temi](#temi)
    - [Personalizzazione](#personalizzazione)
- [GitHub Extra Pins](#github-extra-pins)
    - [Utilizzo](#utilizzo)
    - [Demo](#demo)
- [Top Languages Card](#top-languages-card)
    - [Utilizzo](#utilizzo-1)
    - [Nascondi linguaggi specifici](#nascondi-linguaggi-specifici)
    - [Layout compatto](#layout-compatto)
    - [Demo](#demo-1)
    - [Galleria di esempi](#galleria-di-esempi)
    - [Consiglio veloce (Allineare le Card)](#consiglio-veloce-allineare-le-card)
  - [Deploy su Vercel](#deploy-su-vercel)
  - [:sparkling\_heart: Supporta il progetto](#sparkling_heart-supporta-il-progetto)


# GitHub Stats Card

Per creare una Card con le statistiche GitHub, copia e incolla nel tuo file markdown, tutto qua: è semplice!

Ricorda di cambiare il valore `?username=` con il tuo nome utente GitHub.

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

_Nota: I punteggi sono calcolati sulla base delle tue statistiche, dai un'occhiata a [src/calculateRank.js](../src/calculateRank.js) per ulteriori informazioni_

### Nascondere statistiche individuali

Per nascondere qualche dato, puoi aggiungere i parametri `?hide=`, separando i valori con una virgola.

> Opzioni: `&hide=stars,commits,prs,issues,contribs`

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Includere i contributi privati nel computo totale

Puoi aggiungere i tuoi contributi privati al totale dei commit, utilizzando il parametro `?count_private=true`.

_Nota: se hai deciso di fare il deploy del progetto, i contributi privati verranno inclusi in automatico._

> Opzioni: `&count_private=true`

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&count_private=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&count_private=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Mostrare le icone

Per abilitare le icone, puoi specificare `show_icons=true`, ad esempio:

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Temi

Esistono alcuni temi predefiniti coi quali è possibile personalizzare l'aspetto delle card. In alternativa, è possibile effettuare una [personalizzazione manuale](#personalizzazione).

Usa il parametro `?theme=NOME_TEMA` in questo modo:-

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)


#### Galleria dei temi:-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/ishandutta2007/image/upload/v1595174536/grs-themes_l4ynja.png" alt="Beautiful Github Homepage Themes" width="600px"/>

Puoi avere un'anteprima di [tutti i temi supportati](../themes/README.md) o controllare il [file di configurazione dei temi](../themes/index.js) e **puoi anche contribuire creando un nuovo tema** se vuoi :D

### Personalizzazione

Puoi personalizzare l'aspetto delle tue `Stats Card` o delle `Repo Card` in qualsiasi modo, semplicemente modificando i parametri dell'URL.

#### Opzioni comuni:

- `title_color` - Colore del titolo _(in esadecimale)_
- `text_color` - Colore del testo _(in esadecimale)_
- `icon_color` - Colore delle icone, se disponibili _(in esadecimale)_
- `bg_color` - Colore dello sfondo _(in esadecimale)_ **oppure** un gradiente nella forma _angolo,inizio,fine_
- `hide_border` - Nasconde il bordo della carta _(booleano)_
- `theme` - Nome del tema, dai un'occhiata a [tutti i temi disponibili](../themes/README.md)
- `cache_seconds` - Specifica manualmente il valore di cache, in secondi _(min: 14400, max: 86400)_
- `locale` - Impostare la lingua nella scheda _(per esempio. cn, de, es, eccetera.)_

##### Gradiente nello sfondo

Puoi fornire valori separati da virgola nel parametro bg_color per creare un gradiente, il cui formato è:-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Nota sulla cache: le card hanno un valore di cache di 4 ore (14400 seconds) di default se il numero di fork & il numero di stelle è inferiore a 1000; altrimenti è pari a 2 ore (7200).

#### Opzioni valide solo per le card delle statistiche:

- `hide` - Nasconde gli oggetti selezionati _(valori separati da virgola)_
- `hide_title` - Nasconde il titolo _(booleano)_
- `hide_rank` - Nasconde il punteggio _(booleano)_
- `show_icons` - Mostra le icone _(booleano)_
- `include_all_commits` - Mostra tutti i commit e non solo quelli dell'anno corrente _(booleano)_
- `count_private` - Include i contributi privati _(booleano)_
- `line_height` - Specifica il valore dell'altezza di riga _(numero)_

#### Opzioni valide solo per le Repo Card:

- `show_owner` - Mostra il nome utente del proprietario _(booleano)_

#### Opzioni valide solo per le card dei linguaggi:

- `hide` - Nasconde un linguaggio specifico _(valori separati da virgola)_
- `hide_title` - Nasconde il titolo _(booleano)_
- `layout` - Specificare il tipo di layout, `normal` (esteso), `compact` (compatto), `donut` (ciambella), `donut-vertical` (ciambella verticale) e `pie` (torta)
- `card_width` - Specifica il valore della larghezza _(numero)_

> :warning: **Importante:**
> Per i nomi dei linguaggi, assicurati di effettuare l'encoding giusto nell'uri, come specificato in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
> (ad esempio: `c++` diventa `c%2B%2B`, `jupyter notebook` diventa `jupyter%20notebook`, ecc.)

---

# GitHub Extra Pins

GitHub Extra Pins ti permette di fissare in alto più di 6 repository nel tuo profilo, sfruttando il README del profilo.

### Utilizzo

Copia e incolla il seguente codice, premurandoti di cambiare il link.

Endpoint: `api/pin?username=ishandutta2007&repo=beautiful-github-homepage`

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demo

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)

Usa la variabile [show_owner](#personalizzazione) per includere il nome utente del proprietario

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# Top Languages Card

La Top Languages Card mostra i linguaggi che utilizzi di più su GitHub.

_NOTA: questa card non indica il livello di abilità, ma piuttosto quanto codice hai scritto in un determinato linguaggio_

### Utilizzo

Copia e incolla nel tuo file README, cambiando i link.

Endpoint: `api/top-langs?username=ishandutta2007`

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Nascondi linguaggi specifici

Puoi utilizzare il parametro `?hide=linguaggio1,linguaggio2` per nascondere alcuni linguaggi.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Layout compatto

Puoi utilizzare l'opzione `&layout=compact` per cambiare l'aspetto della card.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

### Demo

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Layout Compatto

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### Galleria di esempi

- Default

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Nascondere dati specifici

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Mostrare le icone

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Includere tutti i commit

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Temi

Scegli uno dei [temi di default](#themes)

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Gradiente

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Personalizzare le Stats Card

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Personalizzare le Repo Card

```md
[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Linguaggi più usati

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### Consiglio veloce (Allineare le Card)

Per allineare le card una accanto all'altra, puoi adottare questo approccio:

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/convoychat">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

## Deploy su Vercel

#### [Guarda questo Video Tutorial, realizzato da @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Since the GitHub API only allows 5k requests per hour, it is possible that my `https://beautiful-github-homepage.vercel.app/api` could hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Click on the deploy button to get started!

NOTE: Since [#58](https://github.com/ishandutta2007/beautiful-github-homepage/pull/58) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/ishandutta2007/beautiful-github-homepage)

<details>
 <summary><b> Guide on setting up Vercel  🔨 </b></summary>

1. Go to [vercel.com](https://vercel.com/)
1. Click on `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. Sign in with GitHub by pressing `Continue with GitHub`
   ![](https://files.catbox.moe/btd78j.jpeg)
1. Sign into GitHub and allow access to all repositories, if prompted
1. Fork this repo
1. Go back to your [Vercel dashboard](https://vercel.com/dashboard)
1. Select `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. Select `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. Select root and keep everything as is, just add your environment variable named PAT_1 (as shown), which will contain a personal access token (PAT), which you can easily create [here](https://github.com/settings/tokens/new) (leave everything as is, just name it something, it can be anything you want)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Click deploy, and you're good to go. See your domains to use the API!

</details>

## :sparkling_heart: Supporta il progetto

Rendo open-source quasi tutto ciò che posso e provo a rispondere a chiunque sia in difficoltà nell'utilizzare questi progetti. Ovviamente, mi richiede del tempo.
Puoi utilizzare questo servizio gratuitamente.

Tuttavia, se usi il progetto e ti piace e vuoi sostenermi, puoi:-

- Dare il giusto riconoscimento quando usi beautiful-github-homepage nei tuoi readme, includendo un link :D
- Mettere una stella e condividere il progetto :rocket:
- [![paypal.me/ishandutta2007](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/ishandutta2007) - Fare una donazione via PayPal. Probabilmente compreròun ~~caffè~~ tè. :tea:

Grazie! :heart:

---

[![https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss](../powered-by-vercel.svg)](https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss)

I contributi sono benvenuti! <3

Realizzato col :heart: e in JavaScript.
