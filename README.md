# SC4AutoInstallerAndLauncher
模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 1.5.49 正式版 (2015-06-23)
====================================================================================

新增
====
1.如果启动时安装程序正在运行会弹出错误框并将焦点移到正在运行的安装程序上。

修改
====
1.在验证文件窗口的取消验证提示框的文本的文件不完整可能会导致安装失败前加上如果两字。
2.现在在验证单个文件完整性完成后会自动关闭那个文件的使用。
3.将验证文件窗口取消按钮的文本由取消改为取消(&C)。
4.将验证文件窗口的取消按钮属性设置为取消按钮。
5.如果模拟城市4安装失败则安装完成窗口的打开模拟城市4 豪华版按钮会无法点击。
6.将安装中窗口的安装任务列表框的列表组改为居中对齐。
7.将安装中窗口的安装任务列表框的模拟城市4 豪华版项移到游戏列表组里。
8.将在安装完成后闪动任务栏图标和标题栏的条件由焦点不在安装完成窗口上闪动改为显示安装完成窗口时闪动。
9.将在安装完成后闪动任务栏图标和标题栏的闪动次数由闪动4294967295次改为闪动5次

修复
====
1.修复了验证文件窗口会弹出Data\Patch\No-CD\SimCity 4.exe文件不存在错误框的bug。
2.彻底修复了即便取消验证文件完整性后验证文件线程仍然在验证文件且验证完成后会重复显示主窗口的bug。
3.修复了无法安装模拟城市4硬盘版、638补丁和640补丁的bug（感谢togaer和涅槃无生_阿淼发现此bug。）。
4.修复了如果模拟城市4安装失败且已经取消后续组件安装，在安装完成窗口4GB补丁和模拟城市4启动器仍然会显示为安装成功的bug。
5.修复了点击验证文件窗口的文件不完整提示框的忽略按钮后仍然会继续验证文件完整性并在验证完成后重复显示主窗口的bug。
6.修复了点击验证文件窗口的文件不完整提示框的忽略按钮后仍然会继续验证文件完整性并在验证完成后重复显示主窗口的bug。
7.修复了点击验证文件窗口的文件不完整提示框的忽略按钮后会直接退出文件验证的bug。
8.修复了点击验证文件窗口的文件不完整提示框的重试按钮后会继续验证下一个文件的完整性的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 1.5.31 正式版 (2015-06-20)
====================================================================================

新增
====
1.现在在安装完成后如果焦点不在安装完成窗口上会闪动任务栏图标和标题栏。

修改
====
1.将Data\4GB\4gb_patch.exe文件改名为Data\4GB.exe；将Data\Image文件夹改名为CD。
2.将Data\638.EXE、640.exe、638.rar和640.rar文件移动到Data\638和Data\640里；将Data\No-CD文件夹改名为NoCD。

修复
====
1.修复了在验证文件完整性时如果要检测的文件或Data文件夹不存在仍然会继续验证文件完整性并触发异常的bug。

模拟城市4 启动器(SC4Launcher) 1.0.16 正式版 (2015-06-20)
====================================================================================

新增
====
1.在设置窗口的颜色位深列表框内添加了黑白选项。
2.添加每次启动时检测并安装更新的功能。
3.现在在主窗口启动游戏后会自动关闭启动器。

修改
====
1.现在当设置窗口的用户目录复选框未选中时用户目录文本框的内容会自动清空。
2.现在如果设置窗口的用户目录文本框或模拟城市4安装目录文本框的路径格式不正确时弹出的提示框会显示是哪个文本框的路径格式不正确。
3.将设置窗口的选择模拟城市4安装目录后如果安装目录里没有游戏程序弹出的警告框的标题和图标由警告改为错误。

修复
====
1.修复了设置窗口的颜色位深列表框不会跟随参数的内容变化的bug。
2.修复了即使设置窗口的自定义用户目录复选框未被选中，在点确认或应用按钮时仍然会判断用户目录路径是否有效的bug。
3.修复了设置窗口的自定义用户目录的参数前面没有空格的bug。
4.修复了如果退出设置窗口后再打开设置窗口重复两次，启动参数就会变成空白的bug。
5.修复了设置窗口的改变模拟城市4安装路径的选择文件夹对话框无法关闭的bug。
6.修复了点击设置窗口的删除SimCity 4.cfg文件按钮会触发FormatException异常的bug。
7.修复了如果设置了用户目录，点击删除SimCity 4.cfg文件按钮会触发ArgumentOutOfRangeException异常的bug。
8.修复了设置窗口的用户目录文本框和模拟城市4安装目录文本框的内容更改后无法更改用户目录或模拟城市4安装目录的bug。
9.修复了如果模拟城市4安装目录和用户目录路径格式不正确只会弹出模拟城市4安装目录格式不正确提示框的bug。
10.修复了模拟城市4安装目录更改后不检查是否是模拟城市4安装目录就直接保存安装目录的bug。

模拟城市4 启动器(SC4Launcher) 1.0.0 正式版 (2015-06-12)
====================================================================================
初版。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 1.5.27 正式版 (2015-06-12)
====================================================================================

新增
====
1.在安装选项窗口的安装组件里添加了模拟城市4启动器。
2.现在在安装模拟城市4后会将GOG版模拟城市4的Graphics Rules.sgr文件替换安装后的Graphics Rules.sgr文件。
3.现在每个窗口的标题都会显示版本号和作者。

修改
====
1.将安装中窗口的安装详细文本框和显示安装详细复选框删除。
2.修改了验证文件完整性窗口和安装中窗口的Tab键顺序。
3.在关于窗口的鸣谢文本框里添加了绿色食品台风的名字。
4.修改了验证文完整性的Data\SC4.rar文件的MD5值。
5.将安装完成窗口的安装已完成前的图标删除。
6.将安装选项窗口的安装目录文本框的是否输入有效的路径判断的激活方式由文本改变时激活改为点击安装按钮激活。
7.如果在安装某一组件中出现错误（或异常），那么该组件会显示为安装失败。
8.将验证文件完整性窗口的取消验证提示框的标题由错误改为警告。
9.删除了未使用的引用。

修复
====
1.修复了无法安装模拟城市4的bug（感谢绿色食品台风发现此bug）。
2.修复了如果选择安装英文语言补丁，在安装中窗口会发生异常的bug。
3.修复了如果模拟城市4安装失败，在安装完成窗口仍然显示为安装成功的bug。
4.修复了如果已经安装了DAEMON Tools，在安装中窗口和安装完成窗口仍然会显示DAEMON Tools项的bug。
5.修复了如果无法安装4GB补丁（非64位系统），在安装中窗口和安装完成窗口仍然会显示4GB补丁项的bug。
6.修复了即便在安装选项窗口已经取消了4GB补丁的安装，在安装中窗口仍然会显示4GB补丁项的bug。
7.修复了即便取消验证文件完整性后验证文件线程仍然在验证文件且验证完成后会重复显示主窗口的bug。
8.修复了如果模拟城市4或语言补丁安装失败，安装完成窗口的对应项的图标仍然是成功图标的bug。
9.修复了如果模拟城市4安装失败仍然会安装其他组件的bug。
10.修复了无法安装语言补丁和注册表信息的bug。
11.修复了无法安装更新的bug。
12.修复了安装选项窗口的安装路径文本框可以输入以非字母开头的路径的bug。
13.修复了如果在安装选项窗口的安装路径文本框输入诸如C:\的路径会提示安装路径不能包含以下文本的bug。
14.修复了安装选项窗口的安装所需要的空间显示不正确的bug。
15.修复了如果安装镜像版模拟城市4，仍然会导入硬盘版模拟城市4的注册表值的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 1.0.18 正式版 (2015-06-02)
====================================================================================

新增
====
1.在安装选项窗口添加了快速选择组件组合框。
2.在安装中窗口和安装选项窗口添加了标题文本标签。
3.现在每次启动时都会检查文件完整性。
4.在安装选项窗口的安装组件里添加了4GB补丁组件。
5.现在可以自动安装镜像版模拟城市4了。
6.添加了每次启动时检测并安装更新的功能。

修改
====
1.现在可以直接修改安装选项窗口的安装路径文本框的内容了。
2.修改了程序集信息。
3.现在可以在安装选项窗口点击同意EA EULA复选框来查看EULA。
4.将安装选项窗口显示组件详情方式由点击组件名改为鼠标悬浮在组件名上。
5.修改了Tab键顺序。
6.修改了安装选项窗口的部分组件说明。

修复
====
1.修复了安装中窗口的安装任务列表框的图标显示错位的bug。
2.修复了即便已经安装了DAEMON Tools，安装选项的安装组件列表框的DAEMON Tools项仍然存在的bug。
3.修复了在安装选项窗口的选择安装路径对话框的可以选择安装在非硬盘分区上的bug。
4.修复了安装选项窗口和安装中窗口的取消对话框会在任务栏上建立图标的bug。
5.修复了安装选项窗口DAEMON Tools的占用大小会加到模拟城市4占用大小里的bug。
6.修复了如果安装路径里有空格会安装失败或安装到Data文件夹下的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 15w21d(0.2.40) 快照预览版 (2015-05-23)
====================================================================================

新增
====
1.现在语言补丁安装失败也会对应到安装中窗口和安装完成窗口组件列表框语言补丁的图标上。
2.现在可以自动安装DAEMON Tools了。

修改
====
1.将安装完成窗口的运行模拟城市4的函数改为Process.Start。
2.修改了安装选项窗口的组件说明。
3.将主界面按钮的字体改为微软雅黑，字号改为五号（10.5pt）。

修复
====
1.修复了安装完成窗口的链接无法点击的bug。
2.修复了在安装选项窗口即便选中免CD补丁，DAEMON Tools仍然被选中的bug。
3.修复了在安装选项窗口选中硬盘版后就不能选中DAEMON Tools项的bug。
4.修复了在安装选项窗口选中可选组件和附加任务下的组件后在安装中窗口不会安装选中的组件，而安装未选中的组件的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 15w21c(0.2.31) 快照预览版 (2015-05-21)
====================================================================================

新增
====
1.如果部分组件安装失败则安装中窗口和安装完成窗口的组件列表框对应组件的图标会变成失败图标。

修改
====
1.安装选项窗口的安装路径文本框只能通过浏览按钮改变内容。
2.如果安装的是硬盘版且系统是64位则导入64位注册表数据。
3.删除了无用的EnableWindowAPI函数。
4.将编译方式改为Release，以便加快程序运行速度。

修复
====
1.修复了安装程序会将模拟城市4安装到Data文件夹下的bug（感谢坐在鸭子发现此bug）。
2.修复了安装选项窗口的模拟城市4安装目录文本框的内容无法跟选择文件夹对话框的内容同步的bug。
3.修复了安装选项窗口的选择安装路径对话框的根目录为Common Files的bug。
4.修复了安装选项窗口的安装目录需要的硬盘空间标签不会变化的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 15w21b(0.2.22) 快照预览版 (2015-05-20)
====================================================================================

新增
====
1.如果安装的是硬盘版会导入镜像版安装程序修改的注册表数据。
2.在主界面上增加了关于按钮。
3.在安装中窗口的安装任务列表框增加了图标。
4.增加了安装完成窗口的内容。

修改
====
1.将语言补丁导入注册表数据的方式由外部运行reg文件导入改为代码内导入数据。
2.修改了窗口标题。
3.修改了程序集信息。
4.修改了安装选项窗口的imagelist的图像名。
5.修改了Tab键顺序。

修复
====
1.修复了无法安装语言补丁的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 15w21a(0.2.12) 快照预览版 (2015-05-19)
====================================================================================

新增
====
1.增加了更新说明。
2.在安装中窗口正在安装组件时会自动禁用取消按钮和关闭按钮。
3.增加了主界面的背景图片。

修改
====
1.将安装完成窗口的起始位置改成屏幕中央。
2.将安装选项窗口中组件选项的复选框修改为自定义图片。
3.修改了程序集信息。
4.修改了API函数的参数类型和名称。

修复
====
1.修复了安装中窗口的安装任务列表框无法跟安装选项窗口里的组件选项同步的bug。
2.修复了点击安装选项窗口的安装按钮后发生ArgumentNullException异常的bug。
3.修复了安装完成后不会跳转到安装完成窗口的bug。
4.修复了如果不用管理员权限执行程序，在安装中窗口会发生UnauthorizedAccessException异常的bug。
5.修复了在安装中窗口，安装开始后发生InvalidOperationException异常的bug。

模拟城市4 豪华版 自动安装程序(SC4AutoInstall) 15w20a(0.1.0) 快照预览版 (2015-05-17)
====================================================================================
初版。
