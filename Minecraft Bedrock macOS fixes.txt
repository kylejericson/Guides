# Minecraft Bedrock fixes for macOS

### Step 1
Download the Nightly build from here:  
👉 [Nightly builds on GitHub](https://github.com/minecraft-linux/macos-builder/releases)

---

### Step 2
Open the launcher one time, then close it.

---

### Step 3

Download this file and change this to your username:
Line 16: {kyle} replace with your mac username
dataDir=/Users/kyle/Library/Application Support/mcpelauncher
Copy this file to the following location: 
📄 [profiles.ini (download link)](https://raw.githubusercontent.com/kylejericson/Guides/main/profiles.ini)

**Destination:**  
`/Users/{your-mac-username}/Library/Application Support/mcpelauncher/profiles`

---

### Step 4
Open the Launcher in dev mode and check these settings:

**Dev Settings:**
![Dev Settings Screenshot](https://raw.githubusercontent.com/kylejericson/Guides/main/dev.png)

**Profile Settings:**
![Profile Settings Screenshot](https://raw.githubusercontent.com/kylejericson/Guides/main/profile.png)

---

### Step 5
Launch Minecraft.

---

**Note:** I’ve had the best results always running the launcher in dev mode.

You can create a simple script to do that:

```bash
#!/bin/bash
open -a "/Applications/Minecraft Bedrock Launcher.app" --args -d
exit 0
