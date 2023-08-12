# NeoVintageous Insert Mode Keymaps

:sparkles: :sparkles: :sparkles: Experimental; Subject to change :sparkles: :sparkles: :sparkles:

Support for insert mode key mappings in [NeoVintageous](https://github.com/NeoVintageous/NeoVintageous).

To disable a key use `vintageous_handle_keys`.

**Example:**

1. Open the Command Palette: `Preferences: NeoVintageous Settings`.
2. Add the following JSON configuration:

   ```json
   {
       "vintageous_handle_keys":
       {
           "i_<C-u>": false,
           "i_<C-d>": false
       }
   }
   ```

Read [How to configure the NeoVintageous key handler](https://blog.gerardroche.com/2022/09/22/neovintageous-key-handler/).

Insert mode keys are disabled by default in NeoVintageous because they can conflict with the base normal functioning of input keys.  This is an [outstanding issue](https://github.com/NeoVintageous/NeoVintageous/issues/837).

This package is meant to be a bridge toward resolving that issue.

## Installation

**Method 1: Manual Installation**

1. Visit the [NeoVintageousInsertModeKeymaps GitHub repository](https://github.com/gerardroche/sublime-phpunit).
2. Click on the "Code" button and select "Download ZIP."
3. Extract the downloaded ZIP file.
4. Open Sublime Text and go to `Preferences -> Browse Packages...` to open the Packages folder.
5. Copy the "NeoVintageousInsertModeKeymaps" folder from the extracted ZIP and paste it into the Packages folder.

**Method 2: Manual Git Repository Installation**

1. Open a terminal or command prompt.
2. Navigate to the Sublime Text Packages directory:
    - On Windows: `%APPDATA%\Sublime Text\Packages`
    - On macOS: `~/Library/Application Support/Sublime Text/Packages`
    - On Linux: `~/.config/sublime-text/Packages`
3. Clone the plugin repository directly into the Packages directory using Git:
   ```
   git clone https://github.com/gerardroche/sublime-phpunit.git NeoVintageousInsertModeKeymaps
   ```

## License

Released under the [GPL-3.0-or-later License](LICENSE).
