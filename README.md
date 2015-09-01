# Oceanic Next JetBrains Theme

Companion for [Oceanic Next Color Scheme](https://github.com/voronianski/oceanic-next-color-scheme).

Because [IntelliJ IDEA does not allow custom themes](https://github.com/jkaving/intellij-colors-solarized/issues/83#issuecomment-63050236), we need to patch existing theme, i.e. Darcula.

1. Find idea.jar or webstorm.jar etc.
2. Open it in 7-zip.
3. Navigate to com/intellij/ide/ui/laf/darcula/darcula.properties and edit it.
4. Change contents with darcula.properties from this repo, save and close editor.
5. 7-zip will ask for modyfing archive, agree.
6. Start IDEA, webstorm etc.

You can also use this for limited functionality:

- https://github.com/dmalch/ColorIDE
- https://github.com/dmalch/ColorTree

# Screenshot

![](/screenshot.png)