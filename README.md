# Hugo Scroll ![Test](https://github.com/janraasch/hugo-scroll/workflows/CI/badge.svg?branch=master&event=push)

📜 A [Hugo](https://gohugo.io/)-theme for pretty, quick and simple single-page websites.

![Screenshot Hugo Scroll Theme](https://raw.githubusercontent.com/janraasch/hugo-scroll/master/images/tn.png)

## Demo

For a current & working demo of this theme please check out https://janraasch.github.io/hugo-scroll/ 🎯.

## Installation

If you already have a hugo site on your machine, you can simply add this theme via

```
git submodule add https://github.com/janraasch/hugo-scroll.git themes/hugo-scroll
```

Then, adjust the `config.toml` as detailed below.

If you simply want to check out the `exampleSite`, you can run

```
git clone https://github.com/janraasch/hugo-scroll.git hugo-scroll
cd hugo-scroll
hugo server --source=exampleSite --themesDir=../..
```

For more information read the official [setup guide][hugo-setup-guide] of Hugo.

## Adjust configuration / config.toml

Please check out the [config.toml](https://github.com/janraasch/hugo-scroll/blob/master/exampleSite/config.toml) included on the [exampleSite](https://github.com/janraasch/hugo-scroll/tree/master/exampleSite) of this theme.

## Content & structure

### Starting fresh

If you are starting fresh, simply copy over the contents of the `exampleSite`-directory included in this theme to your source directory. That should give you a good idea about how things work, and then you can go on from there to make the site your own.

### Adding content

You can add **a new section to the homepage** via running

```
hugo new homepage/my-new-content.md
```

To create **a page separate from the homepage**, run

```
hugo new my-new-page.md
```

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Checkout the [`custom_head.html`](https://github.com/janraasch/hugo-scroll/blob/master/exampleSite/layouts/partials/custom_head.html)-file from the `exampleSite`-directory to get started and to find more detailed instructions.

## Issues / Feedback / Contributing
Please use [GitHub issues](https://github.com/janraasch/hugo-scroll/issues) and [Pull Requests](https://github.com/janraasch/hugo-scroll/pulls).

If you do not have a GitHub-account, feel free to hit me up via e-mail (see [janraasch.com](https://www.janraasch.com)).


## Sponsor [![Pay me][insert-coins-svg]][paypal-dot-me]
Please consider supporting my work on this theme via [GitHub Sponsors][github-sponsors] or [PayPal][paypal-dot-me].

[![GitHub Stats](https://github-readme-stats.vercel.app/api/?username=janraasch)][github-sponsors]

## Special Thanks 🎁

* Go to [Yonatan Wolowelsky](https://github.com/grmmph), for the great [GhostScroll](https://github.com/grmmph/GhostScroll)-theme which formed the basis of this [Hugo](https://gohugo.io/)-theme.
* Go to [Pexels](https://www.pexels.com), for supplying those wonderful *free* stock photos on the [exampleSite](https://github.com/janraasch/hugo-scroll/tree/master/exampleSite).

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) © [Jan Raasch](https://www.janraasch.com)

[paypal-dot-me]: https://www.paypal.me/janraasch/29,00
[github-sponsors]: https://github.com/sponsors/janraasch
[insert-coins-svg]: https://img.shields.io/badge/insert-coins-11dde2.svg

[hugo-setup-guide]: https://gohugo.io/getting-started/installing
