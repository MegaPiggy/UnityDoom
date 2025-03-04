# Unity Doom

Unity Doom is a port of [Managed Doom](https://github.com/sinshu/managed-doom) to Unity.

To place an interactive playable Doom screen in your Unity game, add the UnityDoom.UnityDoomPlayer component to an object and check `play`. For more in-depth usage, read the source code.

The plugin will read DOOM WADs and the included sound font file from the specified static file directory (if blank, defaults to your StreamingAssets folder). If the files are not present in this folder, Doom will fail to run.

## License

Unity Doom and Managed Doom is distributed under the [GPLv2 license](licenses/LICENSE_ManagedDoom.txt).  
Managed Doom uses the following libraries:

* [Silk.NET](https://github.com/dotnet/Silk.NET) by the the Silk.NET team ([MIT License](licenses/LICENSE_SilkNET.txt))
* [TrippyGL](https://github.com/SilkCommunity/TrippyGL) by Thomas Mizrahi ([MIT License](licenses/LICENSE_TrippyGL.txt))
* [TimGM6mb](https://musescore.org/en/handbook/soundfonts-and-sfz-files#gm_soundfonts) by Tim Brechbill ([GPLv2 license](licenses/LICENSE_TimGM6mb.txt))
* [DrippyAL](https://github.com/sinshu/DrippyAL) ([MIT License](licenses/LICENSE_DrippyAL.txt))
* [MeltySynth](https://github.com/sinshu/meltysynth/) ([MIT license](licenses/LICENSE_MeltySynth.txt))

Silk.NET uses the following native libraries:

* [GLFW](https://www.glfw.org/) ([zlib/libpng license](licenses/LICENSE_GLFW.txt))
* [OpenAL Soft](https://openal-soft.org/) ([LGPL license](licenses/LICENSE_OpenALSoft.txt))