自己打标训练了一系列lora模型，并使用confyUI工作流制作了不同Lora效果对比图    
参考图：    
![微信图片_2025-09-01_225401_294](https://github.com/user-attachments/assets/d07ba1b9-ec3b-4bbb-9be8-ede2b20a2f25)    
以majicmixRealistic_v7为基底，25张图片为标注数据，训练出了六版不同的lora模型，其中v1，v2，使用的是原始图片人脸裁剪，v3使用的是原始图片不裁剪，v4，v5，v6采用的是放大后的高清图片。    
v1：  
 <img width="512" height="512" alt="ComfyUI_temp_vgzyg_00033_" src="https://github.com/user-attachments/assets/3b11bed4-5b2a-413d-92b7-6c890cfeafa8" />    
v2：  
<img width="512" height="512" alt="ComfyUI_temp_vgzyg_00034_" src="https://github.com/user-attachments/assets/6f17b595-54a1-4231-ad1c-e943044d4c53" />  
v3：  
<img width="512" height="512" alt="ComfyUI_temp_vgzyg_00036_" src="https://github.com/user-attachments/assets/45266a13-351a-470c-98ee-d89d59c0ea74" />  
v4：
<img width="512" height="512" alt="xsq_v4_e000007_00_20250904235143_190623" src="https://github.com/user-attachments/assets/be6ac4e1-9770-4147-b8c7-5729c61d5b3e" />  
v5:  
<img width="512" height="512" alt="xsq_v5_e000010_00_20250905004253_190623" src="https://github.com/user-attachments/assets/1375ef73-9ad7-4c38-b7c4-0b5f851f12f8" />  
v6:  
<img width="512" height="512" alt="xsq_v6_e000002_00_20250905012414_2333" src="https://github.com/user-attachments/assets/c525b327-d235-4970-af33-96de415c1eff" />  

相同提示词，种子情况下对比图如下
   
<img width="13440" height="3072" alt="0002_XYZ图表" src="https://github.com/user-attachments/assets/20d39471-e218-42bb-aebe-1dfa404a1cee" />    
  
六个lora模型见releases
