# CoreKit

**CoreKit** is a modular CLI tool for iOS and Android apps.  
It allows you to **install, uninstall, update, repair and reset features** in your mobile project with simple commands.

Think of it as a **feature manager** for your app: Auth, Account, Photos, Messaging, Notifications… ready to plug in.

---

## ✨ Features

- 📦 **Modular architecture**: add/remove features on demand  
- ⚡ **Cross-platform**: iOS (Swift) & Android (Kotlin/Java) support  
- 🛠️ **CLI powered**: manage features with commands  
- 🔄 **Two-level structure**:
  - `generated/` → auto-generated code (DO NOT EDIT)  
  - `templates/` → customizable templates you can tweak  

Example usage:

```bash
corekit install auth
corekit install photos
corekit uninstall messaging
corekit update
corekit reset
