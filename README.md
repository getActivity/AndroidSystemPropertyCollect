# Android 系统属性收集

* 前不久我发布了一个 [DeviceCompat](https://github.com/getActivity/DeviceCompat) 库，一经发布深受大家的喜欢，但是很快我就遇到了瓶颈，这个瓶颈不是技术导致的，而是我手头没有那么多设备，为了 DeviceCompat 能够做得更好（判断更加精准），现在需要征集大家手机的系统属性，大家有空的情况下，可以将手头的手机，设置中的包含 Os 类型和 Os 版本的截图给我，另外还需要将设备中系统属性提取到 txt 文件中，可以用这个 adb  命令：`adb shell getprop` 来获取系统属性，然后将手机截图和系统属性文件进行重命名，例如下面这样的：

```
MIUI 12.5.6 Android 11 Xiaomi 9.txt
MIUI 12.5.6 Android 11 Xiaomi 9.jpg
```

* 然后通过 [Pull request](https://github.com/getActivity/AndroidSystemPropertyCollect/pulls) 提交给当前的项目，目前[各大厂商 Os 系统](https://zh.wikipedia.org/wiki/%E5%AE%A2%E8%A3%BD%E5%8C%96Android%E9%9F%8C%E9%AB%94%E5%88%97%E8%A1%A8)属性收集情况如下，欢迎大家补充：

    * [360UI](https://baike.baidu.com/search?enc=utf8&word=360%20OS)（所有版本都极度稀缺）

        * 360UI 3.0

    * [ColorOS](https://zh.wikipedia.org/wiki/ColorOS)（14.x ~ 15.x 版本饱和，其他版本稀缺）

        * ColorOS 15.0

        * ColorOS 14.0

        * ColorOS 13.1

        * ColorOS 11.2

        * ColorOS 11.1

        * ColorOS 7.1

        * ColorOS 5.2

        * ColorOS 3.0

    * [EMUI](https://zh.wikipedia.org/wiki/EMUI)（8.x ~ 11.x 版本饱和，其他版本稀缺）

        * EMUI 11.x

            * 11.0.0

        * EMUI 10.x

            * 10.1.0

            * 10.0.1

            * 10.0.0

        * EMUI 9.x

            * 9.1.1

            * 9.1.0

            * 9.0.0

        * EMUI 8.x

            * 8.0.0

    * [EUI](https://baike.baidu.com/item/EUI/17205923#1)（极度稀缺）

        * EUI 6.0.030

        * EUI 5.9.026

    * [Flyme](https://zh.wikipedia.org/wiki/Flyme)（没有标注的版本稀缺）

        * Flyme 12.x

            * 12.1.0.0

        * Flyme 11.x

            * 11.2.1.0

        * Flyme 10.x

            * 10.5.0.1

        * Flyme 8.x

            * 8.1.8.0

            * 8.0.5.0

        * Flyme 7.x

            * 7.1.5.2

        * Flyme 6.x

            * 6.3.5.0

            * 6.2.0.2

    * [FuntouchOS](https://zh.wikipedia.org/wiki/Funtouch_OS)（数量稀少）

        * FuntouchOS 10.0

        * FuntouchOS 9.0

        * FuntouchOS 4.0

        * FuntouchOS 2.6

    * [H2OS](https://zh.wikipedia.org/wiki/%E6%B0%A2OS)（数量稀少）

        * H2OS 11.1.2.2

        * H2OS 9.0.11

    * [HarmonyOS](https://zh.wikipedia.org/wiki/%E9%B8%BF%E8%92%99_(%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F))（2.0.x ~ 4.3.x 版本饱和，其他版本稀缺）

        * HarmonyOS 4.3.0

        * HarmonyOS 4.2.0

        * HarmonyOS 4.0.0

        * HarmonyOS 3.0.0

        * HarmonyOS 2.0.0

    * [HarmonyOS NEXT（卓易通）](https://zh.wikipedia.org/wiki/HarmonyOS_NEXT)（5.1.x ~ 6.0.x 版本饱和，其他版本稀缺）

        * HarmonyOS NEXT 5.1.0

        * HarmonyOS NEXT 6.0.0

    * [HyperOS](https://zh.wikipedia.org/wiki/%E5%B0%8F%E7%B1%B3%E6%BE%8E%E6%B9%83OS)（1.x ~ 3.x 版本饱和，其他版本稀缺）

        * HyperOS 3.x

            * 3.0.16.0

        * HyperOS 2.x

            * 2.0.214.0

            * 2.0.212.0

            * 2.0.208.0

            * 2.0.205.0

            * 2.0.203.0

            * 2.0.8.0

            * 2.0.6.0

            * 2.0.1.0

        * HyperOS 1.x

            * 1.0.14.0

            * 1.0.10.0

            * 1.0.6.0

            * 1.0.3.0

    * [MagicOS/MagicUI](https://en.wikipedia.org/wiki/Honor_(brand)#History_2)（数量稀少）

        * MagicOS 9.0

        * MagicUI 7.1

        * MagicUI 7.0

        * MagicUI 6.1

        * MagicUI 3.1.1

        * MagicUI 3.0.1

    * [MifavorUI](https://baike.baidu.com/item/%E4%B8%AD%E5%85%B4%E6%89%8B%E6%9C%BA)（数量稀少）

        * MifavorUI 10.1

        * MiFavorUI 4.0

    * [MIUI](https://zh.wikipedia.org/wiki/MIUI)（10.x ~ 14.x 版本饱和，其他版本稀缺）

        * MIUI 14

            * 14.0.18

            * 14.0.10

            * 14.0.9（MIUI Global）

            * 14.0.7（MIUI Global）

            * 14.0.4

            * 14.0.1

        * MIUI 13

            * 13.0.26

            * 13.0.16

            * 13.0.12

            * 13.0.8

            * 13.0.3

        * MIUI 12

            * 12.5.6

            * 12.5.3

            * 12.0.15

        * MIUI 11

            * 11.0.5

        * MIUI 10

            * 10.3.2（MIUI by xiaomi.eu）

            * 10.9.8.22

            * 10.1.1.0

        * MIUI 9

            * 9.2.4.0

    * [MyOS](https://baike.baidu.com/search?word=MyOS&rn=10)（数量稀少）

        * MyOS 14.5.33

        * MyOS 12.0.14

    * MYUI（数量稀少）

        * MYUI 7.0

        * MYUI 6.0

        * MYUI 5.0

    * NebulaAIOS（极度稀缺）

        * NebulaAIOS 1.0.14

    * [nubiaUI](https://baike.baidu.com/search?word=nubiaUI)（极度稀缺）

        * nubiaUI 1.0

    * [OneUI](https://zh.wikipedia.org/wiki/One_UI)（5.x ~ 8.x 版本饱和，其他版本稀缺）

        * OneUI 8.0

        * OneUI 7.0

        * OneUI 6.1

        * OneUI 5.1.1

        * OneUI 5.1

        * OneUI 5.0

        * OneUI 2.5

        * OneUI 1.0

    * [OriginOS](https://zh.wikipedia.org/wiki/Origin_OS)（3.x ~ 5.x 版本饱和，其他版本稀缺）

        * OriginOS 5

            * 15.2.15.1

            * 15.1.19.20

            * 15.0.18.12

        * OriginOS 4

            * 14.2.6.5

        * OriginOS 3

            * 13.0.9.4

        * OriginOS 1

            * 9.16.42

    * [OxygenOS](https://baike.baidu.com/item/%E6%B0%A7OS/17141141)（数量稀少）

        * OxygenOS 14.0

        * OxygenOS 9.0.4

    * [realmeUI](https://baike.baidu.com/item/realme%20UI/58770376)（数量稀少）

        * realmeUI 6.0

        * realmeUI 4.0

        * realmeUI 3.0

    * [RedMagicOS](https://en.wikipedia.org/wiki/Nubia_Technology)（数量稀少）

        * RedMagicOS 10.0.25

        * RedMagicOS 10.0.24

        * RedMagicOS 10.0.12

        * RedMagicOS 6.0

    * ROGUI（极度稀缺）

        * ROGUI 33.0210.0210.235

    * [SmartisanOS](https://en.wikipedia.org/wiki/Smartisan)（数量稀少）

        * SmartisanOS 8.0.2

        * SmartisanOS 6.7.4.3

        * SmartisanOS 6.7.4.2

        * SmartisanOS 6.6.6.2

        * SmartisanOS 4.2.6

    * ZUI（数量稀少）

        * ZUI 16.1.11.187

        * ZUI 14.0.314

        * ZUI 3.5.91

    * ZUXOS（极度稀缺）

        * ZUXOS 1.1.10.138

        * ZUXOS 1.1.350

    * 其他漏掉的 Os（待补充）

* 大家可以看一下自己的手头的设备，看一下是不是属于上述欠缺的 Os 系统或者 Os 版本，如果是的话可以提交一下给我，一定要欠缺的才要，如果是上面已经有的 Os 版本或者已经饱和的 Os 版本范围就不要提交了，样本覆盖程度越高 [DeviceCompat](https://github.com/getActivity/DeviceCompat) 判断准确度会越高，判断效率也会提高，当然你如果嫌弃通过 Pull request 提交太麻烦，你也可以上传到这个项目 [issue](https://github.com/getActivity/AndroidSystemPropertyCollect/issues/new) 区也是可以的。

* 喝水不忘挖井人，希望大家在喝到水的同时，能够停下来帮忙挖一铲是最好不过的，涓涓细水汇成江河，我深知这口井仅凭我一个人是无法挖好，需要借助大家的力量才有可能。

#### 作者的其他开源项目

* 安卓技术中台：[AndroidProject](https://github.com/getActivity/AndroidProject) ![](https://img.shields.io/github/stars/getActivity/AndroidProject.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject.svg)

* 安卓技术中台 Kt 版：[AndroidProject-Kotlin](https://github.com/getActivity/AndroidProject-Kotlin) ![](https://img.shields.io/github/stars/getActivity/AndroidProject-Kotlin.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject-Kotlin.svg)

* 权限框架：[XXPermissions](https://github.com/getActivity/XXPermissions) ![](https://img.shields.io/github/stars/getActivity/XXPermissions.svg) ![](https://img.shields.io/github/forks/getActivity/XXPermissions.svg)

* 吐司框架：[Toaster](https://github.com/getActivity/Toaster) ![](https://img.shields.io/github/stars/getActivity/Toaster.svg) ![](https://img.shields.io/github/forks/getActivity/Toaster.svg)

* 网络框架：[EasyHttp](https://github.com/getActivity/EasyHttp) ![](https://img.shields.io/github/stars/getActivity/EasyHttp.svg) ![](https://img.shields.io/github/forks/getActivity/EasyHttp.svg)

* 标题栏框架：[TitleBar](https://github.com/getActivity/TitleBar) ![](https://img.shields.io/github/stars/getActivity/TitleBar.svg) ![](https://img.shields.io/github/forks/getActivity/TitleBar.svg)

* 悬浮窗框架：[EasyWindow](https://github.com/getActivity/EasyWindow) ![](https://img.shields.io/github/stars/getActivity/EasyWindow.svg) ![](https://img.shields.io/github/forks/getActivity/EasyWindow.svg)

* 设备兼容框架：[DeviceCompat](https://github.com/getActivity/DeviceCompat) ![](https://img.shields.io/github/stars/getActivity/DeviceCompat.svg) ![](https://img.shields.io/github/forks/getActivity/DeviceCompat.svg)

* ShapeView 框架：[ShapeView](https://github.com/getActivity/ShapeView) ![](https://img.shields.io/github/stars/getActivity/ShapeView.svg) ![](https://img.shields.io/github/forks/getActivity/ShapeView.svg)

* ShapeDrawable 框架：[ShapeDrawable](https://github.com/getActivity/ShapeDrawable) ![](https://img.shields.io/github/stars/getActivity/ShapeDrawable.svg) ![](https://img.shields.io/github/forks/getActivity/ShapeDrawable.svg)

* 语种切换框架：[MultiLanguages](https://github.com/getActivity/MultiLanguages) ![](https://img.shields.io/github/stars/getActivity/MultiLanguages.svg) ![](https://img.shields.io/github/forks/getActivity/MultiLanguages.svg)

* Gson 解析容错：[GsonFactory](https://github.com/getActivity/GsonFactory) ![](https://img.shields.io/github/stars/getActivity/GsonFactory.svg) ![](https://img.shields.io/github/forks/getActivity/GsonFactory.svg)

* 日志查看框架：[Logcat](https://github.com/getActivity/Logcat) ![](https://img.shields.io/github/stars/getActivity/Logcat.svg) ![](https://img.shields.io/github/forks/getActivity/Logcat.svg)

* 嵌套滚动布局框架：[NestedScrollLayout](https://github.com/getActivity/NestedScrollLayout) ![](https://img.shields.io/github/stars/getActivity/NestedScrollLayout.svg) ![](https://img.shields.io/github/forks/getActivity/NestedScrollLayout.svg)

* Android 版本适配：[AndroidVersionAdapter](https://github.com/getActivity/AndroidVersionAdapter) ![](https://img.shields.io/github/stars/getActivity/AndroidVersionAdapter.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidVersionAdapter.svg)

* Android 代码规范：[AndroidCodeStandard](https://github.com/getActivity/AndroidCodeStandard) ![](https://img.shields.io/github/stars/getActivity/AndroidCodeStandard.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidCodeStandard.svg)

* Android 资源大汇总：[AndroidIndex](https://github.com/getActivity/AndroidIndex) ![](https://img.shields.io/github/stars/getActivity/AndroidIndex.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidIndex.svg)

* Android 开源排行榜：[AndroidGithubBoss](https://github.com/getActivity/AndroidGithubBoss) ![](https://img.shields.io/github/stars/getActivity/AndroidGithubBoss.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidGithubBoss.svg)

* Studio 精品插件：[StudioPlugins](https://github.com/getActivity/StudioPlugins) ![](https://img.shields.io/github/stars/getActivity/StudioPlugins.svg) ![](https://img.shields.io/github/forks/getActivity/StudioPlugins.svg)

* 表情包大集合：[EmojiPackage](https://github.com/getActivity/EmojiPackage) ![](https://img.shields.io/github/stars/getActivity/EmojiPackage.svg) ![](https://img.shields.io/github/forks/getActivity/EmojiPackage.svg)

* AI 资源大汇总：[AiIndex](https://github.com/getActivity/AiIndex) ![](https://img.shields.io/github/stars/getActivity/AiIndex.svg) ![](https://img.shields.io/github/forks/getActivity/AiIndex.svg)

* 省市区 Json 数据：[ProvinceJson](https://github.com/getActivity/ProvinceJson) ![](https://img.shields.io/github/stars/getActivity/ProvinceJson.svg) ![](https://img.shields.io/github/forks/getActivity/ProvinceJson.svg)

* Markdown 语法文档：[MarkdownDoc](https://github.com/getActivity/MarkdownDoc) ![](https://img.shields.io/github/stars/getActivity/MarkdownDoc.svg) ![](https://img.shields.io/github/forks/getActivity/MarkdownDoc.svg)

#### 微信公众号：Android轮子哥

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/official_ccount.png)

#### Android 技术 Q 群：10047167

#### 如果您觉得我的开源库帮你节省了大量的开发时间，请扫描下方的二维码随意打赏，要是能打赏个 10.24 :monkey_face:就太:thumbsup:了。您的支持将鼓励我继续创作:octocat:（[点击查看捐赠列表](https://github.com/getActivity/Donate)）

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_ali.png) ![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_wechat.png)

## License

```text
Copyright 2025 Huang JinQun

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```