# Text for Ghost

![Ghost version](https://img.shields.io/badge/ghost-v0.8.0-blue.svg?style=flat-square)
![Ghost version](https://img.shields.io/badge/ghost-v1.0.0-blue.svg?style=flat-square)
[![GitHub forks](https://img.shields.io/github/forks/imgarylai/text.svg?style=flat-square)](https://github.com/imgarylai/text/network)
[![GitHub stars](https://img.shields.io/github/stars/imgarylai/text.svg?style=flat-square)](https://github.com/imgarylai/text/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/imgarylai/text.svg?style=flat-square)](https://github.com/imgarylai/text/issues)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/imgarylai/text/master/LICENSE.md)

## Introduction

This theme is for [Ghost](https://ghost.org), a blogging platform. It supports ghost version greater than 1.0.0. 

> For ghost <= v0.8.x, please use [verstion 1.3.0](https://github.com/imgarylai/text/tree/1.3.0)

I focus on things below:

- Reader first: clear readability.
- A responsive theme along with less CSS code and simple HTML construction.
- Less animation, no font or image icon.  

![preview image](blog.gary-lai.com-1366x768.png)

## Demo

Live theme is use my blog: [blog.gary-lai.com](https://blog.gary-lai.com)

## Features

- Responsive
- Error Page(ex: 404, 500)
- Authors, Tags, Pages
- Navigation
- Code highlighting via [highlightjs](https://highlightjs.org/)  
  - Line numbers support (Optional)
- Google Analytics (Optional)
- Disqus(Optional): comments and comments count, (Thanks [@Windfarer](https://github.com/Windfarer))

## Installation

Chose one option below:

- Download as [zip](https://github.com/imgarylai/text/archive/master.zip) and put the folder `text` under `ghost/content/themes/`

- Use git: clone this repository under 'ghost/content/themes'

- DigitalOcean + Ghost: [How To Change Themes and Adjust Settings in Ghost](https://www.digitalocean.com/community/tutorials/how-to-change-themes-and-adjust-settings-in-ghost)

After install the theme, please restart server then you can change theme on settings page.

## Code Injection

### Blog Header

```
<script>
// to enable Google Analytics
var ga_id = 'YOUR UA ID HERE';

// to enable Disqus
var disqus_shortname = 'YOUR DISQUS SHORT NAME HERE'
</script>
```

### Blog footer

```
// to enable line number support
<script>
hljs.initLineNumbersOnLoad();
</script>
```

## Development

You should set your ghost on your develop machine, Please follow [official instruction](https://github.com/TryGhost/Ghost#developer-install-from-git).

Then clone this repository under this directory: `ghost/content/themes/`

Fire up local server and change your theme to `text`.

## License

Open sourced under the [MIT license](LICENSE.md).
