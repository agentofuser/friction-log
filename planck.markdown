# Planck and I

## Going through the guide

- Started out here http://planck-repl.org/guide-all.html
- Let's see where this goes
- Don't know if this is the best approach, but I want to try getting familiar
  with Clojure by using Planck instead of Bash as much as I can
- That is probably a terrible idea
- Installed with `brew install planck`
- Not clear what the difference between `planck` and `plk` is, diffed the
  binaries to make sure `plk` wasn't just a symlink
- It wasn't

It seems like `plk` is a front-end for `planck`. Running `plk -h` yields this:

```
The plk script is a runner for Planck which ultimately constructs and
invokes a command-line of the form:

planck --classpath classpath [init-opt*] [main-opt] [arg*]
```

- Key word there is "runner".
- I think `plk` integrates `planck` with the Java-based Clojure tools, whereas
  `planck` on its own doesn't require either Java or Node.
- I don't want to mix up too many new concepts for now, so I'll leave `plk` for
  later and go with my lazy `alias c=planck`.

## Hello world

- First friction log ever
- First time using Gitlab
- First time using Planck
- First time using Clojure(Script) at all
- So a lot can go wrong here
- And I take all the blame for it from the outset
- Everyone else involved is amazing and I appreciate greatly everything you do
  :)
