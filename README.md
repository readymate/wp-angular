# WordPress Angular Starter

Wordpress Theme wrapper for Angular 4 Frontend

## Table of Contents

- [Pre-Requirements](#pre-requirements)
- [Usage](#usage)
- [Local Development](#local-development)
- [Support](#support)
- [Contributing](#contributing)

## Pre-Requirements
- Setup Git [More info here](https://git-scm.com/)
- Install Node [More info here](https://docs.npmjs.com/getting-started/installing-node)
- Install Angular-CLI [More info here](https://www.npmjs.com/package/@angular/cli/tutorial)

## Usage
1. Upload contents of this repository to your WordPress Theme Folder. 
2. Activate through WP-Admin
3. Customise to your needs


## Local Development
The app inside `angular-src` is generated through the `Angular-CLI`, only change is the `npm run build:prod` command inside `package.json` with the correct output path.

Run App

```sh
cd angular
ng serve
```

Build for Production (outputs to `wp-angular/dist` folder)

```sh
cd angular
npm run build:prod
```

## Support

Please [open an issue](https://github.com/readymate/wp-angular/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/readymate/wp-angular/compare/).
