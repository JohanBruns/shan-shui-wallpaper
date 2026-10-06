# Shan Shui Wallpaper

An ambient desktop wallpaper version of **[{Shan, Shui}\*](https://github.com/LingDong-/shan-shui-inf)** by [Lingdong Huang](https://github.com/LingDong-), made for [Lively Wallpaper](https://github.com/rocksdanister/lively).

All credit for the landscape generator goes to the original project. Its code in `index.html` is unchanged; this repository only adds a wallpaper layer on top:

- `index_wallpaper.html`: a slow, endless camera drift through the landscape (works across multiple monitors), extra mountains in long empty lake stretches, a light ink-wash colour palette and seasonal zones (cherry blossom, summer, autumn)
- `LivelyInfo.json`: project metadata so Lively can load it as a web wallpaper
- `index_wallpaper_*.html`: earlier versions, kept as backups

To use it, copy `index_wallpaper.html` and `LivelyInfo.json` into a folder in Lively's wallpaper library and set it with `Lively.exe setwp --file "<that folder>"`. The settings (speed, colours, seasons) are at the top of the `AMBIENT` script in `index_wallpaper.html`.

Licensed under the MIT License of the original project (see `LICENSE`).

---

*Original README:*

# {Shan, Shui}*
Procedurally-generated vector-format infinitely-scrolling Chinese landscape for the browser.
Generate your own on https://lingdong-.github.io/shan-shui-inf/ (or [Alternative link](https://shan-shui-inf.glitch.me)).

Some examples:
![Screenshot1](/screenshots/screen001.jpg?raw=true "")
![Screenshot2](/screenshots/screen002.jpg?raw=true "")

{Shan, Shui}\* is inspired by [traditional Chinese landscape scrolls](https://en.wikipedia.org/wiki/Shan_shui) (such as [this](https://en.wikipedia.org/wiki/Dwelling_in_the_Fuchun_Mountains) and [this](https://en.wikipedia.org/wiki/Wang_Ximeng)) and uses noises and mathematical functions to model the mountains and trees from scratch. It is written entirely in javascript and outputs Scalable Vector Graphics (SVG) format.
