# Upload Domain Intel

A community-maintained list of known **file upload** and **file sharing** domains used by popular applications, messaging platforms, and cloud services.

This list is useful for:

- Threat detection & exfiltration monitoring  
- Data Loss Prevention (DLP) rules  
- Proxy allow/block lists  
- Application fingerprinting and network traffic analysis  

---

## 📦 Format

The data is organized in a simple, extendable YAML format.  
Each entry includes:

- **App Name**  
- **Known upload domains**  
- *(Optional)* Notes on usage or reverse engineering

```yaml
- app: Zalo
  domains:
    - tt-files-wpa.chat.zalo.me

- app: Telegram
  domains:
    - api.telegram.org

- app: Discord
  domains:
    - cdn.discordapp.com
    - media.discordapp.net
```


## 💡 Contributing
We welcome contributions!

If you know of upload/file transfer domains used by any software, feel free to open a Pull Request or submit an Issue.

