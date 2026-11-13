# fp

Learning functional programming: notes, exercises, and small projects.

## Layout

| Path | What goes there |
| --- | --- |
| [`notes/`](notes/) | Concept notes, one file per topic |
| [`exercises/`](exercises/) | Worked exercises from books and courses, grouped by source |
| [`projects/`](projects/) | Small programs that put the ideas to use |
| [`RESOURCES.md`](RESOURCES.md) | Books, courses, papers, and talks worth the time |

## Roadmap

Roughly in order; tick them off as notes and exercises land.

- [ ] Pure functions and referential transparency
- [ ] Immutability and persistent data structures
- [ ] First-class and higher-order functions (`map`, `filter`, `fold`)
- [ ] Recursion and tail calls
- [ ] Closures, currying, and partial application
- [ ] Function composition and point-free style
- [ ] Algebraic data types and pattern matching
- [ ] Parametric polymorphism and type inference
- [ ] Type classes / traits / modules
- [ ] Laziness and streams
- [ ] Functor, Applicative, Monad
- [ ] Monoids, Foldable, Traversable
- [ ] Managing effects (IO, State, Reader, error handling)
- [ ] Property-based testing
- [ ] Functional architecture (functional core, imperative shell)

## Conventions

- **Notes** — `notes/NN-topic.md`, starting from [`notes/TEMPLATE.md`](notes/TEMPLATE.md).
- **Exercises** — `exercises/<source>/<chapter>/`, e.g. `exercises/sicp/ch1/`.
- **Projects** — one directory each, with its own short README.
- **Commits** — say what was learned or solved, e.g. `sicp 1.2: iterative fib`.

## Resources

The full list is in [RESOURCES.md](RESOURCES.md). If you only pick three:

1. [Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/) — the classic foundation.
2. [OCaml Programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook/) — a modern, free textbook with videos.
3. [Why Functional Programming Matters](https://www.cs.kent.ac.uk/people/staff/dat/miranda/whyfp90.pdf) — the short paper that explains the point of it all.

## License

[MIT](LICENSE)
