# NeoVintageous Insert Mode Keymaps

:sparkles: :sparkles: :sparkles: Experimental; Subject to change :sparkles: :sparkles: :sparkles:

Support for insert mode key mappings in [NeoVintageous](https://github.com/NeoVintageous/NeoVintageous).

To disable a key use `vintageous_handle_keys`.

Example

Menu → Preferences → Settings

```js
"vintageous_handle_keys":
{
    "i_<C-u>": false,
    "i_<C-d>": false,
},
```

Read [How to configure the NeoVintageous key handler](https://blog.gerardroche.com/2022/09/22/neovintageous-key-handler/).

Insert mode keys are disabled by default in NeoVintageous because they can conflict with the base normal functioning of input keys.  This is an [outstanding issue](https://github.com/NeoVintageous/NeoVintageous/issues/837).

This package is meant to be a bridge toward resolving that issue.

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
