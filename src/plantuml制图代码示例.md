# plantuml制图代码示例

## 配置文件
 在mdbook的配置文件book.toml中添加配置语句:
>[preprocessor.plantuml]
plantuml-cmd="plantuml.exe"[^1]

## 代码示例 [^2]

> ```plantuml
> @startmindmap
> * Debian
> ** Ubuntu
> *** Linux Mint
> *** Kubuntu
> *** Lubuntu
> *** KDE Neon
> ** LMDE
> ** SolydXK
> ** SteamOS
> ** Raspbian with a very long name
> *** <s>Raspmbc</s> => OSMC
> *** <s>Raspyfi</s> => Volumio
> @endmindma
> ```

[^1]: plantuml-cmd: Optional command override for PlantUML (defaults to "java -jar plantuml.jar" on Windows and "/usr/bin/plantuml" on Linux). When a URL is provided it is assumed you want to generate the images using a PlantUML server implementation.

[^2]:在代码最前面要添加“```”plantuml,最后加上“```”
