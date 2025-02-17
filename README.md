# CanaryTokens: Detecting Unauthorized Access with Decoy Files

Security is all about staying ahead of attackers, and sometimes the best way to catch them is by setting a trap. This project showcases how to use **CanaryTokens** lightweight honeypots that silently alert you when accessed. Think of them like invisible tripwires: when someone steps on them, you get an instant notification.

---

## **🔍 How It Works**
A **CanaryToken** is a stealthy tracking mechanism embedded in a file. The moment someone **opens or edits** it, the token silently **phones home**, capturing:

- **IP Address** of the person accessing it  
- **Timestamp** of the event  
- **User-Agent** (device/software details)  
- **Geolocation Data** (if available)  

<img src="https://github.com/user-attachments/assets/df2a4683-769b-458d-aa7f-d3e6c7acf8f3" width="600">

No malware. No complex setups. Just **pure deception** that lets attackers reveal themselves.

---

## **🎭 Setting Up the Decoy**

### **1️⃣ Generating the CanaryToken**  
I created a **Microsoft Word CanaryToken** through the CanaryTokens generator. The process was straightforward:

- Enter an **email address** to receive alerts  
- Optionally add a **reminder note** for tracking  
- Download the **booby-trapped Word document**  

<img src="https://github.com/user-attachments/assets/ce3d911c-85de-41b6-a300-c75d1ab75f54" width="600">

This document was then **strategically placed** a shared drive, a cloud folder, or anywhere someone might be tempted to open it.

---

### **2️⃣ Triggering the Alert**  
Once the **decoy file** was opened or edited, the CanaryToken **silently triggered an alert** no pop-ups, no warnings, just **a signal straight to my inbox** with all the details:

- **Time of access**  
- **Source IP address**  
- **Location (if available)**  
- **User-Agent (e.g., Windows, macOS, Office version, etc.)**  

<img src="https://github.com/user-attachments/assets/e59c7976-8b5d-40de-bf1f-78aa2d9dab35" width="600">

This provides **real-time evidence** of unauthorized access, making it easier to spot security threats before they escalate.

---

## **✅ Why This Method Works**
- **Attackers don’t think twice** about opening a juicy-looking file.  
- Unlike logs that might get wiped, this method **sends an external alert** before an attacker can cover their tracks.  
- It requires **almost no setup** just generate, download, and place the file where it’ll get attention.  

<img src="https://github.com/user-attachments/assets/9dc939a6-1829-4f09-848e-289e433ca452" width="600">

Even the most cautious intruder **exposes themselves** the moment they interact with the file.

---

## **🔥 Use Cases**
- **Detecting Insider Threats** – Deploy fake sensitive files in shared directories to catch unauthorized access.  
- **Monitoring Breach Indicators** – Plant decoy credentials in compromised environments.  
- **Early Warning System** – Detect potential security incidents **before they escalate**.  

Instead of waiting to react to an attack, this approach **proactively exposes threats**, putting defenders one step ahead.
