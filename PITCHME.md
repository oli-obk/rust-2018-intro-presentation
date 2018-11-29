---
# Rust 2018 Edition

* What is it?
* Why is this happening?
* When does the fun start?
* How is that even possible?

---
### What is it?

---
### What is it **not**?

* A breaking change
* An ecosystem split (aka not the Python 2 vs 3 desaster)

---
### Ok, back to "what is it?"

* Stability without stagnation
* Language cleanups
* Convenience features
* An *opt-in* breaking change

---
### Wait! You said "no breaking changes"

You opt-in to breaking changes by adding

```toml
edition = '2018'
```

to your `Cargo.toml`

---
### So... now I need to update my code?

Yes, no, maybe. In that order.

* Yes your code needs changing
* No you don't need to do it
    * Running `cargo fix` will do it automatically
* Maybe you run into edge cases

---
### Do I need to upgrade all my crates now?

No. You can

* use 2018 edition crates from 2015 edition crates.
* use 2015 edition crates from 2018 edition crates.

---
### What is this sorcery!?

![sorcery.svg](sorcery.svg)

