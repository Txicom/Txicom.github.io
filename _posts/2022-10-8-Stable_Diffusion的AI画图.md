---
date: 2022-10-8
title: 通过在本地搭建stable diffusion及使用已经训练完毕的模型实现二次元AI画图本地化
---
由于最近泄露出的NovelAI训练模型，现在可以白嫖已经训练完的model来实现AI本地画图  
### 1. 从github上下载[stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)项目
### 2. 按照网站上的教程进行配置部署

> 出现ProxyError: HTTPSConnectionPool错误  
> 可能的解决方案:  
> * 更新python至**3.10**  
> * **科学上网**
{:.prompt-warning}
### 3. 通过[磁力链接](magnet:?xt=urn:btih:5bde442da86265b670a3e5ea3163afad2c6f8ecc&dn=novelaileak&tr=udp%3A%2F%2Ftracker.opentrack)(可能已失效)下载NovelAI泄露的训练模型
> 如果想节约空间可以仅下载`novelaileak\stableckpt\animefull-latest`{:.filepath}下的model.cpkt
{:.prompt-tip}
### 4. 将训练模型放进stable diffusion要求的位置
> 将`novelaileak\stableckpt`{:.filepath}任意文件夹下的`model.ckpt`放进`stable-diffusion-webui\models\Stable-diffusion`{:.filepath}
{:.prompt-info}
### 5. 部署运行stable diffusion
> 推荐的prompt设置:  
> ```
> extremely detailed CG unity 8k wallpaper, masterpiece
> ```
> {: file='prompt'}
> **非常推荐**设置negative prompt:
> ```
> lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry
> ```
> {: file="negative prompt"}
