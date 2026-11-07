# Out of Memory

**[Play it in the browser](https://smokanci.github.io/Smokanci-OutOfMemory-web/)**

A short, endless on-rails shooter: a hoodie-wearing AI CEO glides down a city street at night on a self-balancing board, firing suction-cup arrows at DRAM sticks flying between apartment windows to feed an AI bubble that never stops deflating. You always lose eventually; the score is your peak valuation.

Built in Unity on URP, with low-poly models made in-house in Blender.

## About this repository

This repository holds only the WebGL build, served by GitHub Pages from the root of `main`. The game's source lives in a separate private repository.

The build is uncompressed on purpose: GitHub Pages cannot send the `Content-Encoding` header a Gzip or Brotli Unity build needs. `.nojekyll` stops Pages from running Jekyll over the build files.

## Browser support

It needs a browser with WebGL 2, which every current desktop browser has.
