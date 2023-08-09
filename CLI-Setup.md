# Setting up the Spec CLI

## Requirements

* Node.js >= 16
* npm >= 8

## Steps

#### 1) Install the CLI

```bash
$ npm install -g @spec.dev/cli
```

#### 2) Verify the installation

```bash
$ spec version
```

#### 3) Login to your Spec account

```bash
$ spec login
```

**Reach out personally or on [Twitter](https://twitter.com/SpecDotDev) to request access to an account.**

#### 4) Tell the CLI what your "current" Spec project is

When your account was created, you should have also been added to a particular namespace (usually either a protocol or your username). Within that namespace, there should be a default project called "spec". Go ahead and set this as your *current* project:

```bash
$ spec use project <namespace>/spec
```