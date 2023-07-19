# NeoVintageous Insert Mode Keymaps

:sparkles: :sparkles: :sparkles: Experimental :sparkles: :sparkles: :sparkles:

Support for insert mode key mappings in [NeoVintageous](https://github.com/NeoVintageous/NeoVintageous).

To disable a key use `vintageous_handle_keys`.

Menu → Preferences → Settings

```js
"vintageous_handle_keys":
{
    "<C-f12>": false,
    "<S-f1>": false,
    "<S-tab>": false,
    "<f1>": false,
    "i_<C-u>": false,
    "i_<C-d>": false,
},
```

## Installation

### Manual installation

Close Sublime Text, then download or clone this repository to a directory named **NeoVintageous** in the Sublime Text Packages directory for your platform:

**Linux**

`git clone https://github.com/gerardroche/NeoVintageousInsertModeKeymaps.git ~/.config/sublime-text-3/Packages/NeoVintageous`

**OSX**

`git clone https://github.com/gerardroche/NeoVintageousInsertModeKeymaps.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/NeoVintageous`

**Windows**

`git clone https://github.com/gerardroche/NeoVintageousInsertModeKeymaps.git %APPDATA%\Sublime/ Text/ 3/Packages/NeoVintageous`

## License

Released under the [GPL-3.0-or-later License](LICENSE).
