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

> [!tip] Recommended Workflow
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
	- Looks like theres [[ML]] stuff? https://www.arewelearningyet.com/decision-trees/
	- Some projects are... not in good shape https://github.com/maciejkula/rustlearn
		- ![[assets/Screenshot 2023-03-28 at 01.09.21.jpg]]


## Setup

Via [rustup], `curl`'ing into `sh` like madlads:

```shell {title="Piping into sh lol"}
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


[The Book]: https://doc.rust-lang.org/book
[book-brown]: https://rust-book.cs.brown.edu
[Rust by Example]: https://doc.rust-lang.org/rust-by-example/
[rustlings]: https://github.com/rust-lang/rustlings
[rustup]: https://rustup.rs/