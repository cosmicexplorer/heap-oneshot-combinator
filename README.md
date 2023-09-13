heap-oneshot-combinator
=======================

A [`core::future::Future`](https://doc.rust-lang.org/stable/core/future/trait.Future.html) combinator that boxes up an argument in order to move it into an `FnOnce` closure without enforcing a `'static` lifetime. See [this post](https://circumstances.run/@hipsterelectron/111042888107396604) for more context.

# TODO
- [ ] depend on the `alloc` crate to support `no_std` environments.

# License
[Apache v2](./LICENSE).
