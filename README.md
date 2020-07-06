# vue-storylernawind

Starter Kit That powers Vue, Lerna, Storybook and Tailwind (LST) scaffold based on vue cli 4

## Prerequisists

NODE, NPM ,YARN, LERNA

## Developed On

Vue CLI 4 and above,
yarn as a package manager,
Node version 12 and above

## Install

```
yarn install
```

## Usage

### To Start Your componen driven Development Environment [ CDDE ] using storybook , run the following command

```
yarn storybook:serve
```

### To add a new Package

```
lerna create <package name>
```

### To publish Packages

```
lerna publish

or

yarn publish-packages
```

#### To change the Lerna Mode [ by default its set to `independent`] access `lerna.json`

## NOTE

#### This consists of a sample package called '@npm_from_shihab/example-package-core`, rename the package with <your-npm-user-name> / <package_name> or you can opt to delete it and start a new package using`lerna create` cmd.
