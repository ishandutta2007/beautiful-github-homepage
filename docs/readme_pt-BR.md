<p align="center">
 <img width="100px" src="https://res.cloudinary.com/ishandutta2007/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="Beautiful Github Homepage" />
 <h2 align="center">Beautiful Github Homepage</h2>
 <p align="center">Adicione suas estatísticas no GitHub geradas dinamicamente em seus readmes!</p>
</p>
  <p align="center">
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/actions">
      <img alt="Testes aprovados" src="https://github.com/ishandutta2007/beautiful-github-homepage/workflows/Test/badge.svg" />
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
    <a href="#demonstração">Ver demonstração</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Reportar erros</a>
    ·
    <a href="https://github.com/ishandutta2007/beautiful-github-homepage/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Solicitar recursos</a>
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
<p align="center">Gostou do projeto? Por favor considere <a href="https://www.paypal.me/ishandutta2007">fazer uma doação</a> para ajudar a melhorá-lo!

# Características <!-- omit in toc -->

- [Cartão de estatísticas do GitHub](#cartão-de-estatísticas-do-github)
    - [Ocultando estatísticas específicas](#ocultando-estatísticas-específicas)
    - [Adicionando contagem de contribuições privadas à contagem total de commits](#adicionando-contagem-de-contribuições-privadas-à-contagem-total-de-commits)
    - [Exibindo ícones](#exibindo-ícones)
    - [Temas](#temas)
    - [Personalização](#personalização)
- [Pins extras do GitHub](#pins-extras-do-github)
    - [Utilização](#utilização)
    - [Demonstração](#demonstração)
- [Cartão de principais linguagens de programação](#cartão-de-principais-linguagens-de-programação)
    - [Utilização](#utilização-1)
    - [Ocultar linguagens individualmente](#ocultar-linguagens-individualmente)
    - [Layout de cartão de linguagens compacto](#layout-de-cartão-de-linguagens-compacto)
    - [Demonstração](#demonstração-1)
- [Estatística semanal WakaTime](#estatística-semanal-wakatime)
    - [Demonstração](#demonstração-2)
    - [Todas as demonstrações](#todas-as-demonstrações)
    - [Dica (Alinhandos os cartões de repositório)](#dica-alinhandos-os-cartões-de-repositório)
  - [Implante em sua própria instância do Vercel](#implante-em-sua-própria-instância-do-vercel)
  - [:sparkling\_heart: Apoie o projeto](#sparkling_heart-apoie-o-projeto)

# Cartão de estatísticas do GitHub

Copie e cole isso no seu conteúdo de remarcação e é isso. Simples!

Mude o valor de `?username=` para o seu nome de usuário no GitHub.

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

_Nota: As classificações são baseadas nas estatísticas do usuário, veja [src/calculateRank.js](../src/calculateRank.js)_

### Ocultando estatísticas específicas

Para ocultar estatísticas individualmente, você pode passar um parâmetro de consulta `?hide=` com valores separados por vírgula.

> Opções: `&hide=stars,commits,prs,issues,contribs`

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,prs)
```

### Adicionando contagem de contribuições privadas à contagem total de commits

Adicione a contagem de todas as suas contribuições privadas à contagem total de confirmações usando o parâmetro de consulta `?count_private=true`.

_Nota: Se você estiver implantando este projeto, as contribuições privadas serão contadas por padrão; caso contrário, você precisará compartilhar suas contagens de contribuições privadas._

> Opções: `&count_private=true`

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&count_private=true)
```

### Exibindo ícones

Para habilitar ícones, basta utilizar o parâmetro `show_icons=true` na sua requisição, da seguinte forma:

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true)
```

### Temas

Com temas predefinidos, pode personalizar a aparência dos cartões sem precisar fazer nenhuma [configuração manual](#personalização).

Utilize o parâmetro `?theme=THEME_NAME`, da seguinte forma:

```md
![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)
```

#### Todos os temas predefinidos :

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/ishandutta2007/image/upload/v1595174536/grs-themes_l4ynja.png" alt="Beautiful Github Homepage Themes" width="600px"/>

Visualize [todos o temas disponíveis](../themes/README.md) ou o [arquivo de configuração de tema](../themes/index.js), além de **também poder contribuir com novos temas**, se desejar :D

### Personalização

Personalize a aparência do seu `Stats Card` ou `Repo Card` da maneira que desejar com os parâmetros de URL.

#### Opções comuns

- `title_color` - Cor do título do cartão _(hex color)_
- `text_color` - Cor de texto do conteúdo _(hex color)_
- `icon_color` - Cor dos ícones (se disponível) _(hex color)_
- `bg_color` - Cor de fundo do cartão _(hex color)_
- `hide_border` - Esconde a borda do cartão _(boleano)_
- `theme` - Nome do tema, escolha em [todos os temas disponíveis](../themes/README.md)
- `cache_seconds` - Defina o cabeçalho do cache manualmente _(min: 14400, max: 86400)_
- `locale` - defina o idioma no cartão _(por exemplo. cn, de, es, etc.)_

> Nota sobre o cache: Cartões de repositório tem um cache padrão de 30 minutos (1800 segundos), se o número a contagem de forks e contagem de estrelas é menor que 1 mil o padrão é 2 horas (7200 segundos). Note também que o cache é limitado a um mínimo de 30 minutos e um máximo de 24 horas.

#### Opções exclusivas do cartão de estatísticas:

- `hide` - Oculta itens específicos das estatísticas _(Valores separados por vírgulas)_
- `hide_title` - Ocultar o título _(boolean)_
- `hide_rank` - Ocultar a classificação _(boolean)_
- `show_icons` - Mostrar ícones _(boolean)_
- `include_all_commits` - Contabiliza todos os commits ao invés de apenas os atual ano _(boolean)_
- `count_private` - Contabiliza commits privados _(boolean)_
- `line_height` - Define a altura do espaçamento entre o texto _(number)_

#### Opções exclusivas do cartão de repositórios:

- `show_owner` - Exibir o nome da pessoa a quem o repositório pertence _(boolean)_

#### Opções exclusivas do cartão de linguagens:

- `hide` - Oculta linguagens específicas _(Valores separados por vírgulas)_
- `hide_title` - Oculta o título _(boolean)_
- `layout` - Alternar entre os cinco layouts disponíveis `normal` & `compact` & `donut` & `donut-vertical` & `pie`
- `card_width` - Define a largura do cartão manualmente _(number)_

> :warning: **Importante:**
> Nomes de linguagens devem ser uma sequência escapada de URI, como específicado em [Codificação por cento](https://pt.wikipedia.org/wiki/Codificação_por_cento)
> (Ou seja: `c++` deve se tornar `c%2B%2B`, `jupyter notebook` deve se tornar `jupyter%20notebook`, etc.)

---

# Pins extras do GitHub

Os Pins extras do GitHub permitem fixar mais de 6 repositórios no seu perfil usando um perfil README.me do GitHub.

Uhu! Você não está mais limitado a 6 repositórios fixados.

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/pin?username=ishandutta2007&repo=beautiful-github-homepage`

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demonstração
```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage)](https://github.com/ishandutta2007/beautiful-github-homepage)

Utilize a variável [show_owner](#personalização) para incluir o nome de usuário do proprietária do repositório

```md
[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Readme Card](https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage&show_owner=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

# Cartão de principais linguagens de programação

Exibe uma métrica de linguagens de programação mais usadas pelo usuário do GitHub.

_Nota: As principais linguagens de programação não fazem declarações sobre habilidades pessoais ou similares, é apenas uma figura-chave com base nas estatísticas do GitHub do usuário indicando a frequência com que cada uma foi utilizada._

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/top-langs?username=ishandutta2007`

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Ocultar linguagens individualmente

Utilize o parâmetro `?hide=language1,language2` para ocultar linguagens específicas.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&hide=javascript,html)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Layout de cartão de linguagens compacto

Utilize a opção `&layout=compact` para mudar o layout do cartão.

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demonstração

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Layout compacto

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007&layout=compact)](https://github.com/ishandutta2007/beautiful-github-homepage)

# Estatística semanal WakaTime

Altere o valor de `?username=` para o seu username do WakaTime.

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)


### Demonstração

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs)](https://github.com/ishandutta2007/beautiful-github-homepage)

```md
[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's WakaTime stats](https://beautiful-github-homepage.vercel.app/api/wakatime?username=ffflabs&hide_progress=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

---



### Todas as demonstrações

- Padronizado

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Ocultando estatísticas específicas

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=contribs,issues)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Mostrando ícones

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&hide=issues&show_icons=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Incluir todos os commits

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&include_all_commits=true)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Temas

Escolha entre um dos [temas predefinidos](#temas)

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api?username=ishandutta2007&show_icons=true&theme=radical)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Personalizando o cartão de estatísticas

```md
[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Ishan's GitHub stats](https://beautiful-github-homepage.vercel.app/api/?username=ishandutta2007&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)


- Customizando o cartão de repositório

```md
[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Customized Card](https://beautiful-github-homepage.vercel.app/api/pin?username=ishandutta2007&repo=beautiful-github-homepage&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)](https://github.com/ishandutta2007/beautiful-github-homepage)

- Principais linguagens

```md
[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)
```

[![Top Langs](https://beautiful-github-homepage.vercel.app/api/top-langs/?username=ishandutta2007)](https://github.com/ishandutta2007/beautiful-github-homepage)

---

### Dica (Alinhandos os cartões de repositório)

Por padrão, você não poderá organizar as imagens lado a lado. Para fazer isso, você pode usar a seguinte abordagem:

```html
<a href="https://github.com/ishandutta2007/beautiful-github-homepage">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=beautiful-github-homepage" />
</a>
<a href="https://github.com/ishandutta2007/convoychat">
  <img align="center" src="https://beautiful-github-homepage.vercel.app/api/pin/?username=ishandutta2007&repo=convoychat" />
</a>
```

## Implante em sua própria instância do Vercel

#### [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Como a API do GitHub permite apenas 5 mil solicitações por hora, é possível que minha `https://beautiful-github-homepage.vercel.app/api` atinja a cota limite. Se hospedar em seu próprio servidor Vercel, não precisará se preocupar com nada. Clique no botão de implantação para começar!

Nota: Desde [#58](https://github.com/ishandutta2007/beautiful-github-homepage/pull/58) há possibilidade de lidar com mais de 5 mil chamadas por hora, sem interrupções :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/ishandutta2007/beautiful-github-homepage)

<details>
 <summary>Guia de configuração do Vercel</summary>

1. Acesse [vercel.com](https://vercel.com/)
1. Clique em `Login`
   ![](https://files.catbox.moe/tct1wg.png)
1. Acesse com o GitHub clicando em `Continue with GitHub`
   ![](https://files.catbox.moe/btd78j.jpeg)
1. Entre no GitHub e permita acesso a todos os repositórios, se solicitado
1. Faça Fork neste repositório
1. Volte ao seu [painel principal do Vercel](https://vercel.com/dashboard)
1. Selecione `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. Selecione `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. Selecione a raiz e mantenha tudo como está, basta adicionar sua variável de ambiente chamada PAT_1 (que será exibida), que conterá um token de acesso pessoal (PAT), que você pode criar facilmente [aqui](https://github.com/settings/tokens/new) (deixe tudo como está, apenas dê um nome, que pode ser o que você quiser)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Clique em `deploy` e já estará tudo pronto. Veja seus domínios para usar a API!

</details>

## :sparkling_heart: Apoie o projeto

Disponibilizo como código aberto quase tudo o que posso e tento responder a todos que precisam de ajuda para utilizar esses projetos. Claro,
isso demanda tempo. Utilize este serviço gratuitamente.

No entanto, se você utilizar este projeto e estiver satisfeito com ele, ou apenas quiser me encorajar a continuar criando coisas, existem algumas formas fazê-lo:

- Dando os devidos créditos ao usar beautiful-github-homepage no seu README.me, adicionando uma referência ao projeto :D
- Dando uma estrela (Starring) e compartilhando o projeto 🚀
- [![paypal.me/ishandutta2007](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/ishandutta2007) - Você pode fazer doações únicas via PayPal. Provavelmente vou comprar um ~~café~~ chá. :tea:

Obrigado! :heart:

---

[![https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss](../powered-by-vercel.svg)](https://vercel.com?utm_source=beautiful_github_homepage_team&utm_campaign=oss)

Contribuições são bem-vindas! <3

Feito com :heart: e JavaScript.
