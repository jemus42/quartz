---
title: "Rust"
tags:
  - programming
---

## Learning Resources

- [The Book][The Book]
- [The Book, but interactive][book-brown]
- [Rust by Example][Rust by Example]
- [Rustlings][rustlings]
- [Faster than lime](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)'s neat post(s)
- [This Week in Rust](https://this-week-in-rust.org/)
- [Read Rust](https://readrust.net)

> [!tip] Recommended Beginner Workflow
>  
> By at least one YouTube person anyway:
> 
>1. Go through the book, cover to cover
>2. Go through the book again, but now the interactive version
>3. Rust by example + Rustlings: Complementary.

### Topic-Specific Resources
- [Are we web yet?](https://www.arewewebyet.org/)
- [Are we GUI yet?](https://www.areweguiyet.com/)
- [Are we learning yet?](https://www.arewelearningyet.com/)
	- Looks like theres [[notes/ML/ML]] stuff? https://www.arewelearningyet.com/decision-trees/
	- Some projects are... not in good shape https://github.com/maciejkula/rustlearn
		- ![[assets/Screenshot 2023-03-28 at 01.09.21.jpg]]


## Setup

Via [rustup], `curl`'ing into `sh` like madlads:

```shell {title="Piping into sh lol"}
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


## Crates I should check out I guess
- `clap`: CLI interfaces
- `serde`: Getting data in & out (see also `serde_json`)
	- `csv` either additionally useful or superfluous?
- Web stuff?
	- [`leptos`](https://github.com/leptos-rs/leptos)
	- [`yew`](https://yew.rs/)


## Tools written in Rust to take a peek in

- [[notes/tools/starship]]
- [[rig]]
- [That YouTube ISG thing](https://github.com/DvorakDwarf/Infinite-Storage-Glitch) - archived now, so I guess it was fun while it lasted


[The Book]: https://doc.rust-lang.org/book
[book-brown]: https://rust-book.cs.brown.edu
[Rust by Example]: https://doc.rust-lang.org/rust-by-example/
[rustlings]: https://github.com/rust-lang/rustlings
[rustup]: https://rustup.rs/