Outline of a potential Ramda book
=================================

- Prefatory materials

    - Inspiration and history
    - Rationale, including "Why not `lodash`/`Underscore`?"
    - Aimed toward JS programmers, not FP experts
    - How FP fits in JS
    - Community
    - Standard tech book artifacts
        - How to read (e.g. skip Ch 2, but make sure you understand Ch 3, or whatever)
        - Typesetting conventions

- Basic usage
    - Simple example (`map`?), showing
        - Parameter ordering
        - Auto-currying
        - Immutability
        - Declarative over imperative
    - Small functions on common structures
        - note: use Perlis quote
    - Composition
        - Thinking in pipelines
        - `pipe`, `compose`, `o` (?)
        - `converge`, `lift`
    - Common FP functions
        - `map`, `filter`, `find`, `reduce`, others?

- Philosophy
    - Simplicity
    - Referential transparency
    - Immutability
    - Practical, not academic
    - Library, not framework


- Working with Functions
    - Currying
        - Manual vs Ramda's magic
    - Changing signatures
        - `flip`, `partial`, `lift`, `nAry`, `apply`, `unapply`
    - Combining function
        - `compose*`, `pipe*`, `converge`, `useWith` (?)

      
- Working with logic and flow
    - Combining values
        - `and`, `or`, `not`
    - Combining predicates
        - `both`, `either`, `complement`, `allPass`, `anyPass`
    - Control flow
        - `ifElse`, `cond`, `tap` (?)


- Working with Objects
    - Using properties
        - `prop`, `path`, `props`, `omit`, `pick`
    - Altering properties (immutably)
        - `assoc`, `dissoc`
    - Combining objects
        - `merge*`
    - Comparing objects
        - `equals`, `has`, `where`
    - Creating objects
        - `clone`, `evolve`, `applySpec`, `fromPairs`
    - Restructuring objects
        - `keys`, `values`, `invert`

- Working with Lists
    - Arrays as lists
    - Building lists
        - `range`, `repeat`, `times`, `keys`/`value`, `toPairs`
    - Tweaking lists
        - `insert`, `adjust`
    - Lists to scalars
        - `reduce`, `find`, `nth`, `all`, `any`
    - Slicing and dicing lists
        - `sort*`, `take`, `drop`, `append`, `prepend`, `concat`, `intersperse`, `split*`
    - List transformation
        - `map`, `pluck`, `filter`, `aperture`, `uniq`, `zip`, `partition`, `zip`, `traverse` 


- Working with Strings and Number


- Typeclasses and Fantasy-land


- Lenses


- Transducers (?)


- Other libraries
    - Sanctuary
    - fp-ts
    - Monet
    - fluture
