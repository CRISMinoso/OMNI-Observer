
# OMNI Observer 🎮🎥

**OMNI Observer** is an intelligent, automated spectator camera controller for **Counter-Strike 2 (CS2)**. Designed for streamers, tournament observers, and content creators, the application uses real-time Game State Integration (GSI) telemetry and Half-Life Advanced Effects (HLAE) integration to deliver professional-grade broadcast quality.

<img width="1918" height="1008" alt="print" src="https://github.com/user-attachments/assets/83625f04-162b-4088-aaa1-b9996003c488" />

---

## 🚀 Key Features

* **Auto Observer (AI-Powered Focus):** Automatically selects which player to spectate based on real-time match data (e.g., active gunfights, bomb planting/defusing status, player proximity).
* **Cinematic Camera (HLAE Integration):** Dynamically loads and executes smooth camera paths (*campaths*) at round ends or custom key binds for cinematic transitions.
* **Static Camera Binds Manager:** Fast, customizable hotkeys (F3 to F8) to position the camera instantly at spawn points, bomb sites A/B, mid-map, and overhead top-down views.
* **Intuitive Control Panel:** Built-in desktop dashboard to configure priority weights, adjust transition cooldowns, and manage your license key.

---

## 🛠️ How It Works

The application interfaces with CS2 through two native communication channels:
1. **GSI (Game State Integration):** CS2 sends real-time telemetry (player health, active weapons, match events) to the OMNI Observer server.
2. **Netcon (Network Console):** OMNI Observer connects securely to CS2's internal developer console to simulate spectator slot changes instantly and safely (completely VAC-safe, utilizing official game APIs).

---

## 📦 Installation & Setup (For Users)

1. Download the latest release `.zip` archive from the **Releases** tab of this repository.
2. Extract the archive into a folder of your choice.
3. Open the folder and run **`OMNI Observer.exe`**.
4. In the control panel, click **Install GSI CFG** to configure the integration files for CS2 automatically.
5. Launch CS2 with the `- insecure -netconport 2121` option added to your Steam launch options.
6. You're ready! Start spectating a match, and the automation will take over.

---

## 🖥️ For more content come to our Discord

https://discord.gg/pGAmp6qNYQ
