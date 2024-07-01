# 3D Scan And Share System
[![](https://img.youtube.com/vi/5IKGkQtX96k/0.jpg)](https://www.youtube.com/watch?v=5IKGkQtX96k)

# Setup Instructions

1. **Network Connection**
   - Connect your PC and iPhone/iPad to the same network.

2. **Application Installation**
   - Install the app to iPhone/iPad.
     * Please contact me for the download link. [X](https://twitter.com/Tks_Yoshinaga),[LinkedIn](https://www.linkedin.com/in/tks-yoshinaga/)
     * This app works on iPhone/iPad but using the model with LiDAR sensor is recommended.
   - Download the app for Looking Glass from download page. [Download](https://github.com/TakashiYoshinaga/3D-Scan-And-Share/releases)
   - Download and install Looking Glass Bridge from the official website: [Looking Glass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).
   - Confirm your display setting. [Display Setting](https://docs.lookingglassfactory.com/software-tools/looking-glass-bridge/display-settings-on-windows)



# Application Usage

1. **Connect Devices**
   - Connect your PC and the Looking Glass Portrait using an HDMI cable.

2. **Launch Software**
   - Start the Looking Glass Bridge application.
   - Launch `3DObjectViewer.exe`.
   - Ensure that the Looking Glass displays the PC's IP Address.

3. **Start the iPhone/iPad App**
   - Open the iPhone/iPad app.
   - Enter the IP Address in the app and tap the `Connect` button.

4. **Scan & Play**
   - Please refer to the demo video to perform the 3D scan and share.
   - When viewing objects in Looking Glass, the following operations are possible:


| Operation          | Description               |
| ------------------ | ------------------------- |
| Left Drag          | Move Up/Down/Left/Right   |
| Right Drag         | Rotate                    |
| Scroll             | Move Forward/Backward     |
| Ctrl + Scroll      | Zoom In/Out               |
| Right Arrow (Keyboard)  | Display Next Object     |
| Left Arrow (Keyboard)   | Display Previous Object |
| R (Keyboard)       | Reset Rotation            |
| D (Keyboard)       | Delete Current Object     |
| Q (Keyboard)       | Export Quilt Image        |


  
# Adding and Deleting 3D Model Files
   - Please add or delete files as needed in the `dl` folder within the same directory as 3DObjectViewer.exe.
   - Additionally, you can delete the currently displayed object by pressing the `D key` while running 3DObjectViewer.exe.

# Exporting Data
   - By pressing the `Q key` while running 3DObjectViewer.exe, Quilt images will be saved in the following directory:  
     3DScanObjectViewerForWindows -> Quilts


# Trouble Shooting
- After sending 3d model to a PC, if the model not appear immediately in LookingGlass, please remove 3DObjectViewer.exe from your firewall settings once.  
Alternatively, turn off the firewall only when using this application.
- When you update the version of the Scan app (iOS), the app may crash after the scan is complete. In such cases, please restart your iPhone and try scanning again.
- If the receiver app is unable to receive 3D objects, please restart your PC (or Quest).
  
# Show Your Usecase
I would love to see your use cases and scanned creations. It’s not mandatory, but if you’re willing, I would appreciate it if you could tag the following accounts when posting on social media.

X: [@Tks_Yoshinaga](https://x.com/Tks_Yoshinaga)  
LinkedIn: [Takashi Yoshinaga](https://www.linkedin.com/in/tks-yoshinaga/)  

# Depth Video Player
If you are interested in recording and playing back depth-enabled videos rather than displaying 3D scanned objects, please try the following application!  
https://github.com/TakashiYoshinaga/DepthVideoPlayer


