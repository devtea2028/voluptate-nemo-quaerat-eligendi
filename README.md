# shockpkg Core

The core shockpkg library.

[![npm](https://img.shields.io/npm/v/@devtea2028/voluptate-nemo-quaerat-eligendi.svg)](https://npmjs.com/package/@devtea2028/voluptate-nemo-quaerat-eligendi)
[![node](https://img.shields.io/node/v/@devtea2028/voluptate-nemo-quaerat-eligendi.svg)](https://nodejs.org)

[![size](https://packagephobia.now.sh/badge?p=@devtea2028/voluptate-nemo-quaerat-eligendi)](https://packagephobia.now.sh/result?p=@devtea2028/voluptate-nemo-quaerat-eligendi)
[![downloads](https://img.shields.io/npm/dm/@devtea2028/voluptate-nemo-quaerat-eligendi.svg)](https://npmcharts.com/compare/@devtea2028/voluptate-nemo-quaerat-eligendi?minimal=true)

[![Build Status](https://github.com/devtea2028/voluptate-nemo-quaerat-eligendi/workflows/main/badge.svg)](https://github.com/devtea2028/voluptate-nemo-quaerat-eligendi/actions?query=workflow%3Amain+branch%3Amaster)

# Overview

The core package manager library for shockpkg packages.

# Usage

## Basic Usage

```js
import {Manager} from '@devtea2028/voluptate-nemo-quaerat-eligendi';

const manager = new Manager();
const pkg = 'some-package-name-or-hash';
await manager.update();
await manager.install(pkg);
const file = await manager.file(pkg);
console.log(file);
```

# Bugs

If you find a bug or have compatibility issues, please open a ticket under issues section for this repository.

# License

Copyright (c) 2018-2024 JrMasterModelBuilder

Licensed under the Mozilla Public License, v. 2.0.

If this license does not work for you, feel free to contact me.
