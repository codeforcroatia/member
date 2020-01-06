# Code for Croatia members vCard pages

## Quick set-up

1. [Fork this repository](https://github.com/codeforcroatia/member/)
2. Use gh-pages branch, copy `example` directory, rename new directory to some short URL slug to represent your short URL, edit `index.md`, update as necessary your `avatar.jpg`, `background.jpg` and `favicon.ico`
3. Create pull request and wait for your member vCard to be approved and published!

## Dependencies

Parent upstream repo with single vCard pages is [Epidrome's Cover Card](https://github.com/epidrome/cover-card/tree/master).

This theme is based on [jekyll](https://jekyllrb.com/) and [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme). The above dependencies are natively supported by [Github Pages](https://pages.github.com/), which will build and deploy your site as soon as you make any change to your files. The theme is also based on the icons from [Font Awesome](https://fontawesome.com/). 

## Motivation

Create a cover page for your social media profiles, host it for free on Github Pages, and maintain it in minutes, not hours. [Demo](http://dev.codeforcroatia.org/member/)

This theme is ideal for people or organizations who feel like a member of Code for Croatia community and who want a simple business card for their online presence.

Please keep this README file because it contains the credits at the end and it might become handy after you have completely forgoten the set-up instructions.

## Design rationale

The design rationale of this theme is to do less than other themes: "Less is more"

The majority (99%) of the availabe jekyll themes offers a blog, but I have never been able to keep blog content (or its technology) updated over time.

Let's be honest with ourselves: How does an (abandoned) blog centered web site look to new visitors if we have not posted since two years ago?

## Add your member vCard page

[Fork this repository](https://github.com/codeforcroatia/member/), copy `example` directory and edit the files to your liking: As a first step, you may want to replace the images and edit the `index.md` with your online profiles. You can test the result almost in real-time at the `Github Pages` section in the Settings tab (gh-pages branch).

### Avatar or Logo

The avatar image should be square and at least 200 pixels. Chances are that you have a selfie somewhere in your media storage. If you are making a page for a business or product, then use a logo.

### Background image sets the mood

There is no aspect ratio requirement for the background image, but it should be big enough for contemporary (desktop, tablet, phone) computer displays and dark enough in order to work for the white foreground text and icons.

### Social profiles & contacts

Edit the `index.md` file with your social media profiles by adding the respective account name, according to the documentation and comments inside that file. You can delete or comment out the social media that you don't need.

### Domain name

These pages are hosted on Github Pages under [dev.codeforcroatia.org](http://codeforcroatia.github.io/member/) domain.

If you want your own domain name Github Pages supports free custom domain names, so it is worth buying a domain name and fill it in `Custom domain` field at the settings. If you want to use the theme with you user page (ie. username.github.io), then fork this repo, delete (or rename) your `master branch` and rename your `gh-branch` to `master`, see [#13](https://github.com/epidrome/cover-card/issues/13).

### Site Configuration

The configuration file in this repository is `_config.yml` and it defines Code for Croatia Members site global values. You do not need to edit this file when adding your vCard. You can also [inspect a modified example of the configuration file](https://github.com/epidrome/home/blob/master/_config.yml), which is currently using the previous version of the theme.

### Updates & changes

Please note that the upstream repo theme is currently in beta, so some updates at the [master branch](https://github.com/epidrome/cover-card/tree/master) might break your site. Don't panic! 

If you wish to keep your theme frozen and not receive updates, then you can [revert your remote_theme to the last known good configuration](https://github.com/benbalter/jekyll-remote-theme):

> You may also optionally specify a branch, tag, or commit to use by appending an @ and the Git ref (e.g., codeforcroatia/member@v0.3). If you don't specify a Git ref, the master branch will be used.

Please note that currently Github Pages seems to build your site only when you make a local change. This means that the theme might get updated but you will not receive the updated version unless you make a local change in your forked repository.

You can always visit this members flavour repo [releases](https://github.com/codeforcroatia/member/releases) for new features and check [issues](https://github.com/codeforcroatia/member/issues) for major bugs.

Since v04, repo owner can control the order of social media accounts, add new media accounts and choose the icon.

### Expert options

You can find and locally overide advanced options (custom domain name, extra social icons, font styles) for this theme in the documentation (readme) at the upstream parent repo [master branch](https://github.com/epidrome/cover-card/tree/master).

## Credits

This page is based on the [cover-card jekyll remote theme](https://github.com/epidrome/cover-card/tree/master).

Example background photo by Anders Jildén and avatar photo by Ayo Ogunseinde, both on [Unsplash](https://unsplash.com/)
Root page & Ops page background photo from CodeAcross 2015 was provided by [Ylodi](https://github.com/Ylodi).
