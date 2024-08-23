# Neovim Spelling

The default Neovim Spellcheck, works fine, so sticking with it.

## Configuration

See the `init.lua` file in the parent directory. Look for the following lines.

```
vim.opt.spelllang = 'en_us'
vim.opt.spell = true
```

## Keys

For a full explanation [see the documentation](https://neovim.io/doc/user/spell.html). The following are the important default key bindings:

- `]s`: Next misspelled word
- `[s`: Previous misspelled word
- `z=`: Suggest alternative spelling
- `zg`: Add word to the dictionary
