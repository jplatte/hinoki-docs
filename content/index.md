+++
template = "index.html"
+++

# Hinoki

*Yet another static site generator*

Hinoki is a static site generator, that is a small tool to compile a set of
templates, content files and assets into a website suitable for hosting on an
arbitrary web server or content delivery service.

<div class="message is-warning">
  <div class="message-header">
    <p>Work in progress</p>
  </div>
  <div class="message-body">

Hinoki is a very young project, and it's not yet ready for prime time.
I'm happy about anybody who tries it and provides feedback, but if you're looking for something to
build a production-ready website with in the next couple of months, try something else.
Maybe [Zola](https://www.getzola.org/), which Hinoki takes a lot of inspiration from.

  </div>
</div>

## Installation

For `x86_64` Linux, binaries are provided via [GitHub releases][releases].

Further binaries may be provided in the future, but if you're on a different
platform or want to build from source for other reasons, that's also possible
of course:

1. Make sure you have a working [Rust][] toolchain [installed][install-rust]
2. Run `cargo install --git https://github.com/jplatte/hinoki`, appending
   `--rev vX.Y.Z` where `X.Y.Z` are the version digits if you want to build one
   of the releases rather than the latest state of the `main` branch

[releases]: https://github.com/jplatte/hinoki/releases
[Rust]: https://www.rust-lang.org/
[install-rust]: https://www.rust-lang.org/tools/install
