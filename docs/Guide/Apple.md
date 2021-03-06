# Apple 笔记本安装虚拟机、Windows系统操作指引

!!! Warning
    **ParallelsDesktop 为商业版软件，公司并未购买版权，且在使用过程中出问题也较多，顾不建议安装** <br>
    **日常工作中，如果有 ParallelsDesktop（下文简称 pd ）的升级提示，请勿进行升级操作，否则 pd 无法正常使用。Pvm 文档不可删除，否则 Windows 系统会直接丢失。**

1、在 macOS 下，运行 Finder。

![](/imgs/apple/1.png)

2、在 Finder 窗口下，按下 Command+k，弹出服务器连接窗口，输入服务器地址：**10.1.1.5**

![](/imgs/apple/2.png)

3、“连接”后，按提示输入帐号和密码。此处，选择 注册用户，名称为 **grgbanking\OA帐号**，密码为域账号密码，即上网密码或原台式机开机密码。

![](/imgs/apple/3.png)

4、进入到 **工具软件-10-MAC虚拟机@系统**

![](/imgs/apple/4.png)

5、将该文件夹下面的两个文件拷贝到 macOS 的桌面上。

![](/imgs/apple/5.png)

6、运行 ParallelsDesktop-12.0.1-41296.dmg。

![](/imgs/apple/6.png)

7、点击“安装”。

![](/imgs/apple/7.png)

8、此处输入 macOS 的登陆密码。

![](/imgs/apple/8.png)

9、安装过程中，出现下图的提示框，请选择“否”。

![](/imgs/apple/9.png)

10、pd安装成功后，会自动运行。在新建虚拟机窗口下，选择“从PC迁移Windows”，然后“继续”。

![](/imgs/apple/10.png)

11、选择“外部存储”，然后“继续”。

![](/imgs/apple/11.png)
 
12、选择“手动选择”，然后选取“Win7forTest.pvm”文件

![](/imgs/apple/12.png)

13、对于pvm文档的文件名，可以根据个人喜好更改。然后“继续”。

![](/imgs/apple/13.png)

14、pvm文档的迁移操作，可能会耗费一点时间。此时，无需执行任何操作。

![](/imgs/apple/14.png)

15、pvm文档迁移成功后，Windows系统会自动运行，并执行虚拟机工具的安装操作

![](/imgs/apple/15.png)

16、若弹出重新启动的提示，选择“稍后重新启动”或“推迟”即可。

![](/imgs/apple/16.png)
  
17、由于该pvm文档提供给广大用户使用，所以，迁移成功后，需要进行计算机名修改操作，否则，日后使用过程中可能会出现异常。

18、在“计算机”图表上单击右键，选择“属性”。

 ![](/imgs/apple/18.png)

19、找到“计算机名称、域和工作组设置”栏目，点击“更改设置”。

 ![](/imgs/apple/19.png)

20、选择“修改”。

 ![](/imgs/apple/20.png)

21、根据个人喜好，输入新的计算机名，然后“确认”，返回上一级菜单后，点击“应用”。

 ![](/imgs/apple/21.png)

22、若弹出重新启动提示，选择重启即可。若无提示，手动操作重启即可。

23、需要退出 Window 系统时，执行正常关机操作即可。但在 macOS 段完全退出，需要在pd的图标上单击右键，选择“退出”。

 ![](/imgs/apple/23.png)

24、再次启动pd时，可能会弹出“控制中心”窗口，点击启动按钮，就可以启动Windows系统。点击系统属性按钮，可以修改此 Windows 系统的相关属性（如和 macOS 之间的硬件、文档共享设置等）。
 
![](/imgs/apple/24.png)

