# Cyber Security Internship Task – VPN (Psiphon Pro)

## 📌 Objective
The objective of this task is to understand the role of VPNs in protecting privacy and enabling secure communication by using **Psiphon Pro** to observe changes in IP address, browsing speed, and encryption.

---

## 🛠 Tools Used
- **VPN Client**: Psiphon Pro (Free Version)
- **Device**: <Your Device Name / OS Version>
- **Websites/Services**:  
  - [whatismyipaddress.com](https://whatismyipaddress.com) (IP check)  
  - [speedtest.net](https://www.speedtest.net) (Speed test)  
  - [ipleak.net](https://ipleak.net) (DNS/WebRTC leak test)

---

## 🔎 Steps Performed
1. Checked baseline IP address and browsing speed before enabling Psiphon.
2. Installed Psiphon Pro and connected to a VPN server.
3. Verified that the public IP address changed using **whatismyipaddress.com**.
4. Checked DNS/WebRTC leaks using **ipleak.net**.
5. Measured browsing speed while connected using **speedtest.net**.
6. Disconnected Psiphon and compared baseline vs VPN connection results.

---

## 📷 Screenshots
All screenshots are saved in the `screenshots/` folder:
- `before_ip.png` – IP before connecting  
- `after_ip.png` – IP after connecting  
- `speed_before.png` – Speed before VPN  
- `speed_after.png` – Speed with VPN  
- `after_ipleak.png` – DNS/WebRTC leak test  
- `after_disconnect_ip.png` – IP after disconnecting  

---

## 📊 Results Summary
- **IP before VPN**: `<Your Original IP>`  
- **IP after VPN**: `<VPN Server IP>`  
- **Speed before VPN**: Download `<X Mbps>`, Upload `<Y Mbps>`, Ping `<Z ms>`  
- **Speed after VPN**: Download `<X Mbps>`, Upload `<Y Mbps>`, Ping `<Z ms>`  
- **DNS Leak**: `<Yes/No>`  

---

## ✅ Benefits of VPN
- Hides public IP address and masks location.  
- Encrypts traffic for improved privacy.  
- Helps bypass censorship and geo-restrictions.  

---

## ⚠️ Limitations of Free VPN (Psiphon Pro)
- Limited server selection.  
- Slower browsing speed due to free-tier bandwidth limits.  
- May not fully prevent DNS/WebRTC leaks in all cases.  
- Trust depends on VPN provider’s logging policy.  

---

## 📌 Conclusion
Psiphon Pro successfully demonstrated how VPNs help in changing IP addresses and securing communication. While the browsing speed was slower, the VPN provided anonymity and encryption benefits. For stronger privacy needs, a premium or audited VPN service is recommended.

---


