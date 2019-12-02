# Localization Pack for Hex Editor Neo

This repository hosts a community-based development page of free localization pack for [Hex Editor Neo](//www.hhdsoftware.com/hex-editor-neo) product from HHD Software Ltd.

Please browse our [[Wiki]] for detailed instructions on using this repository and localization utility.

## Localization Utility System Requirements

* Operating system: Windows XP or later (both 32 and 64 bit supported).
* .NET 4.0 Client Profile

## Finished Language Packs

Complete language packs are available directly in Hex Editor Neo. Go to the **Tools » Settings » Languages** tab to see the list of published language packs and to download them.

Currently, the following language packs are complete for latest version of Hex Editor Neo:

* Danish
* German
* French
* Spanish
* Italian
* Simplified Chinese
* Russian
* Ukrainian

And the following language packs are complete for Hex Editor Neo 5.x:

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
