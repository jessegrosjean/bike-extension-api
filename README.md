# Bike Extension API

This directory contains Bike API, configuration, and code for building
extensions. Generally, you should not use this package directly.

Instead clone
[`bike-extension-template`](https://github.com/jessegrosjean/bike-extension-template)
and use the `@app`, `@dom`, and `@style` paths to import Bike API. The benfit is
that those paths will only be availible to code that will run in the right
context. For example you will get errors if you try to import `@app` in a file
that will run in the `@dom` context.