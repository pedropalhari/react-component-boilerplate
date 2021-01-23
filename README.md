# React Component boilerplate

This is a boilerplate for a React component library. Without all the clutter.

The component is built on two folders, `dist-dev` and `dist`.

- `dist-dev` is for development and it's used as a symlink here. `dist-dev` is also added to the `.gitignore`.
- `dist` is for distribution, you can run `yarn build:prod` to generate it and it goes to the github. It's used on installation.

## To install the component:

- `yarn add <GIT_REPO_URL>`

## To develop a component:

- Rename it in `package.json`
- Run `yarn`
- Run `yarn start`

- Go to `example`
- Run `yarn`
- Run `yarn start` and start developing your component.

## To publish

- `yarn build:release`
  - It will generate a `dist` folder with your code.
