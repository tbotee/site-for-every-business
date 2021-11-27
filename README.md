# Site For Every Business

[![Netlify Status](https://api.netlify.com/api/v1/badges/b654c94e-08a6-4b79-b443-7837581b1d8d/deploy-status)](https://app.netlify.com/sites/gatsby-starter-netlify-cms-ci/deploys)

**Note:** This starter uses [Gatsby v4](https://www.gatsbyjs.com/gatsby-4/).

This repo contains a website that is built with [Gatsby](https://www.gatsbyjs.org/), and [Netlify CMS](https://www.netlifycms.org): **[Demo Link](https://gatsby-netlify-cms.netlify.com/)**.

It follows the [JAMstack architecture](https://jamstack.org) by using Git as a single source of truth, and [Netlify](https://www.netlify.com) for continuous deployment, and CDN distribution.


## Prerequisites

- Minimal Node.js version 14.15.0
- [Gatsby CLI](https://www.gatsbyjs.com/docs/reference/gatsby-cli/)
- [Netlify CLI](https://github.com/netlify/cli)

```
$ npm install --save-dev netlify-cli
$ npm install -g gatsby-cli
$ npm install --global yarn
```

## Getting Started (Recommended)

### Access Locally

Pulldown a local copy of the Github repository Netlify created for you, with the name you specified in the previous step

```
$ git clone https://github.com/[GITHUB_USERNAME]/[REPO_NAME].git
$ cd [REPO_NAME]
$ yarn
$ netlify dev # or ntl dev
```

This uses [Netlify Dev](https://www.netlify.com/products/dev/?utm_source=blog&utm_medium=netlifycms&utm_campaign=devex) CLI feature to serve any functions you have in the `netlify/functions` folder.

To test the CMS locally, you'll need to run a production build of the site:

```
$ npm run build
$ netlify dev # or ntl dev
```

