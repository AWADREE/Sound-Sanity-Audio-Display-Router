# Sound Sanity - Audio Display Router


Sound Sanity is a powerful Windows application that automatically routes audio to the correct speakers based on which monitor your applications are displayed on. Perfect for multi-monitor setups with different audio devices.

---

## 🚀 Getting Started

1. **Launch the Application**: Run Sound Sanity as Administrator for full functionality
2. **System Tray**: The app runs in your system tray (look for the audio icon)
3. **Right-click** the tray icon to access the main menu

---

## ⚙️ Initial Setup

**Important**: When you first open Sound Sanity, you'll need to assign your audio devices to your displays for the automatic routing to work properly.

1. **Open Settings**: Right-click the tray icon and select "⚙️ Settings"
2. **Configure Audio Devices**: Assign each of your audio devices (speakers, headphones) to their corresponding displays
3. **Save Configuration**: Your settings will be remembered for future use
4. **Test the Setup**: Move a window between monitors and verify audio follows correctly

_This one-time setup ensures Sound Sanity knows which audio device belongs to each monitor._

**Note**: The Settings window includes a theme toggle button to switch between Light and Dark modes for better visual comfort.
---

## 📋 Main Features

### **System Tray Menu**

Right-click the tray icon to access:

- **💻 Align All**: Instantly routes all audio to match current window positions
- **🖥️ Align Selected**: Instantly routes selected audio to match current window positions
- **🎛️ Audio Mixer**: Configure application preferences
- **⚙️ Settings**: Opens the main audio control window
- **❌ Exit**: Close the application

### **Audio Mixer Window**

The main control center for all your audio sessions.

#### **Header Controls (Top Bar)**

- **Auto Align Switch**:

  - **Location**: Top-left corner
  - **Function**: Automatically routes audio when you drag windows between monitors
  - **Status**: Green when enabled, gray when disabled

- **Auto Refresh Switch**:

  - **Location**: Next to Auto Align
  - **Function**: Automatically detects new audio sessions every 2 seconds
  - **Status**: Green when enabled, gray when disabled

- **💻 Align All Button**:

  - **Location**: Top-right corner
  - **Function**: Manually align all windows and their audio to correct displays
  - **When to use**: After moving multiple windows or starting new applications

- **Refresh Button**:
  - **Location**: Far top-right corner
  - **Function**: Manually refresh the list of audio sessions
  - **When to use**: When new applications aren't showing up automatically

#### **Audio Session Controls**

Each audio device shows its connected applications:

- **🔊 Device Headers**:

  - Shows device name and number of active sessions
  - Groups all applications using that audio device

- **Application Controls** (for each running audio app):
  - **App Icon**: Visual identifier for the application
  - **App Name**: Name of the application and process ID
  - **Volume Slider**: Drag to adjust application volume (0-100%)
  - **Volume Percentage**: Shows current volume level
  - **🔊/🔇 Mute Button**: Click to mute/unmute the specific application

---

## 🎯 How to Use

### **Basic Audio Control**

1. Open the **Mixer** from the tray menu
2. Find your application in the list
3. Use the **volume slider** to adjust loudness
4. Click the **🔊 button** to mute/unmute

### **Automatic Audio Routing**

1. Enable **Auto Align** in the mixer
2. Drag any window to a different monitor
3. Audio automatically routes to that monitor's speakers
4. No manual intervention needed!

### **Manual Audio Alignment**

1. Move your windows to desired monitors
2. Click **💻 Align All** button
3. All audio instantly routes to correct speakers

### **Multi-Monitor Setup**

1. Connect different speakers/headphones to each monitor
2. Enable **Auto Align**
3. Move applications between monitors
4. Audio follows your windows automatically

---

## 💡 Tips & Best Practices

- **Run as Administrator**: For full system access and best performance
- **Enable Auto Refresh**: Automatically detects new applications
- **Use Auto Align**: For seamless multi-monitor audio experience
- **Volume Control**: Adjust individual app volumes without affecting system volume
- **Quick Access**: Keep the mixer open while gaming or working with multiple audio sources
- **Temporary Auto Align Control**: Feel free to disable Auto Align from the mixer window when you don't want a window to change its output device while moving it, then re-enable it again. The window will stay with your preferred output device until you choose to align it again

---

## � Blacklist Manager

The Blacklist Manager allows you to control which applications should be excluded from automatic audio alignment.

### **How to Access**
- Available through the **Settings** menu in the system tray

### **How it Works**
- **Add Applications**: Prevent specific applications from being automatically moved between audio devices
- **System Processes**: Many system processes and applications come pre-checked for your convenience
- **Custom Control**: You can uncheck system processes to enable alignment on them if needed

### **Important Notes**
- **System processes** that you uncheck **will NOT be aligned** using **Auto Align**
- **Manual alignment** still works: Use **💻 Align All** button or **Align Selected** to Align these applications
- **Use Cases**: Perfect for applications you want to keep on a specific audio device (like music players, communication apps, or system sounds)

---

## �🔧 Window Controls

### **Responsive Design**

The mixer window adapts to different sizes:

- **Wide Mode** (545px+): Shows all labels and percentages
- **Medium Mode** (430-545px): Hides switch labels to save space
- **Compact Mode** (<430px): Hides volume percentages and app names for maximum slider space

### **Window Management**

- **Resize**: Drag any edge or corner to resize
- **Move**: Drag the title bar to reposition
- **Close**: Click the ❌ button or minimize to tray

---

## ❓ Troubleshooting

**Q: Application not showing in the list?**

- Click **Refresh** or enable **Auto Refresh**
- Make sure the app is actively playing audio

**Q: Audio not switching monitors?**

- Click **💻 Align All** to manually align
- Or Ensure **Auto Align** is enabled in the **Mixer** window for automatic switching

**Q: Volume controls not working?**

- Run Sound Sanity as Administrator
- Check that the application is not muted in Windows sound settings

**Q: App missing from system tray?**

- Check hidden icons in the system tray
- Restart the application

---

## 💖 Support the Developer

If you find Sound Sanity useful and it makes your multi-monitor audio setup better, consider supporting the developer:

**☕ [Buy me a coffee](https://ko-fi.com/awadree)**

---

## 📝 System Requirements

- **Windows 10/11** (64-bit recommended)
- **Multiple audio devices** (for multi-monitor routing)
- **Administrator privileges** (for full functionality)

---

_Thank you for using Sound Sanity!_
