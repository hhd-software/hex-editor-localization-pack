# Localization Pack for Hex Editor Neo

This repository hosts a community-based development page of free localization pack for [Hex Editor Neo](//www.hhdsoftware.com/free-hex-editor) product from HHD Software Ltd.

Please browse our [Wiki](https://github.com/hhd-software/hex-editor-localization-pack/wiki) for detailed instructions on using this repository and localization utility.

## Localization Utility System Requirements

* Operating system: Windows 7 or later (both 32 and 64 bit supported).
* .NET 4.8 Framework

## Finished Language Packs

Complete language packs are available directly in Hex Editor Neo. Go to the **Tools » Settings » Languages** tab to see the list of published language packs and to download them.

Currently, the following language packs are complete for latest version of Hex Editor Neo:

* Spanish
* German
* French
* Italian
* Portuguese
* Russian
* Ukrainian

And the following language packs are complete for Hex Editor Neo 5.x or 6.x:

* Danish
* Simplified Chinese
* Polish
* Indonesian

## Manually Building Language Packs

You can manually build non-complete language pack and use it in Hex Editor Neo. Follow this procedure:

1. Install Git client.
2. Execute a Clone command for the following repository:

   ```
   git clone https://github.com/hhd-software/hex-editor-localization-pack.git
   ```

3. Switch to your language's branch.
4. Run the supplied `langtool.exe` utility (located at the root of the repository) and open the `hex.xml` project file.
5. Execute the **File » Compile…** command and select the language you want to compile.
6. Make sure you have Hex Editor Neo installed. Compile the Language Pack.
7. Run Hex Editor Neo and select the language pack in corresponding box on the toolbar.

## Using Authoring Mode

Hex Editor Neo may be launched in so-called "authoring" mode that will allow direct editing of most strings that can be localized. As a result, a *corrections* file is produced when the editor is closed. This *corrections* file may be imported into the language pack editor.

To start Hex Editor Neo in authoring mode, use the following command line:

```PowerShell
HexFrame.exe /authoring <path-to-corrections-file>
```

Where `<path-to-corrections-file` should be replaced with a full path of the corrections file. Hex Editor Neo adds the current date and time and `.xml` file extension to the end of the path. The file is created when the editor is closed.

### String Editing

To edit a title of a window, hold `Ctrl` and `Shift` keys and click on a window title. To edit a text label, a button, a checkbox or a radio button, hold `Ctrl` and `Shift` keys and click on a control. After finishing editing, press the `Enter` key. For multi-line controls, press `Ctrl+Enter`. Press `Esc` to discard your changes.

Please note that not all strings can be localized using authoring mode.
