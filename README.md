# asyncomplete-ale.vim

LSP completion source (via [ALE][]) for [asyncomplete.vim][].

## Installation & Usage

Install:

```
Plug 'prabirshrestha/asyncomplete.vim'
Plug 'andreypopp/asyncomplete-ale.vim'
```

Configure:

```
au User asyncomplete_setup call asyncomplete#ale#register_source({
    \ 'name': 'reason',
    \ 'linter': 'flow',
    \ })
```

[asyncomplete.vim]: https://github.com/prabirshrestha/asyncomplete.vim
[ALE]: https://github.com/w0rp/ale
