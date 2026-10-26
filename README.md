# Ex-1_INSTALLING-AND-RUNNING-APPLICATIONS-ON-ANDROID-STUDIO
even_term_ii_2025-2027

## NAME: SANDEEP S
## Register number: 212223220092

# Android Studio Installation and Running Applications

This repository contains the experiment/documentation for installing Android Studio, creating a project, and running applications on an emulator or a physical device.

## Aim
To install Android Studio, configure the environment for Android application development, run a sample application, and connect the project to Firebase.

---

## Software Requirements
- Android Studio (latest stable version)
- JDK 17 or later (bundled with Android Studio as the JetBrains Runtime)
- Android SDK and SDK Platform-Tools
- Android Virtual Device (AVD)
- Google account (for Firebase)

## Hardware Requirements
- 8 GB RAM minimum (16 GB recommended)
- 8 GB free disk space (SSD recommended)
- 64-bit OS (Windows 10/11, macOS or Linux)
- Virtualization enabled in BIOS (Intel VT-x / AMD-V) for the emulator

---

## Step 1 – System Requirements
The tools needed for Android development are free and can be downloaded from the web.

### Required Software
- Android Studio (includes the JDK, SDK and emulator tools)

---

## Step 2 – Setup Android Studio
Android Studio is the official IDE for Android development and is built on IntelliJ IDEA.

### Installation Procedure
1. Download Android Studio from https://developer.android.com/studio.
2. Run the installer and follow the setup wizard.
3. Select the required components:
   - Android Studio
   - Android SDK
   - Android Virtual Device
   - Performance tools (e.g. Intel HAXM / Hypervisor)
4. Choose the installation location.
5. Complete the SDK package download and installation.
6. Launch Android Studio.

---

## Step 3 – Create a New Project
1. Open Android Studio and click **New Project**.
2. Select an activity template (e.g. **Empty Views Activity** or **Empty Activity**).
3. Enter:
   - Application Name
   - Package Name
   - Save Location
   - Language (Java)
   - Minimum SDK version
4. Click **Finish** and wait for the Gradle sync to complete.

---

## Step 4 – Create an Android Virtual Device (AVD)
1. Open **Tools → Device Manager**.
2. Click **Create Device**.
3. Select a device definition (e.g. Pixel 7).
4. Download and select a system image (e.g. API 34).
5. Click **Finish**.

---

## Step 5 – Run the Application
### On the emulator
1. Select the AVD from the device drop-down in the toolbar.
2. Click **Run ▶** (or press `Shift + F10`).
3. Wait for the emulator to boot. The app opens automatically.

### On a physical device
1. Enable **Developer options** (tap *Build number* 7 times in Settings → About phone).
2. Turn on **USB debugging**.
3. Connect the phone with a USB cable and allow the debugging prompt.
4. Select your device in the toolbar and click **Run ▶**.

---

## Result
Android Studio was installed successfully and the Android Virtual Device was configured for running Android applications.

---

## Conclusion
The Android development environment was successfully set up using Android Studio, SDK, and AVD tools.
