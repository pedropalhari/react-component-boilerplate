# React Component boilerplate

This is a boilerplate for a React component library. Without all the clutter.

The component is built on two folders, `dist-dev` and `dist`.

- `dist-dev` is for development and it's used as a symlink here. `dist-dev` is also added to the `.gitignore`.
- `dist` is for distribution, you can run `yarn build:prod` to generate it and it goes to the github. It's used on installation.

_`microbundler` is currently throwing some warnings on React v17, the bundle is correct nonetheless._

## To install the component:

- `yarn add <GIT_REPO_URL>`

## To update the component:

- `yarn add --check-files <GIT_REPO_URL>`

## To develop a component:

- `npx degit https://github.com/pedropalhari/react-component-boilerplate.git COMPONENT_NAME`

- `cd COMPONENT_NAME`
- Rename it in `package.json`
- Run `yarn`
- Run `yarn start`

On another tab:
- Go to `example`
- Run `yarn`
- Run `yarn start` and start developing your component.

## To publish

- Increase the version in `package.json`.
- `yarn build:release`
  - It will generate a `dist` folder with your code.
