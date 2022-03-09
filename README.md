# QCrypt 2021 website

[![Netlify Status](https://api.netlify.com/api/v1/badges/aee8e5e5-1bfe-4e20-9383-ba9abff022ee/deploy-status)](https://app.netlify.com/sites/qcrypt2021/deploys)

Live site at https://2021.qcrypt.net

Using the Hugo template from https://github.com/GDGToulouse/devfest-theme-hugo
adapted from the fork by the cloudnative-amsterdam people: https://github.com/cloudnative-amsterdam/public-website

theme submodule at https://github.com/QCrypt/devfest-theme-hugo-2021

## Building this conference site from scratch

1. Install [Hugo](https://gohugo.io)
2. Clone this repo:

```bash
git clone git@github.com:QCrypt/website-2021.git
```

3. Update the theme submodule

```bash
cd public-website/themes/devfest-theme-hugo
git submodule init
git submodule update
```

4. It's done. Just start Hugo server to see it live!

```bash
cd ../..
hugo server
```

5. When you are happy with the result, commit the changes to the master branch. The site is then automatically deployed to https://qcrypt2021.netlify.com/ and accessible under https://2021.qcrypt.net .

## Customizing the theme
The theme is located at https://github.com/QCrypt/devfest-theme-hugo-2021

First, install [yarn](https://yarnpkg.com/lang/en/docs/install/).

Then, use
```
cd themes/devfest-theme-hugo
yarn
```
to install the dependencies.

As you might have the right version of npm, you might have to install the node version manager [nvm](https://github.com/nvm-sh/nvm). Then, use
```
nvm install 10.0
```

In the same directory, run `npm start` to watch Sass changes.

When you are happy with the result run `npm run build` to build the minified version. Then commit the theme submodule.

### Installing on a new ARM Mac
node-sass is not yet ported to ARM processors, but there is a work-around described here:
https://github.com/sass/node-sass/issues/3033#issuecomment-763180778
