## Electron & React template

using Electron-forge, Typescript and Eslint

### Development

```bash
cd <project-folder>

# install dependencies
yarn

# run the app
yarn start

# lint the app
yarn lint
```

### Production

```bash
cd <project-folder>

# make distributables for the app
# (with Forge config and passed parameters)
yarn make

# package the app into a platform specific format
# put the result in a folder
yarn package

# make the app & publish it to the publish targets (defined in forge config)
yarn publish
```
