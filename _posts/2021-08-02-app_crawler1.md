---
layout: post
title:  "Simplest App Crawler Tutorial (Step 2: Get all we need)"
author: Iris
---
#### PC: MacBook Pro (High Sierra 10.13.6); Mobile device: iPad mini (14.6); Charles (version 4.5.6)
#### App: Blued
Before this part, please make sure you have made all preprations in [Step 1](2021-08-02-app_crawler.md). In Step 2, you will know how to get headers, cookies, request, and responses in Charles.

## Open Charles
Make sure the button below (at the top of Charles) is red (meaning it starts recording)

<img src="https://user-images.githubusercontent.com/55306536/128009931-062ce439-469f-44de-8863-63f494544e91.png" width="500">

## Open Blued and log in
You can find corresponding information about Blued in Charles

<img src="https://user-images.githubusercontent.com/55306536/128010288-54ed7382-cc23-4c9d-a304-672674a3d2b9.png" width="500">

## Request
Right click any item and choose Copy URL, you can get corresponding request

<img src="https://user-images.githubusercontent.com/55306536/128010429-8f39cf17-cbef-429c-8fb7-63a7a6ab46ab.png" width="500">

## Headers and cookies 
Click this item, you can find the corresponding headers and cookies information on the top panel of the right column 

<img src="https://user-images.githubusercontent.com/55306536/128010507-1247fca4-d32c-42ef-9020-03e89be3a17d.png" width="500">

## Responds
You can find the corresponding request results on the bottom panel of the right column (click the JSON Text button)
 
<img src="https://user-images.githubusercontent.com/55306536/128010593-6b79ddaf-09d9-4ce9-b7eb-fc4b3881b3a5.png" width="500">

### You can explore other information. For example, if you want to now how to get all follower information, adopt the following steps:
Step 1: randomly select one user, click his profiles picture, you can find there are new folders under the ticktocks/users folder

<img src="https://user-images.githubusercontent.com/55306536/128010765-46d582ab-2783-4cbb-91ae-e1ffb42bde81.png" width="500">

Step 2: click “Followers” in his home page. you can find there are new folders under the users folder

<img src="https://user-images.githubusercontent.com/55306536/128010842-005de527-5462-4925-8ce7-697fd3d59f38.png" width="500">

Step 3: click any folder (named by the user id) under the “user” folder, you can get the information about this user’s followers

<img src="https://user-images.githubusercontent.com/55306536/128010904-997576b7-fbe5-465b-b357-601bdec0ae3c.png" width="500">

Step 4: based on this item under the user id folder, you can get the headers, request, and responds information as before







