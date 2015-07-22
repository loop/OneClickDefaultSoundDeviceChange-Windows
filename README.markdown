# OneClickDefaultSoundDeviceChange-Windows

This program helps to change the default sound device with one click instead of going to Speaker (right click) -> Volume control options -> Playback and selecting the default device.

## Installation/Modifying

1. Copy this repository to a suitable location such as C:\AudioControlSource
2. Open your Windows Playback devices (Right click on your speaker icon on the taskbar and select __Volume control options__).
3. Take note of the names of the Playback devices names exactly as they appear.
4. Open __.bat__ file located in the root folder and rename the device name to what ever yours is named.
5. Inside __Audio Control__ folder make sure the shortcuts are linked to the __.bat__ file or create your own.
6. Create a new toolbar and select the source as the __Audio Control__ folder.

## Notes

* The “1” in the NIRCMD command line argument indicates that the device is set as “Default Device”.
* A “2” in the command indicates that the device will be set as a “Default Communications Device”.

[NirCmd](http://www.nirsoft.net/utils/nircmd.html) is a command tool without the need of a GUI.

## License

The MIT License (MIT)

Copyright (c) 2015 Yogesh Nagarur

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
