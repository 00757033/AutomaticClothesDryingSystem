![image](https://github.com/user-attachments/assets/ee86ea6d-f66e-4dcd-9a92-5757bf1e76f0)![image](https://github.com/user-attachments/assets/9c0bb0d9-bdaa-4917-a17c-926d662f4ec2)# AutomaticClothesDryingSystem

## Motivation
對於上班族來說，清晨天還未亮就要出門，晚上回家時已經是夜深了。
因此，我們計畫設計一個定時晾衣系統，能在每日特定的時間自動將衣服晾曬在室外，並在適當時候自動收回室內。
考慮到台灣常常陰晴不定的天氣狀況，我們希望系統能夠在下雨或陰天前自動將衣服提早收回室內，避免衣物濕潤。
系統還會在液晶螢幕上顯示現在的時間、晾衣的時間長度以及溫度，方便使用者了解衣物晾曬的狀況。

## Expected System Architecture

![image](https://github.com/user-attachments/assets/0006d660-7d08-4750-a68d-8160d7b2c44d)

## 使用儀器
![image](https://github.com/user-attachments/assets/dbd01243-0aa8-4839-a3f3-421d9efa190e)

## 執行
### 各種情境
1. 在指定時間推出衣架
2. 使用者可以手動控制，推出衣架及收回衣架
3. 太陽下山/陰天，提早收回衣架
4. 下雨，提早收回衣架
5. 在指定時間收回衣架

#所有case中，衣架移動完成後，皆會發出聲音提醒
