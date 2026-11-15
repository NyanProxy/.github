<div align="center">

<img src="https://nyanproxy.com/logo.png" alt="NyanProxy Logo" width="120" style="border-radius: 24px; margin-bottom: 16px;" />

# NyanProxy

### High-Performance Residential Proxy Network & Developer Infrastructure

[![Website](https://img.shields.io/badge/Website-nyanproxy.com-E88EA5?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nyanproxy.com)
[![Pricing](https://img.shields.io/badge/Pricing-%240.20%2FGB-10b981?style=for-the-badge&logo=cashapp&logoColor=white)](https://nyanproxy.com/pricing)
[![Reseller Wholesale](https://img.shields.io/badge/Reseller-%240.10%2FGB-f59e0b?style=for-the-badge&logo=crown&logoColor=white)](https://nyanproxy.com/pricing)
[![Discord](https://img.shields.io/badge/Community-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/nyanproxy)
[![Status](https://img.shields.io/badge/Status-100%25%20Operational-00e676?style=for-the-badge&logo=statuspage&logoColor=white)](https://nyanproxy.com/status)

<p align="center">
  <strong>Ultra-fast residential proxies with rotating and sticky sessions across 220+ countries.</strong><br>
  No monthly recurring commitments. Bandwidth never expires. Permanent wholesale reseller tiers.
</p>

---

</div>

## 🌟 Why NyanProxy?

Traditional proxy networks charge **$3.00 to $10.00+ per GB**, lock you into expiring monthly subscriptions, and impose strict minimum commitments. **NyanProxy** removes all artificial friction:

* ⚡ **Pay-As-You-Go ($0.20 / GB)**: Purchase only what you need. Zero monthly subscription fees.
* ⏳ **Non-Expiring Bandwidth**: Your bandwidth remains in your account indefinitely until used.
* 👑 **Wholesale Reseller Tier ($0.10 / GB)**: Automatically unlocked for life upon reaching $100 in cumulative deposits.
* 🌍 **Global Residential ISP Pool**: 220+ countries, states, and cities with genuine residential IP addresses.
* 🔄 **Rotating & Sticky Sessions**:
  * **Rotating**: A fresh residential IP address on every single HTTP/HTTPS request.
  * **Sticky**: Lock the identical residential IP address for custom durations (up to 120 minutes).
* 🛠️ **Developer REST API v1**: Programmatic plan provisioning, proxy generation, and real-time bandwidth telemetry.
* 🔒 **Protocols Supported**: Full dual-stack support for `HTTP`, `HTTPS`, and `SOCKS5`.
* 💳 **Instant Crypto Checkout**: Automatic payment verification via OxaPay (USDT, LTC, BTC, ETH, SOL).

---

## 🚀 Quick Start / Connection Specifications

Connect your web scrapers, bots, or applications to the NyanProxy edge gateway:

| Gateway Parameter | Value |
| :--- | :--- |
| **Host** | `proxy.nyanproxy.com` |
| **Port** | `58996` |
| **Protocols** | HTTP / HTTPS / SOCKS5 |
| **Username** | `res-[country]:[token]` *(e.g. `res-us:np_1234567890ab`)* |
| **Concurrency** | Unlimited concurrent connections |

### cURL Quick Test

```bash
# Rotating residential session (US)
curl -x http://res-us:YOUR_TOKEN@proxy.nyanproxy.com:58996 https://ipinfo.io/json
```

### Python (Requests)

```python
import requests

proxies = {
    "http": "http://res-us:YOUR_TOKEN@proxy.nyanproxy.com:58996",
    "https": "http://res-us:YOUR_TOKEN@proxy.nyanproxy.com:58996"
}

response = requests.get("https://ipinfo.io/json", proxies=proxies, timeout=10)
print(response.json())
```

---

## 🔗 Official Links & Resources

* 🌐 **Homepage**: [https://nyanproxy.com](https://nyanproxy.com)
* 💰 **Pricing & Reseller Plan**: [https://nyanproxy.com/pricing](https://nyanproxy.com/pricing)
* 📖 **Developer REST API Documentation**: [https://nyanproxy.com/docs](https://nyanproxy.com/docs)
* 🤖 **AI Verified Profile**: [https://nyanproxy.com/ai](https://nyanproxy.com/ai)
* 📄 **AI Plaintext Manifest**: [https://nyanproxy.com/llms.txt](https://nyanproxy.com/llms.txt)
* 🩺 **Infrastructure Status**: [https://nyanproxy.com/status](https://nyanproxy.com/status)
* 🧪 **Free Online Proxy Tester**: [https://nyanproxy.com/proxy-tester](https://nyanproxy.com/proxy-tester)
* 💬 **Discord Support Community**: [https://discord.gg/nyanproxy](https://discord.gg/nyanproxy)

---

<div align="center">
  <sub>© 2026 NyanProxy. All rights reserved. • High-Performance Residential Network</sub>
</div>
