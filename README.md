# 🌐 Computer Networks Lab Assignments

**Student:** Lavnish Pandey
**Programme:** B.Tech Computer Science and Engineering (CSE)
**Section:** C
**Subject:** Computer Networks (ENCS304)

---

## 📁 Repository Structure

This repository contains all lab assignments for the Computer Networks course. Each assignment lives in its own dedicated directory. To learn about a specific assignment — what it covers, how to run it, and what files are included — navigate to that assignment's folder and read the `README.md` inside it.

```
📦 computer-networks-labs/
 ├── README.md               ← You are here
 ├── Assignment_1/
 │   ├── README.md           ← Details about Assignment 1
 │   └── ...
 ├── Assignment_2/
 │   ├── README.md           ← Details about Assignment 2
 │   ├── exp2_packetflow.pkt
 │   └── ...
 └── ...
```

---

## 🛠️ Prerequisites — Cisco Packet Tracer

Several assignments in this repository include **`.pkt` files**, which are network simulation files created with **Cisco Packet Tracer**. You must have Packet Tracer installed on your machine to open and interact with these files.

### What is Cisco Packet Tracer?
Cisco Packet Tracer is a network simulation tool developed by Cisco that lets you build virtual networks, configure devices, and observe packet-level behavior — all without needing physical hardware.

---

### 📥 How to Install Cisco Packet Tracer

#### Step 1 — Create a Cisco Networking Academy Account
1. Go to [https://www.netacad.com](https://www.netacad.com)
2. Click **Sign Up** and create a free account (or log in if you already have one)
3. A NetAcad account is required to download Packet Tracer

#### Step 2 — Enroll in the Free Packet Tracer Course
1. After logging in, search for **"Getting Started with Cisco Packet Tracer"**
2. Enroll in the course — it is completely free
3. This gives you access to the official Packet Tracer download

#### Step 3 — Download the Installer
1. Inside the course, go to the **Resources** or **Download** section
2. Choose the installer for your operating system:
   - 🪟 **Windows** — `.exe` installer (64-bit recommended)
   - 🍎 **macOS** — `.dmg` installer
   - 🐧 **Linux** — `.deb` (Ubuntu/Debian) or `.rpm` (Fedora/RHEL)

#### Step 4 — Install Packet Tracer

**Windows:**
1. Run the downloaded `.exe` file
2. Follow the installation wizard (default settings are fine)
3. Launch **Cisco Packet Tracer** from the Start Menu

**macOS:**
1. Open the `.dmg` file
2. Drag the Packet Tracer app into your Applications folder
3. Open it from Applications (you may need to allow it in System Settings → Privacy & Security)

**Linux (Debian/Ubuntu):**
```bash
sudo dpkg -i CiscoPacketTracer_*.deb
sudo apt-get install -f   # fix any missing dependencies
```

**Linux (Fedora/RHEL/CentOS):**
```bash
sudo rpm -i CiscoPacketTracer_*.rpm
# or using dnf (Fedora 22+)
sudo dnf install CiscoPacketTracer_*.rpm
```

**Linux (Arch/Manjaro):**
> Cisco does not provide an official `.pkg.tar.zst` for Arch. Install via the AUR using an AUR helper like `yay` or `paru`:
```bash
# Using yay
yay -S packettracer

# Using paru
paru -S packettracer
```

---

#### Step 5 — Log In
1. When you launch Packet Tracer for the first time, it will ask you to log in
2. Use the same **Cisco NetAcad credentials** you created in Step 1
3. An internet connection is required for the initial login; after that you can use it offline

---

### ✅ Supported Versions

The `.pkt` files in this repository were created with **Cisco Packet Tracer 8.x**. It is recommended to use version **8.0 or later** to ensure full compatibility. Older versions may not be able to open newer `.pkt` files.

---
