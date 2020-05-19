# Reference The Selected Node

In the Chrome dev tools, if you've selected (highlighted) a node in the DOM,
you can reference that node from the console with `$0`. This is handy if you
are debugging or exploring certain parts of a page and need to run commands
against that node. For instance, if you were to select the `<html>` node in
the DOM, you could then programmatically check the `lang` attribute from the
console like so:

```
> $0.lang
// "en-US"
```


/**
 * This tip is based on the following project:
 *
 * - https://github.com/jbranchaud/til
 *
 * Released under MIT license - © jbranchaud
 */