---
layout: post
title: Innovative Project Proposal
author: [陳厚任]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is to propose an innovative project and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
### Homework Report
**Contents:**<br>
* **應用與功能說明**
  - Specify the future home application, and Describe the key features
  - Describe the key features which may be applied to the home space (kitchen, living room, play room, study room, bed room)
* **設計考量與所需相關技術**
  - List all design considerations and the required technologies
* **系統方塊圖**
  - Draw a System Block Diagram

---
## 家用飛行機器人
### 應用功能說明
1. 居家監控：外出時可隨時查看家裡各處狀況
2. 環境監測：溫濕度感測+瓦斯偵測+空氣品質偵測 
3. 清潔環境：撢灰塵, 除臭
4. 丟棄垃圾：丟棄小型垃圾袋至垃圾車或社區資源回收區
5. 餐飲服務：遞送調味料, 可樂, 水果, 零食

### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式:共軸雙旋翼
2. 供電方式:電池＋自動充電
3. 聯網方式: WiFi 或 BLE to中控電腦

**所需相關技術：**
1. 飛行姿態偵測與控制: ESP32 + MPU6050 + PID controller
2. 溫濕度感測 & 氣體偵測: HTU21D + MQ2 + MQ7 + MQ135
3. 紅外線遙控: IR-LED 
4. 影像傳輸: ESP32-CAM模組
5. 物品夾具：懸吊掛勾, 磁鐵吸吊
6. 服務器: 具AI加速(GPU)
  - 影像物件偵測辨識: CSL-YOLO
  - 任務規劃控制: Mission Planner with Floorplan

### 系統方塊圖
![](https://github.com/rkuo2000/MCU-course/blob/main/images/FutureHome_flying_robot.png?raw=true)
---
## Market Analysis (市場分析)
![](https://blog.hubspot.com/hs-fs/hubfs/tam-sam-som.png?width=1200&name=tam-sam-som.png)

---
### TAM of Future Home Products
The Target Market size (TAM) of Future Home Products is the number of household.<br>

---
### Taiwan Households = 8.93M (台灣 9百萬戶）
* [Total number of households in Taiwan from 2010 to 2020(in 1,000s)](https://www.statista.com/statistics/330804/taiwan-national-total-number-of-households/#:~:text=By%20the%20end%20of%202020,households%20in%20the%20previous%20year.)

### Japan Households = 57.2M (日本 5千7百萬戶)
* [Number of Households in Japan](https://www.helgilibrary.com/indicators/number-of-households/japan/) 

### South Korea Households = 19.9M (南韓 2千萬戶)
* [Number of Households in South Korea](https://www.helgilibrary.com/indicators/number-of-households/south-korea/)

---
### American Households = 129.93M (美國 1.3億戶)
* [Number of households in the U.S. from 1960 to 2021(in millions)](https://www.statista.com/statistics/183635/number-of-households-in-the-us/)<br>
* [The average American household consisted of 2.51 people in 2021.](https://www.statista.com/statistics/183648/average-size-of-households-in-the-us/)<br>

---
### [Number of private households in selected European countries in 2020](https://www.statista.com/statistics/868008/number-of-private-households-in-the-eu/)
![](https://github.com/rkuo2000/MCU-course/blob/main/images/Households_number_Europe2020.png?raw=true)
* Germany households = 40,120.9K **(德國 4千萬戶)**
* France households  = 30,304K **(法國 3千萬戶)**
* United Kingdom households = 27,792K **(英國 2千8百萬戶)**
* Italy households = 26,079K **(義大利 2千6百萬戶)**
* Turkey households = 24,920.1K **(土耳其 2千5百萬戶)**
* Spain households = 18,793.9K **(西班牙 1千9百萬戶)**
* Poland households = 14,723.6K **(波蘭 1千5百萬戶)**

---
### Germany Households = 40.546M (in 2020)
* [Number of households in Germany from 2000 to 2020, by size(in 1,000)](https://www.statista.com/statistics/464187/households-by-size-germany/) 
  - one person: 16,476K
  - two persons: 13,778K
  - three persons: 4,915K
  - four persons: 3,970K
  - five persons: 1,407K
  
---
### France Households = 29.7M 
* [Number of Households in France](https://www.helgilibrary.com/indicators/number-of-households/france/)
* The average household size in France in 2020 is **2.2** people per household.

---
### UK Households = 28.267M 
* [Number of Households in UK ](https://www.ibisworld.com/uk/bed/number-of-households/44090/)
* [Number of households in the United Kingdom in 2020, by type of household(in 1,000s)](https://www.statista.com/statistics/961002/households-in-the-united-kingdom-uk-by-type/)<br>

---
### Canada Households = 10.5M (加拿大 1千萬戶)
* [Number of families in Canada from 2006 to 2021(in millions)](https://www.statista.com/statistics/443323/families-in-canada/)

### Mexico Households = 34.8M (墨西哥 3千4百萬戶)
* [Number of Households in Mexico](https://www.helgilibrary.com/indicators/number-of-households/mexico/) 

---
### Brazil Households = 72.4M (巴西 7千2百萬戶)
* [Number of households in Brazil from 2012 to 2019(in 1,000s)](https://www.statista.com/statistics/870646/brazil-number-households/)

### Argentina Households = 13.8M (阿根廷 1千3百萬戶)
* [Number of Households in Argentina](https://www.helgilibrary.com/indicators/number-of-households/argentina/)

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

