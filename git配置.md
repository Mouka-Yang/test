# Git 及 Github 配置

## 下载安装Git

在 https://git-scm.com/download/win 下载 Windows 64 bit Git 安装包

![1548395655405](C:\Users\BUSDRI~1\AppData\Local\Temp\1548395655405.png)

下载及安装完成后，将目录 ...\Git\cmd 加入PATH中

![1548395815183](C:\Users\BUSDRI~1\AppData\Local\Temp\1548395815183.png)

测试

![1548395889229](C:\Users\BUSDRI~1\AppData\Local\Temp\1548395889229.png)

此时 Git环境 已配置好

## VsCode Git配置

### 创建Git项目

用Vs code 打开需要同步的项目，点击左上角版本同步图标

![1548396120224](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396120224.png)

此时还未关联 Git，点击小图标初始化Git项目

![1548396269748](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396269748.png)

结果如下所示，`changes`列表里是已修改且还未进行同步的文件（因为初次创建，Git项目为空，文件夹中的文件都没有同步到Git中）

![1548396317521](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396317521.png)

将文件夹中的文件同步到Git中

![1548396935228](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396935228.png)

出现如下对话框，选择yes或always即可

![1548396755708](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396755708.png)

提交完成

![1548396998100](C:\Users\BUSDRI~1\AppData\Local\Temp\1548396998100.png)

### 同步Git项目

#### 修改文件

当修改了已提交到Git项目中的文件时（上图所示4个），vs code会自动检测到修改并显示

![1548397200237](C:\Users\BUSDRI~1\AppData\Local\Temp\1548397200237.png)

当需要再次同步时，同样只需要输入 `同步说明`并点击同步即可

![1548397291716](C:\Users\BUSDRI~1\AppData\Local\Temp\1548397291716.png)

#### 创建文件

当在文件夹中创建了新文件，vs code会检测到创建并显示，可用如上方法将其同步到Git项目中

![1548397436428](C:\Users\BUSDRI~1\AppData\Local\Temp\1548397436428.png)

### 注意

以上操作和Github无关，只是进行了本地项目同步