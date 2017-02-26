![Vitae - Logo][logo]

## Table of Contents

- [Installation](#installation)
- [Quick start](#quick-start)
- [Features](#features)
  - [Google Analytics](#google-analytics)
- [About](#about)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

********************

![Vitar Screen][screenshot]

********************

<p align="center"><b><a href="https://demo.nurlan.co/hugo-vitae/">Vitae Live Demo</a></b></p>

## Installation

#### With `git`

From the root of your Hugo site, clone the theme into `themes/hugo-vitae` by running :
```
git clone https://github.com/nurlansu/hugo-vitae.git themes/hugo-vitae
```

#### Manual

1. [Download][zip-archive] zip archive.
2. Unarchive it.
3. Move `hugo-vitae` folder in `themes` folder of your site

For more information read the official [setup guide][hugo-guide] of Hugo.

## Quick start

After installation, take a look in the `exampleSite` folder at. This directory contains an example config file and the content for the demo. It serves as an example setup for your documentation. Edit the site attributes in `config.toml and edit the various entries in `layouts/partials/.

```
  exampleSite
  ├── config.toml
  ├── data
  │     ├── education.yml
  │     ├── employment.yml
  │     ├── hobbies.yml
  │     ├── initiatives.yml
  │     └── skills.yml
  └── static
        └── img
             └── profile.png
```

Copy at least the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

Hugo includes a development server, so you can view your changes as you go -
very handy. Spin it up with the following command:

``` sh
hugo serve
```

Now you can go to [localhost:1313][local] and the Vitae
theme should be visible.

## Features

### Google Analytics

To add Google Analytics, simply sign up to [Google Analytics][g-analytics] to obtain your Google Tracking ID, and add this tracking ID to the `googleAnalytics` parameter in `config.toml`.

## About

This is a port of the Jekyll theme [Vitae][vitae-jekyll] by [Fábio Madeira][vitae-author]. It supports most of the features of the original theme.

## Contributing

Pull requests, bug fixes, and new features are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -a -m 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request on GitHub

## Changelog

> Version 1.0

- Initial release

## License

<p align="center">
  <a href="./LICENSE.md"><img src="https://i.nurlan.co/logo.svg" width="100%" height="128"></a>
  <a href="./LICENSE.md"><strong>MIT</strong></a>
</p>



[logo]: https://i.nurlan.co/vitae.png
[screenshot]: https://i.nurlan.co/vitae-screen.png
[hugo]: https://gohugo.io/
[gh-pages]: https://pages.github.com/
[zip-archive]: https://github.com/nurlansu/hugo-vitae/archive/master.zip
[hugo-guide]: https://gohugo.io/overview/installing/
[local]: http://localhost:1313/
[g-analytics]: https://www.google.com/analytics/
[vitae-jekyll]: https://github.com/biomadeira/vitae/
[vitae-author]: https://github.com/biomadeira/
