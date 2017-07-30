# flying-leopard
Personal React boilerplate. Slightly extends create-react-app

## Installation

- Copy `package.json` to your git repo. Type `npm i`. Sit back and wait.
- Copy `.gitignore` if you don't already have one.

## Notes

- You should have a git repo initialized before npm installation. This gives `husky` a folder to inject its git hooks into.
- Single-quotes and no-semis are enforced. To disable, modify the `eslintConfig` and the `lint-staged` property inside `package.json`.
- All configuration is defined within the `package.json` file.
- This config very slightly extends `create-react-app`. Refer to their official [README](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) for more info.
