# Schlagzeile
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ffront-matter%2Fschlagzeile.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ffront-matter%2Fschlagzeile?ref=badge_shield)


Schlagzeile is a [Ghost](https://github.com/TryGhost/Ghost) theme forked from the official Ghost theme [Headline](https://github.com/TryGhost/Headline). See \[Changelog(<https://github.com/front-matter/schlagzeile/blob/master/CHANGELOG.md>) for changes to the headline theme. While it can be used for any purpose, the theme takes a thoughtful approach to displaying large amounts of content across various areas of coverage. Schlagzeile adapts to your content by showcasing your most written about topics or by giving you the control to decide which topics are front and center.

# Instructions

1.  [Download this theme](https://github.com/front-matter/schlagzeile/archive/main.zip)
2.  Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/schlagzeile.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Contribution

This repo is synced automatically with [Front-Matter/schlagzeile](https://github.com/front-matter/schlagzeile) repo.

## Copyright & License

Copyright (c) 2022 Front Matter - Released under the [MIT license](LICENSE).


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ffront-matter%2Fschlagzeile.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ffront-matter%2Fschlagzeile?ref=badge_large)