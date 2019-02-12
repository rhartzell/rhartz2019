# Product Name
My Azure website code
https://rhartz2019.azurewebsites.net/


[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

## Synopsis

This repo contains the files I dumped on my quick and dirty Azure hosted NODE website. It's mostly math and graphics stuff that I have been playing with, but it could turn into more things as my sandbox expands.

## Code Example

Mostly graphics from ThreeJs at this point.
```      // Global vars...
      var container, camera, scene, geometry, mesh, renderer, controls, particles, colors;

      // DOM element...
      container = document.createElement('div');
      document.body.appendChild(container);

      // Camera...
      camera = new THREE.PerspectiveCamera(45, window.innerWidth / window.innerHeight, 1, 10000);
      camera.position.set(25, 10, 100);

      // Scene...
      scene = new THREE.Scene();
      scene.add(camera);

      // Renderer...
      renderer = new THREE.WebGLRenderer({
          clearAlpha: 1
      });
```

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki