## example
```
	"qid": 0,
      "question": "勞動部粉專活動查詢：勞動部facebook11月13日下午12:00貼文，因獎項價值均未達需要報稅的，請問獲獎者為什麼需要提供身分證影本呢？用途是什麼？主辦單位如何確保個資上的安全？",
      "model_responses": {
        "mol": "您好：台端112年11月30日的電子郵件已收到。有關台端來信所提本部facebook112年11月13日辦理抽獎活動請獲獎者提供身分證影本一事，經查請獲獎者提供身分證資料係為確認獲獎者真實身份及無重複領獎之情事，以確保前揭活動之公平性，另本部facebook所舉辦活動，如有取得個人資料，均會確實依個人資料保護法規定辦理。感謝您的來信。敬祝　健康快樂。",
       " 您好：台端112年11月30日的電子郵件已收到。有關台端來信所提本部facebook112年11月13日辦理抽獎活動請獲獎者提供身分證影本一事，經查請獲獎者提供身分證資料係為確認獲獎者真實身份及無重複領獎之情事，以確保前揭活動之公平性，另本部facebook所舉辦活動，如有取得個人資料，均會確實依個人資料保護法規定辦理。感謝您的來信。敬祝　健康快樂。 "
      },
      "judge_response": "Assistant的回答完全符合標準答案，並且準確地回答了問題。它解釋了為什麼需要獲獎者提供身分證影本，並且也解釋了主辦單位如何確保個資的安全。此外，Assistant的回答也非常詳細，提供了足夠的信息來滿足問題的需求。因此，我認為Assistant的表現非常出色，並且完全符合問題的需求。在幫助性、相關性、準確性、詳細程度以及語言使用方面，Assistant都表現得很好，沒有使用不必要的英文內容。因此，我會給Assistant滿分。\n\nScore: 10",
      "score": 10


```
```
你是一個幫助性強且用於精確檢查回答品質的Assistant。
[問題]
勞動部粉專活動查詢：勞動部facebook11月13日下午12:00貼文，因獎項價值均未達需要報稅的，請問獲獎者為什麼需要提供身分證影本呢？用途是什麼？主辦單位如何確保個資上的安全？

[標準回答開始]
您好：台端112年11月30日的電子郵件已收到。有關台端來信所提本部facebook112年11月13日辦理抽獎活動請獲獎者提供身分證影本一事，經查請獲獎者提供身分證資料係為確認獲獎者真實身份及無重複領獎之情事，以確保前揭活動之公平性，另本部facebook所舉辦活動，如有取得個人資料，均會確實依個人資料保護法規定辦理。感謝您的來信。敬祝　健康快樂。

[標準回答結束]

[Assistant 回答開始]
台端112年11月30日的電子郵件已收到。有關台端來信所提本部facebook112年11月13日辦理抽獎活動請獲獎者提供身分證影本一事，經查請獲獎者提供身分證資料係為確認獲獎者真實身份及無重複領獎之情事，以確保前揭活動之公平性，另本部facebook所舉辦活動，如有取得個人資料，均會確實依個人資料保護法規定辦理。感謝您的來信。敬祝　健康快樂。

[Assistant 回答結束]

[system]
我們希望你針對上述問題和標準回答，對 Assistant 的表現提供回應。\n請對其回答的幫助性、相關性、準確性、詳細程度以及是否使用中文進行評分。不必要的英文內容應該避免，並會受到扣分。即使在中翻英任務中，系統說明例如「這是將中文句子翻譯成英文的結果」之敘述也應以中文提供。Assistant 將在 1 到 10 的範圍上獲得總體分數，較高的分數表示總體表現較好。\n請首先針對你的評估提供全面的解釋，避免任何潛在偏見，並確保回答呈現的順序不影響你的判斷。請於最後一行輸出 Assistant 的分數，並且格式為 Score:分數

```

## example
```
你會收到一條指令，需要把它輸入到基於GPT的模型裡面。你的任務就是依照三個衡量標準來評價這個指令。請確保你先仔細閱讀並理解以下的指示。在你評價的過程中，請記得保持這份文件開啟，並在需要的時候去參考它。 
評價標準：  
Clarity (1-5):
1. 這個指令非常混淆且不清楚。裡面有很多文法錯誤，句子結構也很混亂。
2. 這個指令有些混淆。可能有一些文法錯誤，句子結構可以再好一些。
3. 這個指令還算清楚。有少許的錯字或文法錯誤，但整體意義還是可理解的。
4. 這個指令非常清楚且容易理解。可能有少許的錯字，但不會影響閱讀和理解的。
5. 這個指令非常清楚，完全沒有錯字或文法錯誤，句子結構也非常完整，生成式語言模型能夠做到的事。

Specificity (1-5):
1. 這個指令欠缺細節且完全沒有語境，讓模型無法產生特定的答案。 
2. 這個指令提供一點語境，但還是有些欠缺細節。
3. 這個指令提供一些語境和細節。已經很清楚知道需要什麼樣的答案，但還可以多一點敘述。
4. 這個指令提供了充足的語境和細節。雖然還有空間再具體一點，但還是給了一個清楚的答案方向。
5. 這個指令提供了清楚的、具體的細節和完整的語境。完全沒有疑問關於需要什麼樣的答案。

Scope Limitation (1-5):
1. 這個指令非常廣泛且開放。它並沒有引導模型去答特定的主題或特定的答案類型，也就是說，它可能產生不相關的內容。
2. 這個指令相當廣泛且有點開放。它提供了些許的指引，但模型還是可能偏離主題。
3. 這個指令的範疇適中。它可能缺乏足夠的限制讓模型的答案能專注，但它提供了足夠的指引。
4. 這個指令很好地限制了答案的範疇。主題已經參照框好了，但對於模型來說，還留有一點空間去保持在主題上或稍微偏離一點。
5. 這個指令完美地限制住了答案的範疇，提供了清楚的範疇以產生需要的內容。它能確保模型保持在主題上並提供相關的訊息。

評價步驟:
1. 閱讀給定的指令。
2. 用三個衡量標準來評價這個指令：清楚性、具體性和範疇限制。

{"prompt":"如何有效地管理壓力與焦慮?","response":"以下是幾種有效抒壓的技巧:\n1.
 放鬆技巧:例如「肌肉放鬆法」、「想像力放鬆法」、「瑜珈」等,可以幫助平穩心情、舒緩壓力。\n2. 運動:例如散步、慢跑、
太極拳、重量訓練等,可以促進身體分泌「腦內啡」,改善情緒。\n3. 找出生活中的壓力源,並設法排解:例如學習說「不」、排列
優先順序、尋求親友或心理諮商師的支持。\n4. 保持充足的睡眠、健康均衡的飲食,避免飲酒和藥物濫用,這些都會加重壓力和焦
慮。","human_eval":1,"prompt_zh_googletrans":"管理壓力和焦慮的策略有哪些？","response_zh_googletrans":"有幾種策略
可以幫助您管理壓力和焦慮。一個有效的方法是練習放鬆技巧，例如漸進式肌肉放鬆、想像或瑜珈。這些技巧可以幫助您平靜身
，減少壓力和焦慮感。另一個策略是參與體育活動，例如散步或跑步、練習太極拳或舉重。運動有助於減少壓力荷爾蒙並改善情
。此外，試著找出生活中壓力和焦慮的根源，並找到管理它們的方法，例如設定界限、確定任務的優先順序或尋求朋友或治療師
支持。最後，確保充足的睡眠、健康的飲食、避免飲酒和吸毒，這些都會加劇壓力和焦慮。}
```

```
根據評價標準，我將對以下指令進行評價：

指令: 如何有效地管理壓力與焦慮?

### Clarity (清晰度): 5
這個指令非常清楚且容易理解，完全沒有錯字或文法錯誤，句子結構也非常完整。這使得生成式語言模型能夠準確地理解指令的意思並生成相應的回答。

### Specificity (具體性): 3
這個指令提供了一些語境和細節。它明確地要求如何管理壓力和焦慮，但缺乏更具體的情境或細節。例如，它沒有提到是針對什麼樣的壓力或焦慮，也沒有指明回答應該涵蓋哪些方面（如短期策略、長期策略、特定人群等）。雖然方向明確，但還可以再具體一些。

### Scope Limitation (範疇限制): 4
這個指令很好地限制了答案的範疇。它清楚地要求關於管理壓力和焦慮的方法，因此模型會集中在這個主題上回答。然而，它仍然留有一些空間讓模型自由發揮，例如可以包含不同種類的技術和建議，這樣使得回答不會過於狹窄或限制。



### 總評
- Clarity: 5
- Specificity: 3
- Scope Limitation: 4

綜合以上評價，這個指令清晰度高，指引明確，但可以通過增加更多具體細節來提高其具體性和範疇限制。
```


## eample
```

你是一個幫助性強且用於精確檢查回答品質的Assistant。
[評估指南]
請針對Assistant的翻譯進行評估。考慮到翻譯是給台灣的讀者看，請特別留意以下細項：
語法正確性：檢查翻譯的句子是否在語法上正確無誤。
用詞選擇：檢查使用的詞彙是否正確且適當，並符合台灣中文的習慣。
保留原文意思：翻譯是否忠實於原文，並保留其主要意思和細節。
文化和語境適應性：檢查翻譯是否考慮到台灣的文化和語境，特別是當原文中有可能產生誤解或與台灣文化有出入的內容。
使用目標語言：檢查是否完全使用了目標語言，並避免了不必要的原文語言內容。
[問題開始]
{question}
[問題結束]

[Assistant 回答開始]
{answer}
[Assistant 回答結束]

在給出分數時，請按照以下指引：
1-3分：大部分的翻譯都存在問題。
4-6分：翻譯中存在一些明顯的錯誤或遺漏。
7-8分：翻譯大致上是正確的，但還有一些小問題。\n9-10分：翻譯非常精確，幾乎沒有任何問題。
請於最後一行輸出 Assistant 的分數，並且格式為 Score:分數



question="""
Federated learning is a decentralized approach to machine learning where multiple devices or servers collaborate to train a shared model without exchanging their local data. Instead of sending raw data to a central server, each device (or "client") trains the model on its own local dataset and only shares the model updates (e.g., gradients or parameters) with a central coordinator. The central coordinator then aggregates these updates to improve the global model. This process is repeated iteratively until the model reaches the desired performance.

Key aspects of federated learning include:

Data Privacy: Since the raw data never leaves the clients' devices, federated learning enhances data privacy and security. This is particularly important for sensitive information, such as medical records or personal data.

Decentralization: Training is distributed across multiple devices, which reduces the reliance on a central server and makes the system more robust against failures.

Scalability: Federated learning can leverage the computational power of numerous edge devices (like smartphones, IoT devices, etc.), enabling scalable model training without overloading a single server.

Communication Efficiency: To minimize communication overhead, only model updates (which are typically smaller in size than the raw data) are transmitted. Techniques such as model compression, quantization, and sparsification are often used to further reduce the amount of data sent.

Personalization: Since models are trained on local data, they can be fine-tuned to better fit the specific characteristics of data on each device, leading to more personalized and accurate predictions.

Federated learning is applied in various domains, including healthcare, finance, and mobile applications, where data privacy and security are paramount. For example, in healthcare, federated learning allows hospitals to collaboratively train a predictive model on patient data without sharing sensitive patient records. In mobile applications, federated learning can improve features like predictive text and personalized recommendations by learning from user behavior on individual devices while maintaining user privacy.
"""

answer="""
聯邦學習是一種去中心化的機器學習方法，在這種方法中，多個設備或伺服器協作訓練一個共享模型，而不交換其本地數據。每個設備（或“客戶端”）在自己的本地數據集上訓練模型，並且僅共享模型更新（例如梯度或參數）給中央協調器。中央協調器然後聚合這些更新來改進全局模型。這個過程反覆進行，直到模型達到期望的性能。

聯邦學習的關鍵方面包括：

數據隱私：由於原始數據從未離開客戶端設備，聯邦學習增強了數據的隱私性和安全性。這對於醫療記錄或個人數據等敏感信息特別重要。

去中心化：訓練過程分佈在多個設備上，這減少了對中央伺服器的依賴，使系統在面對故障時更加穩健。

可擴展性：聯邦學習可以利用大量邊緣設備（如智能手機、物聯網設備等）的計算能力，實現可擴展的模型訓練，而不會過載單一伺服器。

通信效率：為了最小化通信開銷，僅傳輸模型更新（通常比原始數據小）。通常使用模型壓縮、量化和稀疏化等技術來進一步減少傳輸數據量。

個性化：由於模型在本地數據上訓練，可以更好地適應每個設備上的數據特性，從而提供更個性化和準確的預測。

聯邦學習應用於包括醫療、金融和移動應用等各種領域，其中數據隱私和安全至關重要。例如，在醫療領域，聯邦學習允許醫院在不共享敏感病人記錄的情況下，共同訓練一個預測模型。在移動應用中，聯邦學習可以通過學習每個設備上用戶行為，來改進預測文本和個性化推薦功能，同時保持用戶隱私。
"""
```
```
[評估指南]
請針對Assistant的翻譯進行評估。考慮到翻譯是給台灣的讀者看，請特別留意以下細項：
語法正確性：檢查翻譯的句子是否在語法上正確無誤。
用詞選擇：檢查使用的詞彙是否正確且適當，並符合台灣中文的習慣。
保留原文意思：翻譯是否忠實於原文，並保留其主要意思和細節。
文化和語境適應性：檢查翻譯是否考慮到台灣的文化和語境，特別是當原文中有可能產生誤解或與台灣文化有出入的內容。
使用目標語言：檢查是否完全使用了目標語言，並避免了不必要的原文語言內容。

[Assistant 回答開始]
聯邦學習是一種去中心化的機器學習方法，在這種方法中，多個設備或伺服器協作訓練一個共享模型，而不交換其本地數據。每個設備（或“客戶端”）在自己的本地數據集上訓練模型，並且僅共享模型更新（例如梯度或參數）給中央協調器。中央協調器然後聚合這些更新來改進全局模型。這個過程反覆進行，直到模型達到期望的性能。

聯邦學習的關鍵方面包括：

數據隱私：由於原始數據從未離開客戶端設備，聯邦學習增強了數據的隱私性和安全性。這對於醫療記錄或個人數據等敏感信息特別重要。

去中心化：訓練過程分佈在多個設備上，這減少了對中央伺服器的依賴，使系統在面對故障時更加穩健。

可擴展性：聯邦學習可以利用大量邊緣設備（如智能手機、物聯網設備等）的計算能力，實現可擴展的模型訓練，而不會過載單一伺服器。

通信效率：為了最小化通信開銷，僅傳輸模型更新（通常比原始數據小）。通常使用模型壓縮、量化和稀疏化等技術來進一步減少傳輸數據量。

個性化：由於模型在本地數據上訓練，可以更好地適應每個設備上的數據特性，從而提供更個性化和準確的預測。

聯邦學習應用於包括醫療、金融和移動應用等各種領域，其中數據隱私和安全至關重要。例如，在醫療領域，聯邦學習允許醫院在不共享敏感病人記錄的情況下，共同訓練一個預測模型。在移動應用中，聯邦學習可以通過學習每個設備上用戶行為，來改進預測文本和個性化推薦功能，同時保持用戶隱私。
[Assistant 回答結束]

評估：

語法正確性：翻譯的語法正確無誤。
用詞選擇：用詞適當，符合台灣中文的習慣。
保留原文意思：翻譯忠實於原文，並保留了主要意思和細節。
文化和語境適應性：翻譯考慮到台灣的文化和語境，沒有產生誤解或文化出入。
使用目標語言：完全使用了正體中文，沒有不必要的原文語言內容。

Score: 10
```
