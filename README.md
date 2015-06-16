XHXcodePlug
===========

收集xcode常用的插件和最新的插件，仅供参考，请不要吐槽。

收集适合我自己的插件哦！如果你发现有更好的，希望您高抬贵手，pull request给我，我合并进去哦！

####1、[SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander)是对用户自定义或者系统定义的枚举类变量做了处理，扩展switch自动补全所有case。                               
* 使用心得：当你写了一些比较多类型枚举类型的时，那就会要重复输入，好烦，就copy，但是用了这个之后，很快的就补全了，直接写实现代码


####2、[FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)是代码补全的插件，提供对用户自定义方法或者系统api方法都可以预先提示。比如你想要UIImageView，你只需要输入uimv，就会出现提示
* 使用心得：当你输入的方法名关键字会涉及到所有系统或者用户定义方法关键字的时候，你就会有点烦，所以这个看人吧！如果想偷懒，但是还是需要技巧的，比如你想要UIImageView，如果你输入UIge，会很快查到，所以这个看人吧！


####3、[Reveal-Plugin-for-XCode](https://github.com/shjborage/Reveal-Plugin-for-XCode)是Reveal App的一个辅助插件，省去开发者的配置时间，从而达到最大的效果。
* 使用心得：当对一个需求比较特殊的时候，比如富文本显示复杂的数据，这时候可能需要对每行、每列、字体进行细节的调整，可以利用Reveal进行三维空间的查看，这只是对开发哦！如果你想破解别人的app，看别人app的某个功能时，通过它还是可以给予多少帮助的哈！看封装、看继承的基类是什么，具体[点击这里](http://c.blog.sina.com.cn/profile.php?blogid=cb8a22ea89000gtw)                          

####4、[XcodeBoost](https://github.com/fortinmike/XcodeBoost)对未预先定义的函数进行copy，注意了copy的代码里面没有函数的实现，直接复制函数名，而且会把函数原本的注释一起copy，所以我们不需要手工一个一个函数的copy到Interface的api里面了。
* 使用心得：这个插件对于我这个比较懒的程序员来说，还是有用的，比如在开发中，进度很赶，所以没有那么多时间来规划和设计，所以直接对每个功能的函数直接实现了，对于这样是不规范的，所以需要把公开的api放在.h添加相应的注释、把私有的方法放在.m的Interface里面，再添加注释，哇！看起来好很多了，说到添加注释，下面会介绍另外一个插件


####5、[VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode)很多时候，为了快速开发，很多的技术文档都是能省则省，这个时候注释就变得异常重要。但是每次都要手动输入规范化的注释，着实也麻烦，但有了VVDocumenter，规范化的注释，主需要输入三个斜线“///”，就OK啦！
* 使用心得：这个没有什么异议了，之所以输入三行斜杠，是避免了默认的注释功能，所以两者配合一起用，也不错，有时候不需要规范的注释，有时候对API就需要规范的注释，所以就得需要VVDocumenter-xcode来帮忙啦！



####6、[KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode)为项目中使用的UIImage的imageNamed提供文件名自动补全功能。使用[UIImage imageNamed:@"xxx"]时，该插件会扫描整个workspace中的图片文件。
* 使用心得：这个有个技巧，不知道是不是用了[KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode)这个插件的原因，我描述一下流程吧！当输入[UIImage imageNamed:在这里会弹出窗口，进行选择图片，但是这里如果记得图片的名字，可输入一些关键词，就马上可以快速的选择相应的图片]


####7、对于现阶段，扁平化的设计、扁平化的app越来越多，这时候对颜色的感知需要敏感，对于程序员而言，可能对颜色没那么敏感，我只是说普通，不是一棒子打死所有人。这时候需要另外一个插件，[ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode)代码里的那些冷冰冰的颜色数值，到底时什么颜色？如果你经常遇到这个问题，每每不得不运行下模拟器去看看，那么这个插件绝对不容错过。更彪悍的是你甚至可以点击显示的颜色面板，直接通过系统的ColorPicker来自动生成对应颜色代码，再也不用做各种颜色代码转换了！
* 使用心得：当我看到一个UI高保真图的时候，想知道那个颜色的RGB，问UI，我去，他不烦我也烦了，所以直接打开Mac自带的工具，数码测色计，吸取颜色的RGB，然后配合ColorSense插件，就可以直接对UI设置颜色了，扁平化又高保的UI出来啦！哈哈


####8、现在的竞争越来越大了，在大公司内部都存在竞争，更何况在不同的公司对吧？那我就介绍一个插件，把自己最核心的代码打包成类似iOS SDK一样的framework，而不是打包成.a文件带上一大堆头文件，恶心死了，我个人觉得，所以这个插件诞生了。[iOS-Universal-Framework](https://github.com/kstenerud/iOS-Universal-Framework)可以打包静态库、动态库、带有资源文件的静态库，非常方便。
* 使用心得：有很多人，吐槽或者挖苦我说：你这不是开源，就是坑，然后我再想，如果我反过来问你要一个功能的源码，你愿意给吗？然后我说抽离出来，你会去做吗？所以希望这些吐槽我的人，能把你不能公开的源码，封装起来，然后给予大家使用，帮助大家，而不是一味的对我吐槽。呵呵！不过有些更搞笑的，吐槽完之后，然后又问我，你这个怎么打包而成的，然后我在想，你吐槽我是什么意思啊？然后你自己又要这么干？嘿嘿！

####9、[Auto-Importer-for-Xcode](https://github.com/lucholaf/Auto-Importer-for-Xcode)是一款自动包含所需头文件的插件，省去烦人的import，这样一来你写代码都顺畅。
* 使用心得：这样会导致一个小小的问题，你变懒了，你可能遗忘你写的类名、遗忘你所熟悉的东西，不过好处远远大于坏处啦！

####10、[synx](https://github.com/venmo/synx)Xcode文件夹整理利器。
* 使用心得：对于一个比较随意的人而言，因为你不是处女座，哈哈！你会直接在工程内新建文件目录，但是新添加的文件却不在相应的目录下，这是查找文件会出现一个困扰，那么synx就可以给予很大的帮助，直接根据工程文件（xml格式文件），进行整理项目的实际文件目录，实在太方便了，不过还是自己养成习惯为好。

####11、[frameit](https://github.com/KrauseFx/frameit)是对App截图起着快速作用的脚本。个人开发者比较适合使用，这样一来省去一些无意义的工作。
* 暂时没有使用

####12、Xcode view配色方案 [HexColorPicker](http://wafflesoftware.net/hexpicker/download/1.6.1/)
有时通过xib或者storyboard直接对一个view设置颜色，此时只知道颜色的16进制值，就非常有用了。
有人说用代码也可以实现， 是的。 如果view多了那不是需要声明N多个IBOutLet
* 安装插件的方法: 解压到至~/Library/ColorPickers/ 文件夹不存在请手动创建
![image](http://img.my.csdn.net/uploads/201209/20/1348077380_7140.png)


####13、我们国人开发的Xcode插件，必须顶起，而且真的很实用，[ZLGotoSandboxPlugin](https://github.com/MakeZL/ZLGotoSandboxPlugin)你能快速在Simulator文件夹中找到对应编译过的App。
* 使用心得，感觉比较实在，比如我想看数据库文件，录制的视频文件，那就可以快速的响应，而不需要，咦！你等下，我找找看。

####终极插件，嘿嘿！[Alcatraz](https://github.com/supermarin/Alcatraz)是一个开源的Xcode 4包管理器，可以让你更便捷地发现、安装以及管理插件、模板和配色方案。只需要简单地点击或者勾选，不需要手工复制和粘贴。
* 使用心得：当你想起一个插件的时候，可能会想知道他有什么功能，或者先预览一下，这时候它就可以帮你了，每个插件的描述右下角有两个按钮，可以出现你喜欢的功能，哈哈！

