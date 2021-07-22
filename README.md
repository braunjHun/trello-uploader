# Trello XLS Uploader

A small sample Power-Up for Trello .... 

## Setup Prerequisites

- npm install -g yarn (install yarn if not installed yet)
- yarn init (create package.json)
- yarn add -D parcel-bundler (install parcel if not installed yet)
- edit package.jason, 
    add: ```"scripts": {"build": "parcel build src/html/*.html"},```
- yarn build
- register this github project on netlify.com -> xls-uploader-power-up.netlify.app
- register the local power-up on: https://trello.com/power-ups/admin 

### NodeJS

We use [NodeJS](https://nodejs.org) to build our Power-Up. Currently, this
project expects that you are running version 12.x

We recommend you use a tool called [nvm](https://github.com/nvm-sh/nvm) to help
you manage your versions of node. If you have it installed, you can simply run
`nvm i` in this directory to install the right version of node.

### Yarn

We use [Yarn](https://yarnpkg.com) to install and manage our dependencies. Once
you've got Yarn installed, in this directory, you can run `yarn install` to
setup your dependencies locally.

## Resources

Trello has a whole [Developers Site](https://developers.trello.com/) with
various guides and documentation.

You can jump right to
[Power-Ups Documentation](https://developers.trello.com/reference#power-ups-intro)
