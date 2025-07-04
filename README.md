# generative_ai
- 姓名：謝宇宸
- 系級：資工 115
- 課程名稱：生成式AI：文字與圖像生成的原理與實務_國立臺灣師範大學衛星課程
- 修課學期：113-2
  
# 作業說明
### hw1
- 用函式畫出一個螺旋圖
- 隨著Ｘ座標的不同，圖片會有不同顏色
- google colab連結：https://colab.research.google.com/drive/1BMq2HY2L0soHGCISzT7V7QVK8jvJVE1J?usp=sharing

### hw2 
- 使用全連結來訓練模型用於辨識手寫數字
- 總共有四層，神經元分別為N1 = 160，N2 = 320，N3 = 640，N4 = 1280
- 過程穿插dropout避免overfitting
- 優化器選擇adam，損失函數選擇categorical_crossentropy
- batch_size=80, epochs=15
- 最後使用gradio來與使用者互動
- google colab連結：https://colab.research.google.com/drive/1aLDgllk-VXqwW-iSwI_61HyGaAp-GAP8?usp=sharing

### hw3
- 選擇主題一來完成作業
- 使用GAN與diffusion的方式用同一個prompt產出五組圖片進行比較
- 比較為什麼現在較沒有人在使用GAN來生圖？

### hw4
- 比較Gemini與Chatgpt差別
- 用同一個prompt讓兩個模型回答
- prompt「我是新手，我想學寫 C語言，你會怎麼建議我入門？」

### hw5
- 設計一個專門罵人的《理性爆罵機》，針對對方的問題嚴肅的痛罵一頓，但不會說髒話，在罵人的過程中也會給一些改進的方向。
- google colab連結：https://colab.research.google.com/drive/19uXG62lrHvg_Bez-6s8n567sDsqbrWs_?usp=sharing

### hw6
- 選擇主題一來完成作業
- 延續hw5的內容設計一個可以持續對話的機器人
- 使用gemma3的12b版本
- google colab連結：https://colab.research.google.com/drive/1gBcWgX5fnTTtPQ0KdRuDf9QjZDzO6aP5?usp=sharing

### hw7
- 使用12年課綱的pdf檔來當作rag資料庫的訓練資料
- 用rag的方式讓大型語言模型學習並回答
- google colab連結：https://colab.research.google.com/drive/1BPdMgwMJpag-obswkvT6rGb_8kpfjUdJ?usp=sharing

### hw8
- 用CoT的方式延續hw5的主題完成ai回應
- 先生成五種大綱，再從中挑選最適合的完成回應
- google colab連結：https://colab.research.google.com/drive/1opmkF-qTfMTBMG3P7OEDbklLIHqFBedA?usp=sharing

### hw9
- 試用diffussion model產出自訂風格的圖片
- 選用進擊的巨人風格

### hw10
- 選用"stablediffusionapi/sdvn5-3dcutewave"製作可愛3D角色生成器
- 用groq將使用者輸入翻譯成英文
- 反覆試驗找出適合的 default_enhance prompt 和 default_negative prompt
- google colab連結：https://colab.research.google.com/drive/1N8cUlSGF03eaabDEediAUg8ckLqqKfef?usp=sharing

### hw11
- 用fooocus產出不同風格和目的的圖片

### hw12
- 透過 Gradio 介面，整合 Google Maps API 與 Gemma-7B-it 大型語言模型，實現對餐廳評論的即時 AI 摘要功能。

### hw13（期末專案）
- 本專案是一個 AI 驅動的餐廳評論分析工具，旨在幫助使用者快速了解位於台北市大安區的餐廳口碑。
- 透過串接 Google Maps API 獲取即時顧客評論，並利用 Gemma-7B 大型語言模型生成精簡的摘要。
- 所有功能均整合在一個以 Gradio 建構、易于操作的 Web 介面中呈現。
- google colab連結：https://colab.research.google.com/drive/13CdvIF_CQENOvxDfOC7MS5e-wo0_MPU0?usp=sharing

### project
- 本專案是一個 AI 驅動的餐廳評論分析工具，旨在幫助使用者快速了解位於台北市大安區的餐廳口碑。
- 透過串接 Google Maps API 獲取即時顧客評論，並利用 Gemma-7B 大型語言模型生成精簡的摘要。
- 所有功能均整合在一個以 Gradio 建構、易于操作的 Web 介面中呈現。
- google colab連結：https://colab.research.google.com/drive/13CdvIF_CQENOvxDfOC7MS5e-wo0_MPU0?usp=sharing

