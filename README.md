# 3DO-ODE-MENU-BGSOUND

此套软件可修改3DO ODE光驱板软件的开机启动画面LOGOpic，游戏列表背景图片MENUpic，背景音乐BGSOUND。

注意，可能有杀毒软件报警，请放心使用，没有病毒和木马！没有病毒和木马！没有病毒和木马！

<img width="518" height="304" alt="358d9f61529ca812abe9c8b3c42fb1e9" src="https://github.com/user-attachments/assets/be6ea3d8-f9cc-4ee8-b847-13141cd82c42" />

3DOLOGOpic.EXE的功能是修改启动画面

![IMG_1875](https://github.com/user-attachments/assets/f1da0f20-6711-454a-a419-e2e97d10003c)


3DOMENUpic.EXE的功能是更改游戏列表背景图片

![IMG_1876](https://github.com/user-attachments/assets/00a55d1c-a873-4349-bea3-d6875e8671a1)


3DOBGSOUND.EXE的功能是更改游戏列表背景音乐




文件需求：

1.需要5个文件，这里提供3DOBGSOUND.EXE，3DOMENUpic.EXE和3DOLOGOpic.EXE，还需要2个文件，一个是BOOT.ISO,一个是FFMPEG.EXE；

2.在3DO ODE的U盘或SD卡找到BOOT.ISO，建议使用最新的R5版本；

3.FFMPEG.EXE文件可在  https://www.gyan.dev/ffmpeg/builds/  下载，此站点有essentials和full版本，
均可以使用，解压缩后在BIN文件夹内。

（注：FFMPEG 7.0后，full版本不再支持Windows7和8，请下载essentials版本。）

4.运行前确保目录结构如下有5个文件，可以放在U盘或SD卡根目录：

        3DOMLOGOpic.EXE
        
        3DOMENUpic.EXE

        3DOBGSOUND.EXE
        
        BOOT.ISO
        
        FFMPEG.EXE
        
        

5.音频文件基本兼容所有格式，不管源文件是什么格式或品质，均以16Bit 44.1Khz Stereo注入BOOT.ISO

6.图片文件基本兼容所有格式。需要注意游戏列表背景图片最好使用亮度偏暗一点的图片，否则可能会看不清游戏列表字符，此软件已自动降低亮度20%，如需再次降低亮度，请自行提前处理，然后再让软件注入BOOT.ISO

3个修改软件使用方法基本相同，使用鼠标将图片或音频文件拖拉至不同功能的EXE文件上方即可。

这里以背景音乐修改软件3DOBGSOUND.EXE举例说明如何使用，其它两个软件方法相同：

方法1：

1.打开2个文件夹窗口，一个是此5个文件的文件夹，一个音频文件夹；

2.鼠标左键持续按住音频文件不松手，然后拖到3DOBGSOUND.EXE上方松开鼠标左键；

3.屏幕可见黑白字符滚动的窗口，稍后提示“请按任意键继续”，此时你可以关闭窗口；

4.此时BOOT.ISO已被修改，把它拷贝到3DO的U盘或SD；

5.插入3DO ODE运行。




方法2：

1.用鼠标右击音频文件，选择“复制”

2.用鼠标右击3DOBGSOUND.EXE，选择“粘贴”

3.屏幕可见黑白字符滚动的窗口，稍后提示“请按任意键继续”，此时你可以关闭窗口；

4.此时BOOT.ISO已被修改，把它拷贝到3DO的U盘或SD；

5.插入3DO ODE运行。




By tzmwx

2025/07/12



感谢以下软件及作者：

1.3DO homebrew encryption   v0.6a        By Charles Doty

2.OperaTool     0.01a - By Cristina Ramos

3.3DO R.E.A.L. Multiplayer ISO tool. v0.1 By nikk 

4.BOOT.ISO    R5    By Fixel

5.FFMPEG
