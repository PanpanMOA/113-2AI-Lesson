### 113-2AI-Lesson
### 姓名：潘瑩真
### 系級：美術碩一
### 課程名稱：生成式AI：文字與圖像生成的原理與實務_國立臺灣師範大學衛星課程
### 修課學期：113-2

---
## 作業1
題目：請在colab中畫一個函數圖形  

連結：[W1_函數圖形](https://colab.research.google.com/github/PanpanMOA/113-2AI-Lesson/blob/main/W1_%E5%87%BD%E6%95%B8%E5%9C%96%E5%BD%A2.ipynb)  

成果：  

<img width="268" alt="作業一 函數圖形 跑出的圖片" src="https://github.com/user-attachments/assets/07cbb626-f375-407a-aab3-a100573bbb9a" />

## 作業2
題目：打造出神經網路，以手寫辨識為目標  

連結：[W2_打造出神經網路](https://colab.research.google.com/drive/1RTl_6m6aUA8LxLpwZ7293m1ix_wA0hwo?usp=sharing)  

成果：  
![作業二 神經網路 手寫數字辨識 有更改的程式碼](https://github.com/user-attachments/assets/11532c3e-6792-4a7d-a4db-288d860b6837)  

![作業二 神經網路 手寫數字辨識截圖](https://github.com/user-attachments/assets/5c2614bc-e0a1-47fb-bb26-b4d57cf17024)  

---
## 作業3
題目: 使用 GAN對抗生成網路模型，來生成圖片  

成果：  
### 回答問題 
為什麼在生成式圖片的應用上，大家多不再使用GAN對抗生成網路，而改用Stable diffusion？（先去思考原因，不一定需要是標準答案）

如果用小朋友的畫畫遊戲來比喻，對抗生成網路GAN就像兩個小朋友在玩「一人畫一人鑑別」的遊戲，想像班上有兩個小朋友：
小華是「畫家」負責畫出圖片，小美是「評審」，負責鑑別圖片（但不會告訴小明需要修改的地方），經過數百次這樣的來回，
小華終於能畫出栩栩如生的貓咪，連小美都分不清是專業藝術家畫的，還是小華畫的。這就是GAN的基本原理——生成器（小華）和鑑別器（小美）在對抗中產生圖像。
而Stable Diffusio則像畫家拿著橡皮擦，把一張佈滿雜點的畫紙慢慢擦出清晰的圖案。
可能有以下原因，我想到的是，GAN生成圖片即便改良之後，能夠加入風格向量，
或者能夠讓畫面從簡單到精細，但如果進行某些「細節」的創作，鑑別器卻又不會給出明確的指示，應該很難掌控細節來進行生成。 

![thispersondoesnotexist W3](https://github.com/user-attachments/assets/d31ac184-5b0a-4d5e-8b00-2af23725df16)  

![W3 gan](https://github.com/user-attachments/assets/c6a5547f-0fb9-457b-90f0-66a8db1afadf)  

Gan生成的圖片身體軀幹似乎不太自然。
![W3 GAN2 身體軀幹不自然](https://github.com/user-attachments/assets/b0c9b53b-d26a-4c6c-b94c-9483febba163)  

---
## 作業4
題目: 建立自己的benchmarks  
連結：[W4 建立自己的Benchmark](https://github.com/PanpanMOA/113-2AI-Lesson/blob/main/W4%20%E5%BB%BA%E7%AB%8B%E8%87%AA%E5%B7%B1%E7%9A%84Benchmark)  
成果：大型語言模型輸出內容的比較成果，詳細內容請見Github筆記內容。

---
## 作業5
題目：用OpenAI API打造自己的對話機器人  
連結：[W6用Groq_API打造輔導老師式的同理回話機器人](https://colab.research.google.com/drive/1dzyHC2wVBurRVPxmgfed-oAhr879x9eB?usp=sharing)  

成果：  
![W6截圖-輔導老師的同理回話機器人](https://github.com/user-attachments/assets/1701234b-7204-411f-b403-ba3ce0ba9db7)  

---
## 作業6
題目：打造自己的對話機器人進階版-ollama  

連結：[W7用Ollama打造熱血對話機器人](https://colab.research.google.com/github/PanpanMOA/113-2AI-Lesson/blob/main/W7%20%E7%94%A8Ollama%E6%89%93%E9%80%A0%E7%86%B1%E8%A1%80%E5%B0%8D%E8%A9%B1%E6%A9%9F%E5%99%A8%E4%BA%BA_%E6%BD%98%E7%91%A9%E7%9C%9F.ipynb)

成果：  
![W7_ollama](https://github.com/user-attachments/assets/801122ee-4762-46aa-919d-60b64eba7cf0)  

![W7冒險王](https://github.com/user-attachments/assets/a35d05d7-a364-4ef4-a015-8410ed3537ea)  

---
## 作業7
題目：實作文獻檢索RAG系統  

連結：[W8文獻檢索RAG系統](https://colab.research.google.com/drive/1afI_55gVDUCCY3ql5wL7x8LO76pjTVzG?usp=sharing)

成果：  
![螢幕擷取畫面 2025-04-14 173925](https://github.com/user-attachments/assets/f1fea250-c72a-4b6b-bea9-f9f45318d352)  

![螢幕擷取畫面 2025-04-14 173911](https://github.com/user-attachments/assets/f169770d-e5cb-45cd-aec2-dc6d39922884)  

---
## 作業8
題目：實作planing AI agent  

連結：[W9-AI代理設計模式_輔導老師超同理對話生成器](https://colab.research.google.com/drive/1MoFMDqOSvnVFRj6slkBjOlqJwXhubQgt?usp=sharing)

成果：  ![螢幕擷取畫面 2025-05-14 170600](https://github.com/user-attachments/assets/8724d5e3-1824-48e7-bbd5-4dacc8f8c10f)  

![螢幕擷取畫面 2025-05-14 171140](https://github.com/user-attachments/assets/e4382d4a-e27e-4c2d-8fd1-17b95461a458)  

---
## 作業9
題目:利用Bing 進行文字生圖

連結：[W10 利用Bing 進行文字生圖-Diffusion modle.pdf](https://drive.google.com/file/d/1UFtuhkhdxLbL_wXKLJDXU-MJ_YI9cK7E/view?usp=sharing)

成果：完整內容請見雲端pdf檔案  

![螢幕擷取畫面 2025-05-14 171510](https://github.com/user-attachments/assets/0f07d8a4-735c-41d5-a4f0-61169b307db0)  

---


