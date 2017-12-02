# Robohash SVG
SVG+JS Identicons based on [Robohash](https://robohash.org). The original library is designed to run on a server while this version is designed to run in browsers. The library is only ~27kB compressed and heaviliy optimized for performance. 


This is an open source contribution by [Nimiq - the browser-based blockchain](https://nimiq.com)

## Usage
 1. Include the script: `<script src="dist/robohash.min.js"></script>`
 2. Render: `Robohash.render('any text here', document.getElementById('someElement'))`

## Background Infos
For more information on our design decisions read our [design blog post](https://medium.com/nimiq-network/devblog-2-identicons-be50dca91d55).

## Hexagon-shaped Identicons
Since hexagons are part of our brand identity we've created another version of this library generating [hexagon-shaped robohashs](https://github.com/nimiq/x-identicon).
