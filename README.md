<p align="center">
  <a href="https://play.google.com/store/apps/dev?id=7086930298279250852" target="_blank">
    <img alt="" src="https://github-production-user-asset-6210df.s3.amazonaws.com/125717930/246971879-8ce757c3-90dc-438d-807f-3f3d29ddc064.png" width=500/>
  </a>  
</p>

### Our facial recognition algorithm is globally top-ranked by NIST in the FRVT 1:1 leaderboards. <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>  
[Latest NIST FRVT evaluation report 2024-12-20](https://pages.nist.gov/frvt/html/frvt11.html)  

![FRVT Sheet](https://github.com/user-attachments/assets/16b4cee2-3a91-453f-94e0-9e81262393d7)

#### 🆔 ID Document Liveness Detection - Linux - [Here](https://web.kby-ai.com)  <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>
#### 🤗 Hugging Face - [Here](https://huggingface.co/kby-ai)
#### 📚 Product & Resources - [Here](https://github.com/kby-ai/Product)
#### 🛟 Help Center - [Here](https://docs.kby-ai.com)
#### 💼 KYC Verification Demo - [Here](https://github.com/kby-ai/KYC-Verification-Demo-Android)
#### 🙋‍♀️ Docker Hub - [Here](https://hub.docker.com/u/kbyai)

# Automatic-License-Plate-Recognition-iOS

## Overview

We implemented `ANPR/ALPR(Automatic Number/License Plate Recognition)` engine with unmatched accuracy and precision by applying SOTA(State-of-the-art) deep learning techniques in this repository. </br>

KBY-AI's `LPR` solutions utilizes artificial intelligence and machine learning to greatly surpass legacy solutions. Now, in real-time, users can receive a vehicle's plate number.

The `ALPR` system consists of the following steps:
- Vehicle image capture
- Preprocessing
- Vehicle detection
- Number plate extraction
- Charater segmentation
- Optical Character Recognition(OCR) </br>

The `ALPR` system works in these strides, the initial step is the location of the vehicle and capturing a vehicle image of front or back perspective of the vehicle, the second step is the localization of Number Plate and then extraction of vehicle Number Plate is an image. The final stride uses image segmentation strategy, for the segmentation a few techniques neural network, mathematical morphology, color analysis and histogram analysis. Segmentation is for individual character recognition. Optical Character Recognition (OCR) is one of the strategies to perceive the every character with the assistance of database stored for separate alphanumeric character.

### ◾License Plate Recognition SDK Product List
  | No.      | Repository | SDK Details | Status |
  |------------------|------------------|------------------|------------------|
  | 1        | [LPR - Linux](https://github.com/kby-ai/Automatic-License-Plate-Recognition-Docker)    | License Plate Recognition Linux SDK | Available |
  | 2        | [LPR - Docker](https://hub.docker.com/r/kbyai/license-plate-recognition)    | License Plate Recognition Docker Image | Available |
  | 3        | [LPR - Flutter](https://github.com/kby-ai/Automatic-License-Plate-Recognition-Flutter)    | License Plate Recognition Flutter SDK | Available |
  | 4        | [LPR - C#](https://github.com/kby-ai/Automatic-License-Plate-Recognition-CSharp-.NET)    | License Plate Recognition C# SDK | Available |
  | 5        | [LPR - Android](https://github.com/kby-ai/Automatic-License-Plate-Recognition-Android)    | License Plate Recognition Android SDK | Available |
  | ➡️        | <b>[LPR - iOS](https://github.com/kby-ai/Automatic-License-Plate-Recognition-iOS)</b>    | <b>License Plate Recognition iOS SDK</b> | <b>Available</b> |

> To get more products, please visit products [here](https://github.com/kby-ai):<br/>

## Screenshots
<p float="left">
  <img src="https://github.com/user-attachments/assets/d19998a8-9b94-47dd-86f5-a206e430d4cf" width=200/>
  <img src="https://github.com/user-attachments/assets/34be1181-fe83-4be0-b955-7c174961410b" width=200/>
  <img src="https://github.com/user-attachments/assets/4d17e31e-d1e0-492a-98bd-c34ed68c3a6a" width=200/>
</p>

<p float="left">
  <img src="https://github.com/user-attachments/assets/dc819a46-cdc7-4459-aca1-f94da8e1a14e" width=200/>
  <img src="https://github.com/user-attachments/assets/84f89d18-9c34-465e-a855-8c2b4467ce69" width=200/>
  <img src="https://github.com/user-attachments/assets/23645cc7-2f79-4deb-becd-2d88cb32c983" width=200/>
</p>

## Performance Video
You can visit our `YouTube` video for `ANPR/ALPR` model's performance [here](https://www.youtube.com/watch?v=sLBYxgMdXlA) to see how well our demo app works.</br></br>
[![ANPR/ALPR Demo](https://img.youtube.com/vi/sLBYxgMdXlA/0.jpg)](https://www.youtube.com/watch?v=sLBYxgMdXlA)</br>

## SDK License
- The code line below shows how to update `SDK` with the `license key`: https://github.com/kby-ai/Automatic-License-Plate-Recognition-iOS/blob/491bcd3d6df41d705fac8147adb04c5ae035ac14/ALPRDemo/ViewController.swift#L35-L40
- To request `license key`, please contact us:</br>
🧙`Email:` contact@kby-ai.com</br>
🧙`Telegram:` [@kbyaisupport](https://t.me/kbyaisupport)</br>
🧙`WhatsApp:` [+19092802609](https://wa.me/+19092802609)</br>
🧙`Discord:` [KBY-AI](https://discord.gg/CgHtWQ3k9T)</br>
🧙`Teams:` [KBY-AI](https://teams.live.com/l/invite/FBAYGB1-IlXkuQM3AY)</br>

## About SDK

### 1. Set up
1. Copy the `SDK` library (`alprsdk.framework` folder) and pre-built `onnxruntime` library (`onnxruntime.framework` folder) to the `root` folder in your project.

2. Add `alprsdk.framework` and `onnxruntime.framework` to your project in `Xcode`.

> Project Navigator -> General -> Frameworks, Libraries, and Embedded Content

![image](https://github.com/user-attachments/assets/83717e85-0613-40f7-ae8e-f709b85bb314)

3. Add the bridging header to your project settings

> Project Navigator -> Build Settings -> Swift Compiler - General

![image](https://github.com/user-attachments/assets/88d55cac-4507-428c-b9af-d6865ee02642)


### 2 API Usages
  - Activate the `SDK` by calling the `setActivation` method:
  ```kotlin
    var ret = AlprSdk.setActivation("xxx...")
  ```
  - Extract plates using the `extractPlates` method:
  ```kotlin
   val alprResult: AlprResult = AlprSdk.process(
        SDK_IMAGE_TYPE.ULTALPR_SDK_IMAGE_TYPE_RGBA32,
        nativeBuffer, width.toLong(), height.toLong()
   )
   val plates = AlprUtils.extractPlates(alprResult);
  ```
