使用方法
---


#### [CFW下载地址](https://github.com/Fndroid/clash_for_windows_pkg/releases)
* 建议下载便携版`Clash.for.Windows-x.xx.xx-win.7z`，并于`Clash for Windows`目录下新建`data`文件夹，以启用便携模式
#### [CFW汉化补丁](https://github.com/BoyceLig/Clash_Chinese_Patch/releases)   
* 下载 `app.7z` 或 `app.zip` 文件(两个压缩包内容一样)后，解压压缩包，请自行替换`Clash for Windows\resources\app.asar`目录中的 `app.asar` 文件




本地配置转换（推荐）
---
* 打开配置文件主目录
![、](https://github.com/Repcz/Open-Proflies/blob/main/Clash/Photo/%E6%89%93%E5%BC%80%E7%9B%AE%E5%BD%95.png)
* 在目录下新建`all.yaml`
* 将机场下发的配置文件内容复制进`all.yaml`
> `all.yaml`可以改成任意名称，但必须于同步修改配置文件中的`path: ./all.yaml`，适用于切换多个机场

![、、](https://github.com/Repcz/Open-Proflies/blob/main/Clash/Photo/%E6%96%B0%E5%BB%BAall.yaml.png)

* CFW中导入 **配置**

**_完整配置_**（包含多种分流规则）
```
https://ghproxy.com/https://raw.githubusercontent.com/Repcz/Open-Proflies/main/Clash/CFW.yaml
```


**_简洁配置_**（仅支持国内、国外分流）

```
https://ghproxy.com/https://raw.githubusercontent.com/Repcz/Open-Proflies/main/Clash/CFW_lite.yaml
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

纯懒人方法见：[订阅配置转换](https://github.com/Repcz/Open-Proflies/wiki/Clash-For-Windows#%E5%9C%A8%E7%BA%BF%E8%AE%A2%E9%98%85%E8%BD%AC%E6%8D%A2%E4%B8%8D%E6%8E%A8%E8%8D%90)


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

