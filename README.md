# JD-GUI

JD-GUI，一个独立的图形化工具，用于从 CLASS 文件显示 Java 源代码。

![](https://raw.githubusercontent.com/java-decompiler/jd-gui/master/src/website/img/jd-gui.png)

- Java 反编译器项目主页：[http://java-decompiler.github.io](http://java-decompiler.github.io)
- JD-GUI 源代码：[https://github.com/java-decompiler/jd-gui](https://github.com/java-decompiler/jd-gui)

## 描述
JD-GUI 是一个独立的图形化工具，用于显示 ".class" 文件的 Java 源代码。您可以使用 JD-GUI 浏览重构后的源代码，以便快速访问方法和字段。

## 如何构建 JD-GUI？
```
> git clone https://github.com/java-decompiler/jd-gui.git
> cd jd-gui
> ./gradlew build 
```
生成：
- _"build/libs/jd-gui-x.y.z.jar"_
- _"build/libs/jd-gui-x.y.z-min.jar"_
- _"build/distributions/jd-gui-windows-x.y.z.zip"_
- _"build/distributions/jd-gui-osx-x.y.z.tar"_
- _"build/distributions/jd-gui-x.y.z.deb"_
- _"build/distributions/jd-gui-x.y.z.rpm"_

## 如何启动 JD-GUI？
- 双击 _"jd-gui-x.y.z.jar"_
- 在 Windows 上双击 _"jd-gui.exe"_ 应用程序
- 在 Mac OSX 上双击 _"JD-GUI"_ 应用程序
- 执行 _"java -jar jd-gui-x.y.z.jar"_ 或 _"java -classpath jd-gui-x.y.z.jar org.jd.gui.App"_

## 如何使用 JD-GUI？
- 通过菜单 "File > Open File..." 打开文件
- 通过菜单 "File > Recent Files" 打开最近的文件
- 从文件浏览器中拖放文件

## 如何扩展 JD-GUI？
```
> ./gradlew idea 
```
生成 Idea Intellij 项目
```
> ./gradlew eclipse
```
生成 Eclipse 项目
```
> java -classpath jd-gui-x.y.z.jar;myextension1.jar;myextension2.jar org.jd.gui.App
```
使用您的扩展启动 JD-GUI

## 如何卸载 JD-GUI？
- Java：删除 "jd-gui-x.y.z.jar" 和 "jd-gui.cfg"。
- Mac OSX：将 "JD-GUI" 应用程序拖放到废纸篓。
- Windows：删除 "jd-gui.exe" 和 "jd-gui.cfg"。

## 许可证
根据 [GNU GPL v3](LICENSE) 发布。

## 捐款
JD-GUI 是否帮助您解决了关键情况？您每天都在使用 JD-Eclipse 吗？为什么不考虑捐款呢？

[![paypal](https://raw.githubusercontent.com/java-decompiler/jd-gui/master/src/website/img/btn_donate_euro.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C88ZMVZ78RF22) [![paypal](https://raw.githubusercontent.com/java-decompiler/jd-gui/master/src/website/img/btn_donate_usd.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CRMXT4Y4QLQGU)
