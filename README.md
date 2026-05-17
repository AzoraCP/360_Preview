# 🌐 360 Preview

### See your Blender 360° renders on your phone instantly.

Render a 360° image in Blender, scan a QR code with your phone, and look around your scene by simply moving your phone.

---

## What Does This Do?

Imagine you just designed an amazing 360° scene in Blender maybe a room, a landscape, or an entire world. Normally, to see how it really feels in 360°, you'd need to upload it to a website, send it to your phone somehow, or use complicated software.

**Gyro 360 Preview makes this simple.** With one click, your 360° render appears on your phone. You hold up your phone, look around, and it's like you're standing inside your scene. Move your phone left, right, up, down, you see everywhere.

---

## What You Get

- **One-click rendering** of 360° images in Blender
- **Instant phone preview** no apps to download, just open the browser
- **Look around with your phone** using its built-in motion sensors (gyroscope)
- **Or swipe with your finger** to look around
- **QR code** to connect your phone instantly
- **Auto-updates** when you render a new image in Blender, your phone updates automatically

---

## Installation

### Step 1: Download the Add-on
1. Click the green **"Code"** button at the top of this page
2. Click **"Download ZIP"**

### Step 2: Install in Blender
1. Open **Blender**
2. Go to **Edit** > **Preferences**
3. Click **Add-ons** on the left side
4. Click the **Install** button at the top
5. Find the ZIP file you downloaded and click **Install Add-on**
6. You'll see "Gyro 360 Preview" appear in the list  **check the box** to enable it


**Done!** The add-on is now ready to use.

---

## 📖 How to Use It

### The Simple 5-Step Workflow

#### 1. Choose Your Render Quality
In the **Render** section:
- **1K** = Fast preview, lower quality
- **2K** = Good balance of speed and quality
- **4K** = Best quality, takes longer
- **Custom** = Pick your own size

> 💡 **Tip**: Start with 1K to test, then go higher for final results.

#### 2. Render Your 360° Image
- Make sure you have a camera in your scene
- Click the big **"Render 360"** button
- Wait for Blender to finish rendering (you'll see a progress bar)

#### 3. Start the Mobile Preview
- In the **Mobile Preview** section, click **"Start Mobile Preview"**
- The add-on will start a small server on your computer
- You'll see a web address appear (something like `http://192.168.1.42:8765`)

> ⚠️ **Important**: Your computer and phone must be on the **same Wi-Fi network**.

#### 4. First Time? Install the QR Module
The first time you use the QR code feature, you'll see a red button that says **"Install QR Module"**. 
- Click it once
- Wait about 30 seconds while it installs
- Click **"Refresh (after install)"** when it's done

You only need to do this **once ever**. After this, the QR code is always available.

#### 5. Scan and Enjoy!
- Click **"Generate QR Code"**
- A QR code will appear in the panel
- Open your phone's camera app and point it at the QR code
- Tap the notification that pops up, it'll open your preview in your phone's browser
- **Allow motion access** when your phone asks (so the gyroscope works)
- Now look around by moving your phone! 🎉

---

## On Your Phone

When you open the preview on your phone, you can:

| Action | What Happens |
|--------|-------------|
| **Move your phone around** | Look around the scene (gyroscope) |
| **Drag your finger** | Look around with touch |
| **Tap "Enable Gyro"** | Turn on motion controls |
| **Tap "Reset"** | Return to the starting view |

> 💡 If gyroscope isn't working on iPhone, go to **Settings > Safari > Motion & Orientation Access** and turn it ON.

---

## Working Faster

Once everything is set up, your workflow becomes super fast:

1. Make changes in Blender
2. Click **"Render 360"**
3. Your phone **automatically updates** with the new render
4. No need to scan QR again, no need to refresh, just look at your phone!

---

## ❓ Common Problems

### "My phone can't connect to the preview"
- Make sure your **computer and phone are on the same Wi-Fi**
- Try turning off your VPN if you have one
- Check that your firewall isn't blocking Blender

### "The QR code isn't working"
- Make sure you clicked **"Start Mobile Preview"** first
- Click **"Install QR Module"** if you see the red button
- Restart Blender if the QR module won't install

### "Gyroscope doesn't work on my iPhone"
- Open the preview in **Safari** (not Chrome) on iPhone
- Go to **Settings → Safari → Motion & Orientation Access** → turn ON
- Tap the **"Enable Gyro"** button on the preview screen
- Allow motion access when prompted


