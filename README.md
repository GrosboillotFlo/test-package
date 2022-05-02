# test-package
A test for creating a package, using GitHub Package Registry

# Consuming package:

Create/copy a Personnal Access Token (PAT) from GitHub and paste in `~/.npmrc`:

```shell
//npm.pkg.github.com/:_authToken=<your_PAT>
```

At the root of your project (where you will consume the package):

```.npm
// .npmrc
@<owner_userName>:registry=https://npm.pkg.github.com
```

```shell
yarn add @grosboillotflo/test-package
```
