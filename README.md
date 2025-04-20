# raspi_hat_voice_speaker_oled

![image](https://github.com/user-attachments/assets/26c51ed3-b8ef-4d7f-9af6-ca39473e8398)
![image](https://github.com/user-attachments/assets/6072c0b3-adc2-4d7c-88a4-ec18f26084f8)

## 簡介
這個Raspberry Pi HAT 整合了麥克風、音訊放大器和OLED螢幕，讓你輕鬆打造語音互動或多媒體應用！

## 設定驅動
在  
`/boot/firmware/config.txt`  
加入  
`dtoverlay=googlevoicehat-soundcard`  
重開機後就成為預設音訊輸入出裝置    
