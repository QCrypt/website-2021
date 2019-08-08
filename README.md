# QCrypt 2020 website

[![Netlify Status](https://api.netlify.com/api/v1/badges/aee8e5e5-1bfe-4e20-9383-ba9abff022ee/deploy-status)](https://app.netlify.com/sites/qcrypt2020/deploys)

Live site at https://qcrypt2020.netlify.com/

Using the Hugo template from https://github.com/GDGToulouse/devfest-theme-hugo
adapted from the fork by the cloudnative-amsterdam people: https://github.com/cloudnative-amsterdam/public-website


## Building this conference site from scratch

1. Install [Hugo](https://gohugo.io)
2. Clone this repo:

```bash
git clone git@github.com:QCrypt/public-website.git
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

5. When you are happy with the result, commit the changes to the master branch. The site is then automatically deployed to https://qcrypt2020.netlify.com/ .

## Customizing the theme

First, install [yarn][https://yarnpkg.com/lang/en/docs/install/].

```
cd themes/devfest-theme-hugo
yarn
```
to install the dependencies.

In the same directory, run `npm start` to watch Sass changes.

When you are happy with the result run `npm run build` to build the minified version. Then commit the theme submodule.
