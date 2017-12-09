# Xiaomi_Yi
## 一个基于Python的小蚁运动相机控制脚本
## 汉化：Tiya Anlite
## Xiaomi Yi Camera Control&Configure GUI and via python scripts

## 原作者项目地址：https://github.com/deltaflyer4747/Xiaomi_Yi
## GitUrl：https://github.com/deltaflyer4747/Xiaomi_Yi

## 向原作者捐款：http://sw.deltaflyer.cz/donate.html
## Donate：http://sw.deltaflyer.cz/donate.html

### Multiplatform脚本可以运行于Windows, Linux 和 Mac
### Multiplatform, runs on Windows, Linux and Mac!

#### 通过PC与相机使用WIFI连接，可控制选项：拍照，录像与实时预览，配置和文件管理
#### Control (Photo, Record, Live View), Configure & Manage files via PC & Wifi.

### CC.exe目前尚未构建完成，汉化完毕之后会构建
### CC.exe is compiled - NO PYTHON INSTALLATION NEEDED

#### CC.pyw为主脚本，需要窗口界面Tkinter库的支持
#### CC.pyw - for all systems capable of running python with Tkinter


-------
##### Obsolete

运行此脚本的Python版本为2.7.x
For these scripts you need Python 2.7.x https://www.python.org/downloads/ 

不建议使用windows自带的记事本，建议使用其他的文本编辑软件
Windows Notepad is derping about newline style, use something better than that, like Notepad++, PsPad, or even WordPad

在settings.py中设置相机IP，无需再运行此脚本
Edit settings.py with your camera IP. No need to launch this script

编辑options.txt中的配置项，再运行Camera_set.py脚本便可设置相机参数
* Edit options.txt (un/comment lines as needed) and launch Camera_set.py to set uncommented options

Camera_all_options.py脚本会显示所有可选参数和值
* Camera_all_options.py displays all possible options for all possible variables

Camera_get.py脚本显示目前相机的配置
* Camera_get.py displays current settings from camera

Camera_photo.py脚本可以使相机拍摄一张照片
* Camera_photo.py captures single photo

Camera_record_start.py和Camera_record_stop.py脚本可以控制录像的开始与停止
* Camera_record_start.py & Camera_record_stop.py starts / stops video recording respectively

Camera_video_stream.py脚本将会打开实时预览，以便通过支持RTSP协议的软件查看（例如VLC软件）
* Camera_video_stream.py enables streaming for RTSP capable player (for example VLC)
