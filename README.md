# Keyboards
This repo hosts my keyboard configuration files.

## deeng
deeng is a keyboard optimized for German speaking programmers. It is based on QUERTY and
changes some keys to better suit programmers.
Keyboards have a language they are registerd as, which allows the OS to derive services like spell checking.
To support the os, deeng has two versions: Deeng and deEng. 
**Deeng** is registered as a German keyboard.
**deEng** is registered as an American Englisch keyboard.

How it works:
- **based on querty-international**: Enter key shape stays the same. The English layout is much more comfortable to programming/terminal use cases.
- We remap **caps-lock to escape**, escape stays the same. Allows for comfortable navigation in vim.
- We remap the **key next to left-shift to AltGr**. Now we define all the umlauts `öäüÖÄÜ`, the sharp s `ß`, the EUR sign `€` as well as the section sign `§` on the expected positions when AltGr (and shift) is pressed.

### deeng on Windows
Install Deeng and deEng. Now go into Settings > Language > Options on Language Englisch / German. Select deEng and Deeng respectively. Now change the windows registry entries:
- CAPS_LOCK to ESCAPE
- |, \, ~, ` to RIGHT_ALT (AltGr)
The easiest (and safest) way to manipulate the according registry keys is by using [sharpkeys](https://github.com/randyrants/sharpkeys).
