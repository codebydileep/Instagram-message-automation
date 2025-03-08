# 🚀 Instagram Auto Messenger Bot  

### 📌 Automate Your Instagram Messaging with Selenium  

Tired of manually sending messages on Instagram? This bot does it for you! It reads profile links from a CSV file and sends randomized messages while incorporating smart delays to avoid bot detection.  

---

## 🎯 Features  

✅ **Automated Login** – Logs into Instagram using provided credentials.  
✅ **Bulk Messaging** – Sends messages to multiple Instagram profiles.  
✅ **Randomized Messages** – Selects messages at random to personalize outreach.  
✅ **Anti-Bot Protection** – Implements delays and message limits to avoid detection.  
✅ **CSV Status Tracking** – Logs sent messages and failed attempts in a CSV file.  

---

## 🔧 Prerequisites  

Ensure you have the following installed:  

- **Python 3.x**  
- **Google Chrome**  
- **ChromeDriver** (managed automatically by `webdriver-manager`)  

Install dependencies using:  

```sh
pip install selenium webdriver-manager pandas
```

---

## 📂 Project Structure  

```
📦 Instagram Auto Messenger  
 ┣ 📜 Instagram.py             # Main script  
 ┣ 📜 profile_link.csv         # List of Instagram profile links  
 ┣ 📜 Profile_links_updated.csv # Status log of sent messages  
 ┗ 📜 README.md                # Project documentation  
```

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  

```sh
git clone https://github.com/codebydileep/Instagram-Auto-Messenger.git
cd Instagram-Auto-Messenger
```

### 2️⃣ Update Credentials  
   - Modify `username` and `password` in `Instagram.py`.  
   - ⚠️ _Use a secondary account to avoid bans._  

### 3️⃣ Prepare Profile Links  
   - Add Instagram profile links in `profile_link.csv`.  
   - Ensure they are in a single-column format.  

### 4️⃣ Run the Script  

```sh
python Instagram.py
```

### 5️⃣ Monitor Status  
   - The script logs successful and failed messages in `Profile_links_updated.csv`.  

---

## 🔄 Customization  

- **Modify Messages** – Update the `messages` list in the script to change the texts.  
- **Adjust Bot Behavior** – Tweak `max_messages` and `time_interval` to manage sending limits.  
- **Error Handling** – The script logs failed attempts to help you troubleshoot issues.  

---

## ⚠️ Disclaimer  

- ❗ This script is for educational purposes only.  
- 🚨 **Use responsibly** and comply with Instagram's policies.  
- 🔒 Avoid using your main account to prevent restrictions.  

---

## 📜 License  

This project is open-source and provided "as-is" for learning purposes. Use it at your own risk.  
 


