## 序言
> 不念过去，不畏将来，只争朝夕，不负韶华！

## 安装

详情查看 [Stable Diffusion 插件安装](https://onethingai.com/docs/StableDiffusion/)

## 卸载

### 第一步 SD-WEB-UI 操作
1. 进入SD-WEB—UI 界面，找到 **扩展**
2. 取消勾选需要卸载的插件。
3. 点击应用更改并重启

![extend.png](images%2Fextend.png)

### 第二步骤 文件删除
4. 点击工具栏按钮 JupyterLab 进入文件管理界面
![work.png](images%2Fwork.png)
5. 通过点击左侧文件目录找到安装扩展的文件夹 /root/onethingai-tmp/app/stable-diffusion-webui/extensions
6. 找到需要卸载的插件，注意，JupyterLab 不支持直接删除文件夹，所以我们需要通过命令删除
7. 点击终端按钮进入终端界面
![remove_1.png](images%2Fremove_1.png)
8. 执行命令 pwd ，确认当前命令后所在路径为 扩展安装路径 /root/onethingai-tmp/app/stable-diffusion-webui/extensions，如果不是，可以通过 cd 命令 切换到该路径
9. 执行 rm -rf ./xxx xxx为需要卸载的扩展的名称。

```bash
# 查看当前所在路径命令
pwd
# 切换路径命令
cd /root/onethingai-tmp/app/stable-diffusion-webui/extensions
# 删除命令 xxx 为文件或者文件夹名称
rm -rf ./xxx 
```

![remove_2.png](images%2Fremove_2.png)


### 注意
一定要先执行第一步，在执行第二步，不然可能出现报错。导致无法使用。