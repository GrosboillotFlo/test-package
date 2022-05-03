# test-package
A test for creating a package, using GitHub Package Registry

# Consuming this package:

### At the root of your project (same level as your `package.json`):

```.npmrc
// .npmrc

registry=https://npm.pkg.github.com/grosboillotflo
```

### If you are installing packages from multiple registries:
```.npmrc
// .npmrc

@grosboillotflo:registry=https://npm.pkg.github.com
@<anotherUsername>:registry=https://npm.pkg.github.com
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
