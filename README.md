### Factory

- a static method (creates objects)
- a common method (creates objects with respect to current object state)
  - **prototype**
- a different class for creating objects of another class
  - **builder**
  - **config**
  - **factory "method"**
  - **abstract factory**

### Customization point

- behavioural
  - **strategy** - *single hierarchy (just a customization point)*
  - **command** - *multiple users (independent stateful object with an action)*
- structural
  - **bridge** - *multiple hierarcies (abstraction and implementation can be changed independedly)*

### Decorator/Proxy difference

- **decorator**
  - does not control wrapee's lifetime
  - does not control flow
- **proxy**
  - controls wrapee's lifetime
  - controls flow

### Decorator/Composite difference

- **decorator**
  - one wrapee
  - enhances the wrapee's result
- **composite**
  - many wrapees
  - sums-up wrapees' results

### Decorator/Chain difference

- **decorator**
  - just add additional functionality (pre/post-effects)
- **chain of responsibility**
  - controls flow (pass/interrupt)
