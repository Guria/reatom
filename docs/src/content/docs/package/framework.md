---
title: framework
description: Reatom for framework
---

This is a meta package which aggregates general Reatom packages for better handling async logic and models coupling. This package helps to reduce imports boilerplate and simplify dependencies management.

Docs around this package and it combination usage you could find in the [tutorial](/tutorial).

Included packages:

- [@reatom/async](/package/async)
- [@reatom/core](/core)
- [@reatom/effects](/package/effects)
- [@reatom/hooks](/package/hooks)
- [@reatom/lens](/package/lens)
- [@reatom/logger](/package/logger)
- [@reatom/primitives](/package/primitives)
- [@reatom/utils](/package/utils)

All size is around [6.5kb](https://bundlejs.com/?q=%40reatom%2Fasync%2C%40reatom%2Fcore%2C%40reatom%2Feffects%2C%40reatom%2Fhooks%2C%40reatom%2Flens%2C%40reatom%2Fprimitives%2C%40reatom%2Futils&config=%7B%22esbuild%22%3A%7B%22external%22%3A%5B%22%40reatom%2Flogger%22%5D%7D%7D) (the logger package is not included in prod build normally).

> Also, we have a [package for testing](/package/testing)!

<!-- TODO -->
<!-- All exported variables: -->
