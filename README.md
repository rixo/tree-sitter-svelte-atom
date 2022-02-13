# tree-sitter-svelte-atom

This is a fork of [tree-sitter-svelte](https://github.com/Himujjal/tree-sitter-svelte/) with [downgraded tree-sitter CLI](https://github.com/tree-sitter/tree-sitter/issues/966#issuecomment-813016444) to make it possible to use it in an Atom grammar package.

As the only goal of this fork is to enable Atom grammars, other improvements toward this goal might be added in the short term, however the long-term goal is to have these changes incorporated into the upstream tree-sitter-svelte package (or abandonned, if they don't prove valuable enough).

Eventually, our intention is to deprecate this fork when Atom's support of tree-sitter is upgraded, so that the upstream parser can be used instead.

# LICENSE

[MIT](./LICENSE)
