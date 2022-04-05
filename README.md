# rustwiki.org

![Build Status](https://github.com/rust-lang-cn/rustwiki.org/workflows/CI/badge.svg)
[![LICENSE-MIT](https://img.shields.io/badge/license-MIT-green)](https://raw.githubusercontent.com/rust-lang-cn/rust-by-example-cn/master/LICENSE-MIT)
[![LICENSE-APACHE](https://img.shields.io/badge/license-Apache%202-blue)](https://raw.githubusercontent.com/rust-lang-cn/rust-by-example-cn/master/LICENSE-APACHE)
![GitHub last commit](https://img.shields.io/github/last-commit/rust-lang-cn/rustwiki.org?color=gold)
![rustwiki.org](https://img.shields.io/website?up_message=rustwiki.org&url=https%3A%2F%2Frustwiki.org)

This is the source code of the [rustwiki.org](https://rustwiki.org) and [rustwiki.org.cn](https://rustwiki.org.cn) websites.

## Running and Building

First, You need to install the [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.13.0.

To run the site locally:

```bash
$ git clone https://github.com/rust-lang-cn/rustwiki.org.git
$ cd rustwiki.org
$ zola serve
```

If you want to build the site, just run `zola build`. From there, the generated HTML will be in the `public` directory.

## How to Contribute?

This is a big project with many translations involved. You can contribute by
reporting errors or suggesting improvements. Just open an issue or pull request.

## License

rustwiki.og is licensed under either of

- Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or
   <http://opensource.org/licenses/MIT>)

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in rustwiki.org by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
