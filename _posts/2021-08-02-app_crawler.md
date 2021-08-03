---
layout: post
title:  "Simplest App Crawler Tutorial (Step 1: Preparations)"
author: Iris
---
#### PC: MacBook Pro (High Sierra 10.13.6); Mobile device: iPad mini (14.6); Charles (version 4.5.6)
#### App: Blued
## Charles
### Charles Intro
We need Charles to analyze requests, responses and the HTTP headers. You can find Charles [here](https://www.charlesproxy.com).
![image](https://user-images.githubusercontent.com/55306536/127965639-43808bed-5398-4048-b6d4-35caaed000eb.png)
Click Download button on the right hand side and choose the right version for your OS. Charles is not free. You can try Charles for 30 days and buy a lisense for further use (you can get one from taobao 🤫). 
![image](https://user-images.githubusercontent.com/55306536/127966686-4a247fb1-a56d-477f-a918-2e0860f0574f.png)
### Proxy Setting for your PC and the mobile device
❗️❗️❗️ Before installation, make sure your PC and your mobile device are on the same Wi-Fi network.
#### Install certificate for PC (Mac for me)
Open Charles —> find menu tree (on the top) -> help -> SSL Proxying -> Install Charles Root Certificate

<img width="1126" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127976951-4408e667-f8af-4a9f-9ee9-8d53bb76e2b0.png">
In the pop up window (Keychain Access), you can find the installed certificate

<img width="915" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977026-0af8bf32-ce35-42c3-ba53-8694f0e12cac.png">
Double click this item, click Trust in the pop up window

<img width="625" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977161-b0ca8b4d-c6e7-4c59-aefc-29dd10821ef5.png">

Select Always Trust in When using this certificate, then save your settings.

<img width="413" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977221-761e3cf5-9341-4e1e-aaeb-82aca53dc47f.png">

Move back to Charles, find the meanu tree -> Proxy -> choose MacOS Proxy

![image](https://user-images.githubusercontent.com/55306536/128007899-cc624e4e-f935-4dc2-b15c-500c564aab22.png)

Again in the meanu tree -> click Proxy Settings

![image](https://user-images.githubusercontent.com/55306536/128007993-ac4db6e6-5fa5-4ebd-97fa-c3b5ad47563a.png)

Choose the following two options

![image](https://user-images.githubusercontent.com/55306536/128008488-26be9d6c-67b3-4c3e-9a8b-0f46327cecbf.png)

#### Install certificate for mobile device (iPad mini for me)
Open Charles —> find menu tree (on the top) -> help -> SSL Proxying -> Install Charles Root Certificate on a Mobile Device or Remote Browser

<img width="1266" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977306-45937f0e-3384-4091-b503-242ffc46d6f5.png">
You can find the instructions in the pop up window

<img width="891" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977397-e44dceac-47ac-428d-a9cd-1b79e6d97cd1.png">
Move to the mobile device. For my iPad mini, Setting -> Wi-Fi -> Connect the same network as PC -> click the blue button at the corner

<img width="459" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977454-736b149e-2d60-4263-80ed-8ae83a9e3f8d.png">

Move to the bottom of this page -> find HTTP PROXY -> click Configure Proxy

<img width="305" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977503-52f66b5e-96a6-4d23-b976-8b7f2f93591d.png">

Choose Manual -> Input Server (IP) and Port information  > click Save

<img width="310" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977574-aa9ab506-7fe4-4011-a71f-f04924b52e29.png">

Move to Safari -> enter chls.pro/ssl -> download the certificate following the instruction 

<img width="531" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977629-dd16898d-7d72-4afe-8fe5-4ec4925e3789.png">

Move to Setting -> General -> About -> Certificate Trust Settings 
You can find the certificate you just download
Click the button on the right hand side and click continue in the pop up window

<img width="302" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/55306536/127977688-15839f59-ba39-403d-b840-949247aa89d2.png">

Till now, you have made all preparations for building the app crawler 😝😝😝
