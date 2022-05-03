# test-package
A test for creating a package, using GitHub Package Registry

# Consuming this package:

### Authenticate to GitHub Packages

For more information, see ["Authentication to GitHub Packages"](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

### In the same directory as your `package.json`, create or edit an `.npmrc` file:

```.npmrc
@grosboillotflo:registry=https://npm.pkg.github.com
```

### If you are installing packages from multiple registries:
```.npmrc
@grosboillotflo:registry=https://npm.pkg.github.com
@<anotherOwner>:registry=https://npm.pkg.github.com
...
```

### Installing package:

```shell
npm install @grosboillotflo/test-package
```
or
```shell
yarn add @grosboillotflo/test-package
```
