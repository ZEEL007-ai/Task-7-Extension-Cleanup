# 🚨 Task 7 - Suspicious Browser Extensions Cleanup (Brave)

## 🧠 Objective:
To identify and remove potentially harmful browser extensions, increasing awareness of browser security risks.

## 🔧 Browser Used:
**Brave Browser** (Chromium-based)

## 🛠 Tools:
- Brave Extension Manager (`brave://extensions`)
- Screenshot Tool
- Manual permission inspection

---

## 🔍 Installed Extensions Reviewed:

| Extension Name         | Status        | Action         | Reason                                                    |
|------------------------|---------------|----------------|-----------------------------------------------------------|
| Adobe Acrobat          | ✅ Safe        | Kept           | Trusted PDF tool from Adobe                               |
| Dark Mode              | ⚠️ Unnecessary | Kept (Optional)| Only cosmetic; no major threat                            |
| Grammarly              | ⚠️ Caution     | Kept           | Accesses input fields — caution advised                   |
| **Hola VPN**           | 🚫 Suspicious  | ❌ Removed      | Known for privacy violations, data tracking               |
| **Online PDF Converter**| 🚫 Suspicious | ❌ Removed      | Unknown publisher; requested file system permissions      |
| **WebCRX**             | ⚠️ Risky       | ❌ Removed      | Allows local CRX installs — risk of unverified extensions |


---

## 🧠 Key Learnings:
- Always check extension permissions and source before installing.
- Even cosmetic or useful tools like VPNs may pose major risks.
- Regularly audit browser extensions for privacy and performance.
- Brave has similar extension risks as Chrome.

---

> ⚠️ Disclaimer: All suspicious extensions were temporarily installed or already present and were removed immediately after analysis. This task was completed purely for cybersecurity learning and reporting.
