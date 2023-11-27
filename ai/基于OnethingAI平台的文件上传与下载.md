## 序言
> 不念过去，不畏将来，只争朝夕，不负韶华！

## 上传文件到实例
### 方式一: 百度网盘

详情参考[公共网盘使用](https://onethingai.com/docs/cloud_drive/)

### 方式二: JupyterLab

0.开机

1.点击右侧 JupyterLab 按钮，打开 JupyterLab 页面。

![console.png](alchemy%2Fimages%2Fconsole.png)

2.通过左侧文件目录，选择要上传到的目标文件夹。

![dir_0.png](images%2Fdir_0.png)

3.点击上传文件按钮上传。

![upload_1.png](images%2Fupload_1.png)

4.或者通过拖拽需要上传的文件到左侧目录进行上传。

![upload_2.png](images%2Fupload_2.png)

5.等待上传完成。

![upload_3.png](images%2Fupload_3.png)

### 方式三: JupyterLab + 命令

0.开机

1.点击右侧 JupyterLab 按钮，打开 JupyterLab 页面。

![console.png](alchemy%2Fimages%2Fconsole.png)

2.点击 Terminal 按钮进入终端界面。

![terminal.png](alchemy%2Fimages%2Fterminal.png)

3.通过命令进入到需要上传文件的目标路径，或者自己创建文件夹用于上传文件。

**切换文件路径命令**

```bash
cd 文件路径
```

![cd_1.png](alchemy%2Fimages%2Fcd_1.png)

**创建文件夹命令**

```bash
mkdir 文件夹名称
```

![mkdir.png](alchemy%2Fimages%2Fmkdir.png)

4.通过命令下载文件。

```bash
# 以下两个命令都可以用于下载文件
curl 文件链接
wget 文件链接
```
![download_1.png](images%2Fdownload_1.png)
![download_2.png](images%2Fdownload_2.png)
![download_3.png](images%2Fdownload_3.png)
![download_4.png](images%2Fdownload_4.png)
![download_5.png](images%2Fdownload_5.png)
![download_6.png](images%2Fdownload_6.png)

## 下载文件到本地
### 方式一: JupyterLab

0.开机

1.点击右侧 JupyterLab 按钮，打开 JupyterLab 页面。

![console.png](alchemy%2Fimages%2Fconsole.png)

2.通过左侧文件目录，找到需要下载的文件。

![dir_0.png](images%2Fdir_0.png)

3.选择文件(可多选)，点击右键，点击下载选项下载文件。

![download_0.png](images%2Fdownload_0.png)

---
**注意**

+ 批量下载单次最多下载10个文件，想要下载更多，可以分批下载或者打包好后一次性下载。
+ 不支持文件夹下载


