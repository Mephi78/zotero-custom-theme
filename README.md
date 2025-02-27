<!-- Sprungmarke TOP -->
<a id="top"></a>

# zotero-custom-theme

<!-- Status badges -->
![w] ![c] ![l] ![s] ![f]</br></br>

<!-- ToC -->
<details>
  <summary>Table of Content</summary>
  <ul style="list-style-type: none;">
    <li><a href="#about">About</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#customizing">Customizing</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#attribution-and-acknowledgment">Attribution and Acknowledgment</a></li>
  </ul>
</details>

## About
In general the appearance of Mozilla, on which Zotero is based, can be modified using the browser's *userChrome.css* feature.

Read more at ➡️ [userChrome.org][extUserChrome]

<p align="right"><a href="#top">top ^</a></p>

## Usage
> [!CAUTION]
> Use on your own risk.

> [!NOTE]
> Full destination path:  
`C:\Users\<User_name>\AppData\Roaming\Zotero\Zotero\Profiles\<user_profile>\chrome\userChrome.css`

> [!IMPORTANT] This installation guide applies to **Zotero 7** on **Windows**.

### Install
- in your Zotero instance open *Edit* → *Settings*
- in the *Advanced* tab scroll down and open the *Config Editor*
- when asked choose *Accept risk and continue*
- in the search bar insert `toolkit.legacyUserProfileCustomizations.stylesheets`
- double click the value `false` so it becomes `true`
- close the dialog and Zotero
- go to your Zotero user profile folder  
 `C:\Users\<User_name>\AppData\Roaming\Zotero\Zotero\Profiles\<user_profile>\`
- create a folder named `chrome`
- save `userChrome.css` file inside
- open Zotero
- be happy

### Uninstall
- in your Zotero instance open *Edit* → *Settings*
- in the *Advanced* tab scroll down and open the *Config Editor*
- when asked choose *Accept risk and continue*
- in the search bar insert `toolkit.legacyUserProfileCustomizations.stylesheets`
- double click the value `true` so it becomes `false`
- close the dialog and Zotero
- delete your custom `userChrome.css` file from where you saved it before
- open Zotero
- everything back to normal

<p align="right"><a href="#top">top ^</a></p>

## Customizing

<p align="right"><a href="#top">top ^</a></p>

## Contributing

<p align="right"><a href="#top">top ^</a></p>

## License
This work is distributed under the [GPLv3](LICENSE).
<p align="right"><a href="#top">top ^</a></p>

## Attribution and Acknowledgment
This work was inspired by [Rosmaninho's - Zotero Dark Theme](https://github.com/Rosmaninho/Zotero-Dark-Theme).  
Thanks to [Josmar Cristello](https://github.com/josmarcristello/Zotero-Material-Dark-Theme) for the hint about Zotero 7 stylesheets flag - made my day!
<p align="right"><a href="#top">top ^</a></p>

<!-- Badges -->
[c]: https://badgen.net/github/commits/Mephi78/zotero-custom-theme
[l]: https://badgen.net/github/last-commit/Mephi78/zotero-custom-theme
[w]: https://badgen.net/badge/work/in%20progress/yellow
[s]: https://badgen.net/github/stars/Mephi78/zotero-custom-theme
[f]: https://badgen.net/github/forks/Mephi78/zotero-custom-theme

<!-- external Links -->
[extUserChrome]: https://www.userchrome.org/what-is-userchrome-css.html