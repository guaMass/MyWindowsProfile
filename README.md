# MyWindowsProfile
This repository will be used for building up my windows terminal settings.

## 添加windows terminal到右键菜单
* 下载icon文件，以便右键菜单上显示wt图标。
* 下载reg文件，确定自己计算机的wt图标存储位置和wt可执行文件存储位置。
* 保存，执行reg文件。
* 修改wt的profile文件，在profile->defaults->startingDirectory中设置参数，如下：

``` json
"profiles":
    {
        "defaults":
        {
            "startingDirectory": "./"
        },
    }
```
效果如下

![addwt]()