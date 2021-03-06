# cljsjs/commonmark

[](dependency)
```clojure
[cljsjs/commonmark "0.26.0-1"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.commonmark))
```

[CommonMark][commonmark] is a rationalized version of Markdown syntax. It provides a
[library][library] with functions for parsing CommonMark documents to an abstract
syntax tree (AST), manipulating the AST, and rendering the document to HTML or
to an XML representation of the AST.

[flibs]: https://clojurescript.org/reference/packaging-foreign-deps
[commonmark]: http://commonmark.org/
[library]: https://github.com/jgm/commonmark.js
