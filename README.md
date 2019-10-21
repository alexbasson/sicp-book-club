# Structure and Intepretation of Computer Programs

## Resources

[The Book](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), by Harold Abelson, Gerald Sussman, and Julie Sussman.

[Video Lectures (1986)](https://www.youtube.com/playlist?list=PLE18841CABEA24090), taught by Harold Abelson, Gerald Sussman, and Julie Sussman.

[Video Lectures (2004)](https://www.youtube.com/playlist?list=PL7BcsI5ueSNFPCEisbaoQ0kXIDX9rR5FF), taught by Eric Grimson.

## Schedule & Syllabus

Here's a link to [the schedule](./wiki/Schedule), together with which sections from the book, videos, and exercises we'll be covering each session.

## Installing Scheme

MIT Scheme (using Homebrew):

```bash
$ brew install mit-scheme
```

Chez Scheme: [https://cisco.github.io/ChezScheme/#get](https://cisco.github.io/ChezScheme/#get)

More Scheme resources: [https://exercism.io/tracks/scheme/installation](https://exercism.io/tracks/scheme/installation)

## Using Scheme in IntelliJ

[Scheme plugin](https://plugins.jetbrains.com/plugin/10171-scheme/)

### Some useful keymaps:

- Start In-Process Scheme Console: `Cmd-Shift-F10`
- Execute code in REPL: `Cmd-Enter`
- To load a Scheme file: `Cmd-Shift-L`
- Run Selected Text in REPL: `Cmd-Shift-J`

## Scheme Basics

- Loading a file
```scheme
(load "path/to/file.scm")
```
