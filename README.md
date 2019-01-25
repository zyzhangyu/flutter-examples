![Image](img/github_banner.png)

### Show some :heart: and star the repo to support the project

[![GitHub stars](https://img.shields.io/github/stars/nisrulz/flutter-examples.svg?style=social&label=Star)](https://github.com/nisrulz/flutter-examples) [![GitHub forks](https://img.shields.io/github/forks/nisrulz/flutter-examples.svg?style=social&label=Fork)](https://github.com/nisrulz/flutter-examples/fork) [![GitHub watchers](https://img.shields.io/github/watchers/nisrulz/flutter-examples.svg?style=social&label=Watch)](https://github.com/nisrulz/flutter-examples) [![GitHub followers](https://img.shields.io/github/followers/nisrulz.svg?style=social&label=Follow)](https://github.com/nisrulz/flutter-examples)  
[![Twitter Follow](https://img.shields.io/twitter/follow/nisrulz.svg?style=social)](https://twitter.com/nisrulz)

Main repository containing all the example apps demonstrating features/functionality/integrations in [Flutter](https://flutter.io/) application development

### Featured In

- [Official Flutter Samples](https://github.com/flutter/samples/blob/master/INDEX.md)  点这个链接调到官方的一个集合demo库，然后里面第一个又回到这个项目，暂时还是不要点了！
- [Flutter Weekly #11](https://mailchi.mp/5db146a7468b/flutter-weekly-11)

Lookup Links: [[Setup Flutter](https://flutter.io/setup/)] [[Widgets Catalog](https://flutter.io/widgets/)] [[Dart Lang](https://flutter.io/bootstrap-into-dart/)]

<img src="stateful_widget/demo_img.gif" height="300em" /> <img src="using_bottom_nav_bar/demo_img.gif" height="300em" /> <img src="dropdown_button/demo_img.gif" height="300em" /> <img src="using_stepper/demo_img.gif" height="300em" /> <img src="using_tabs/demo_img.gif" height="300em" />

## Example apps

1.  [Simple Material App](/simple_material_app) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/simple_material_app) 这是一个简单的hello world标签的flutter app，不需要学习！

***
2.  [Using Theme](/using_theme) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_theme)

这个是教你使用theme设置主题的一个app，在app程序的一开始设置themedata就好，后面如果有些局部想覆盖或者使用另外的主题，只需要重写themedata就好，重写有两种方法，这个使用的时候，可以回到这个app来查看。

***
1.  [Stateless Widgets](/stateless_widgets) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/stateless_widgets)
这个教程里面作者自己创建了一个statelesswidget名字叫做MyCard简单的学习了一下，怎么创建statelesswidget，这里还有一个概念也学习到了，那就是mainaxisalignment和crossaxisalignment。这个还是有点点收获的！

***
1.  [Stateful Widget](/stateful_widget) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/stateful_widget)
这个教程很简单就是一个按钮和一个文本，点击按钮，文本改变，没什么特别需要注意的！
stateful的创建方式和stateless 不太一样，但是也没有什么需要记忆的！
***
1.  [Using EditText](/using_edittext) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_edittext)
这也是一个简单的教程，但是我确犯了知名错误，不小心把main打成了mian，编译器的提示尽然是这个样子...

E/flutter ( 7944): [ERROR:flutter/shell/common/engine.cc(172)] Could not prepare to run the isolate.
E/flutter ( 7944): [ERROR:flutter/shell/common/engine.cc(119)] Engine not prepare and launch isolate.
E/flutter ( 7944): [ERROR:flutter/shell/platform/android/android_shell_holder.cc(167)] Could not launch engine in configuration.
I/Choreographer( 7944): Skipped 31 frames!  The application may be doing too much work on its main thread.

***
1.  [Load local image](/load_local_image) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/load_local_image)
加载本地图片，难度指数0颗星！
***
1.  [Load local json](/load_local_json) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/load_local_json)
加载本地的json数据，这里面使用了两个东西一个是FutureBuilder，另一个是ListView 然后通过给count和item的方式来画列表。
***
1.  [Using HTTP GET](/using_http_get) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_http_get)

这里面用到了Future 我看这个写的future还挺好的 https://www.jianshu.com/p/c0e30769ea7e  前面会用知道有这么个东西就行，不用理解的特别深刻！
***
1.  [Using Alert Dialog](/using_alert_dialog) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_alert_dialog)
这里面只有一个showalert的操作，也没有什么需要注意的！
***
1.  [Using Stepper](/using_stepper) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_stepper)
这是是一个分步器，例子太简单了，过
***
1.  [Using Tabs](/using_tabs) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_tabs)
实现了一个顶部的tabbar
***
1.  [Using Bottom Navigation Bar](/using_bottom_nav_bar) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_bottom_nav_bar)

底部导航栏----欸，和iOS不太一样！
***
1.  [Using Custom Fonts](/using_custom_fonts) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_custom_fonts)
自定义字体，作者在另一个文件写的实现，在main文件中直接调用了！
**** 
1.  [Using Gradient](/using_gradient) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_gradient)
一个渐变着色器

***
1.  [Navigation Drawer](/navigation_drawer) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/navigation_drawer)
1.  [Enable Splash Screen](/enabling_splash_screen) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/enabling_splash_screen)
1.  [Using Listview](/using_listview) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_listview)
1.  [Using SnackBar](/using_snackbar) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/using_snackbar)
1.  [Grid Layout](/grid_layout) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/grid_layout)
1.  [DropDown Button](/dropdown_button) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/dropdown_button)
1.  [Image from Network](/image_from_network) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/image_from_network)
1.  [Infinite List](/infinite_list) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/infinite_list)
1.  [Google Signin](/google_signin) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/google_signin)
1.  [Persist Key Value](/persist_key_value) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/persist_key_value)

### Complete apps with multiple features

1.  [Tip Calculator](/tip_calculator) [![download](img/ic_download.png)](https://kinolien.github.com/gitzip/?download=https://github.com/nisrulz/flutter-examples/tree/master/tip_calculator)

# Pull Requests

I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request. Here are some basic rules to follow to ensure timely addition of your request:

1.  Match coding style (braces, spacing, etc.) This is best achieved using `Reformat Code` feature of Android Studio `CMD`+`Option`+`L` on Mac and `CTRL` + `ALT` + `L` on Linux + Windows .
2.  If its a feature, bugfix, or anything please only change code to what you specify.
3.  Please keep PR titles easy to read and descriptive of changes, this will make them easier to merge :)
4.  Pull requests _must_ be made against `develop` branch. Any other branch (unless specified by the maintainers) will get rejected.
5.  Check for existing [issues](https://github.com/nisrulz/flutter-examples/issues) first, before filing an issue.
6.  Make sure you follow the set standard as all other projects in this repo do
7.  Have fun!

> P.S. : I saw if you use Adblocker then Gitzip downloads an empty `zip` file, so disable Adblocker to get the correct `zip` file.

### Created & Maintained By

[Nishant Srivastava](https://github.com/nisrulz) ([@nisrulz](https://www.twitter.com/nisrulz))

> If you found these examples helpful or you learned something from their source code and want to thank me, consider buying me a cup of :coffee:
>
> - [PayPal](https://www.paypal.me/nisrulz/5usd)
> - Bitcoin Address: 13PjuJcfVW2Ad81fawqwLtku4bZLv1AxCL

# License

    Copyright 2017 Nishant Srivastava

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
