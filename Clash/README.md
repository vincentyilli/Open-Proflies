下载Clash for Windows
---
### [CFW下载地址](https://github.com/Fndroid/clash_for_windows_pkg/releases)
* 建议下载便携版`Clash.for.Windows-x.xx.xx-win.7z`，并于`Clash for Windows`目录下新建`data`文件夹，以启用便携模式
### [CFW汉化补丁](https://github.com/BoyceLig/Clash_Chinese_Patch/releases)   
* 下载 `app.7z` 或 `app.zip` 文件(两个压缩包内容一样)后，解压压缩包，请自行替换`Clash for Windows\resources\app.asar`目录中的 `app.asar` 文件



本地配置转换
---
* CFW中导入 **配置**
```
https://ghproxy.com/https://raw.githubusercontent.com/Repcz/Open-Proflies/main/Clash/CFW.yaml
```
* 修改配置`proxy-providers`中的机场订阅地址
```
proxy-providers:
  All:
    type: http
    url: "https://api.v1.mk/sub?target=clash&url=你的订阅链接&list=true&udp=true"
    # 可以使用任意类型的链接替换上面文字，多个链接使用英文符号的竖杠|隔开一起写上即可
    # 也可以使用在线订阅转换，在进阶模式中勾选`输出为Node List`，将Clash订阅链接转换为只包含节点信息的配置，并替换掉整个引号""内的链接
    # 建议使用本地自建后端订阅转换
```




***


 <details>
  <summary>AD</summary>
   
> 根据自身网络环境选择，建议月付或季付

|☄️Helium Network|[:link:官网](https://console.henet.uk/#/register?code=84Nb9Jzl)||
|:--|:--:|:--:|
|套餐名称|流量情况|价格|
|Bronze🚀(12个月起)|200G/月|￥50/年|
|Silver🚀(3个月起)|350G/月|￥21/季|
|Gold🚀|540G/月|￥11/月|
|Platinum🚀|1000G/月|￥15/月|
|Dimon🚀|2000G/月|￥30/月|
|200G不限时🚀|200G|￥10/一次性|
|400G不限时🚀|400G|￥20/一次性|
|800G不限时🚀|800G|￥40/一次性|

 </details>

