# 🚀 **Formatify - Burp Suite Extension**  

**Formatify** is a **Burp Suite extension** that instantly converts HTTP requests into multiple formats, including cURL, Python, PowerShell, JavaScript, and more. Designed for **pentesters and developers**, Formatify streamlines request replication, payload crafting, and automation—eliminating the need for multiple extensions. With **seamless Burp Suite integration, a user-friendly interface, and one-click conversions**, Formatify saves time and enhances efficiency in security testing. 🚀

<p align="center">
  <img src="https://raw.githubusercontent.com/dr34mhacks/formatify/refs/heads/main/logo.svg" width="300">
</p>  

No more installing multiple extensions like:  
❌ *Copy as cURL*  
❌ *Copy as Python Request*  
❌ *Copy as PowerShell*  

🔥 **Formatify does it all in one place!**  

---

## ⚡ **Features**  

✅ **Convert HTTP requests to multiple formats:**  
- 🟢 **JavaScript Fetch**  
- 🟢 **cURL Command**  
- 🟢 **Python Requests**  
- 🟢 **Python aiohttp**  
- 🟢 **Node.js Axios**  
- 🟢 **Go HTTP**  
- 🟢 **PowerShell Invoke-WebRequest**  
- 🟢 **FFUF Command** (for fuzzing)  
- 🟢 **Java OkHttp**  
- 🟢 **CSRF Payload Builder**  
- 🟢 **CORS Exploit Proof of Concept**  

✅ **Seamlessly integrates** with Burp Suite **Intruder & Repeater**  
✅ **Context menu support** – Convert requests in **two clicks**  
✅ **Dedicated UI Tab** – Paste, convert, and copy request data easily  
✅ **Optimized for performance** – Runs in the background  

---

## 📥 **Installation**  

### **Prerequisites**  
- **Burp Suite** (Pro)  
- **Jython** environment setup  

### **Installing Formatify**  

1️⃣ Open **Burp Suite** → Go to **Extender** tab  
2️⃣ Click **Add** → Set **Extension Type** to `Python`  
3️⃣ Select the **formatify.py** file  
4️⃣ Click **Next** to load the extension  

✅ **Done!** Formatify is now installed and ready to use.  

---

## 🚀 **Usage**  

### **🔹 Using the Context Menu**  

1️⃣ In **Burp Suite's Repeater or Intruder**, right-click on a request  
2️⃣ Select **"Send to Formatify"** from the context menu  
3️⃣ The request will appear in the **Formatify** tab  
4️⃣ Choose a format from the dropdown  
5️⃣ Click **Formatify** to generate the converted request  

---

## ⏳ **Save Time & Boost Efficiency!**  

🔥 **Why install multiple Burp extensions when Formatify does it all?**  

✅ Convert **ANY** request format instantly  
✅ Automate **CORS PoCs** & **CSRF Payloads**  
✅ Speed up **fuzzing** with **FFUF Command Generation**  
✅ **Spend less time copying requests** and more time hacking!  

---

## 📌 **Example Conversions**  

### **🔹 Example HTTP Request**  
```
POST /search.php?test=query HTTP/1.1
Host: testphp.vulnweb.com
Content-Length: 31
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36

searchFor=formatify&goButton=go
```

### **🔹 Converted Output**  

#### **JavaScript Fetch**  

<img width="1259" alt="image" src="https://github.com/user-attachments/assets/42d1caa7-380e-4110-adb0-d5bb114e70ee" />


#### **Java OkHTTP**  

<img width="1259" alt="image" src="https://github.com/user-attachments/assets/79a126df-44b0-4372-bcd2-e073ca41fa01" />


#### **Python Requests**  

<img width="1259" alt="image" src="https://github.com/user-attachments/assets/28a50800-1476-4dd3-9dcd-01caea93193a" />


---

## 🛠️ **Development & Contribution**  

🚀 Want to improve Formatify? Fork the repo and submit a pull request!  

### **🔗 Clone the Repository**  
```sh
git clone https://github.com/dr34mhacks/formatify.git
cd formatify
```

---

## 📜 **License**  

🔓 **Formatify** is open-source and released under the **MIT License**.  

---

## 📝 **Acknowledgments**  

❤️ Special thanks to the **Burp Suite community** and all contributors!  

📧 Found a bug? **[Open an issue](https://github.com/dr34mhacks/formatify/issues)**  

---

## 📢 **Support & Feedback**  

💡 **Like this tool? Give it a ⭐ on GitHub!**  
🚀 **Follow me on [GitHub](https://github.com/dr34mhacks) for more tools!**  

---

### 🔔 **Stay Updated**  

📢 **Connect with me on** [LinkedIn](https://www.linkedin.com/in/sid-j0shi/)  

---

### **🚀 Formatify – The Only Burp Suite Request Converter You'll Ever Need!**  

### *Made with ❤️ by Sid*  
