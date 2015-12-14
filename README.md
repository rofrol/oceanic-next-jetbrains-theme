# Oceanic Next JetBrains Theme

Companion for [Oceanic Next Color Scheme](https://github.com/minwe/oceanic-next-jetbrains).

Because [IntelliJ IDEA does not allow custom themes](https://github.com/jkaving/intellij-colors-solarized/issues/83#issuecomment-63050236), we need to patch existing theme, i.e. Darcula.

0. When installing Webstorm, etc. answer no when asking for admin rights or install in the place when you have write privileges.
1. Find idea.jar or webstorm.jar etc.
2. Add JAVA_PATH/bin to your PATH.
3. Extract file and check changes: `jar xf /c/installed/WebStorm*/lib/webstorm.jar com/intellij/ide/ui/laf/darcula/darcula.properties`
4. Upload file `jar uf /c/installed/WebStorm*/lib/webstorm.jar com/intellij/ide/ui/laf/darcula/darcula.properties`

You can also use this for limited functionality:

- https://github.com/dmalch/ColorIDE
- https://github.com/dmalch/ColorTree

# Screenshot

![](/screenshot.png)
