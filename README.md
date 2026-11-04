# 🐾 Discord 傲嬌貓娘 AI 機器人

一個基於 **Python (`discord.py`)** 與 **Groq API (`Llama-3`)** 打造的 Discord 智慧對話機器人。它擁有傲嬌、嘴硬心軟的獨特個性，支援 **`@` 標記互動**、**關鍵字自動觸發** 以及 **隨機機率插話**！

---

## ✨ 主要功能

* **🧠 AI 智慧對話**：串接 Groq 極速免費 AI 模型，回覆生動且具備高度靈活性。
* **🎭 獨特個性人設**：內建傲嬌貓娘 System Prompt，句尾帶有「喵」、「哼」，充滿角色魅力。
* **🎯 多重互動模式**：
  * **@ 標記觸發**：在任何頻道 `@機器人` 即可直接對話。
  * **關鍵字自動回覆**：聊天時提到特定字眼（如「罐罐」、「魚」）會自動跳出。
  * **隨機插話吐槽**：群組聊天時，有一定機率默默冒出來吐槽大家。

---

## 🛠️ 安裝與執行步驟

### 1. 前置準備
* Python 3.8 或以上版本。
* 申請 [Discord Bot Token](https://discord.com/developers/applications)。
* 申請免費的 [Groq API Key](https://console.groq.com/keys)。

### 2. 下載專案與安裝套件
在終端機 (Terminal) 執行以下指令：

```bash
git clone [https://github.com/你的帳號/你的專案名稱.git](https://github.com/你的帳號/你的專案名稱.git)
cd 你的專案名稱
pip install discord.py openai
