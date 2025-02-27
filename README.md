# How to Install and Set Up Flutter on Windows (Step-by-Step Guide)

Flutter is a framework created by Google for building cross-platform apps with a single codebase. This guide will help you install Flutter on your Windows PC, even if you have no prior programming experience.

## Step 1: Check System Requirements
Before installing Flutter, make sure your PC meets the following requirements:
- ✅ Windows 10 or later (64-bit)
- ✅ At least 8GB RAM (Recommended: 16GB)
- ✅ At least 10GB of free disk space
- ✅ Git for Windows installed
- ✅ Latest version of PowerShell

## Step 2: Download and Install Flutter

### 1️⃣ Download Flutter SDK
[Download Flutter for Windows](https://docs.flutter.dev/get-started/install/windows)

- Click on **"Windows"** under the Install Flutter section.
- Download the latest stable **Flutter SDK (Windows .zip file)**.

### 2️⃣ Extract Flutter SDK
- Locate the downloaded ZIP file (usually in the Downloads folder).
- Right-click the ZIP file and select **Extract All…**
- Choose a location, such as **C:\flutter** (avoid installing in "Program Files" to prevent permission issues).

## Step 3: Set Up Environment Variables

### 1️⃣ Add Flutter to System Path
- Open **File Explorer** and navigate to `C:\src\flutter\bin`.
- Copy the path (`C:\src\flutter\bin`).
- Search for **"Environment Variables"** in Windows and open **"Edit the system environment variables"**.
- Click **"Environment Variables"** > Find **"Path"** under System Variables > Click **"Edit…"**.
- Click **"New"**, paste `C:\src\flutter\bin`, and click **OK**.

## Step 4: Install Git (Required for Flutter)

- Go to [Git for Windows](https://git-scm.com/download/win) and download the latest version.
- Run the installer and follow the default settings.

## Step 5: Verify Flutter Installation

- Open **Command Prompt (cmd)** or **PowerShell**.
- Type:
  ```sh
  flutter doctor
  ```
- Press **Enter**.

## Step 6: Install Android Studio (For Emulator and SDK)

[Download Android Studio](https://developer.android.com/studio)

- Install Android Studio and open it.
- In the **Setup Wizard**, install the **Android SDK, Android SDK Command-line Tools, and an Emulator**.

## Step 7: Set Up Flutter in Android Studio

1. Open **Android Studio**.
2. Go to **Settings** > **Plugins**.
3. Search for **Flutter**, click **Install**, and then restart Android Studio.
4. Go to **Settings > Appearance & Behavior > System Settings > Android SDK**.
5. Make sure **"Android SDK Platform"** and **"Android SDK Build-Tools"** are installed.

## Step 8: Set Up Emulator (Optional but Recommended)

1. Open **Android Studio**.
2. Go to **Tools > AVD Manager** (Android Virtual Device Manager).
3. Click **Create Virtual Device** and select a device (e.g., Pixel 5).
4. Select a system image and install it.
5. Click **Finish** and **Launch Emulator**.

## Step 9: Run Your First Flutter App

1. Open **Command Prompt** and navigate to your projects folder:
   ```sh
   cd C:\Users\YourName\Documents
   ```
2. Create a new Flutter app:
   ```sh
   flutter create my_first_app
   ```
3. Navigate into your app folder:
   ```sh
   cd my_first_app
   ```
4. Run the app:
   ```sh
   flutter run
   ```

**Congratulations! Your first Flutter app is running on an emulator or a connected device!** 

## Troubleshooting & FAQs

### 1. "flutter doctor" shows missing dependencies?
- Make sure Git and Android SDK are installed.
- Restart your PC and run `flutter doctor` again.

### 2. Emulator is slow or not working?
- Enable **Virtualization Technology (VT-x)** in BIOS.
- Use a real Android device instead.

### 3. Need Help?
- Visit the official Flutter docs: [Flutter Docs](https://docs.flutter.dev)
- Connect with me, Shrijal Shrestha:
  [Linkedin](https://www.linkedin.com/in/shrijal-shrestha-063421181/) | [Instagram](https://www.instagram.com/shrijalshr/)

**You are now ready to build Flutter apps!**
