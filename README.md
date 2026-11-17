Yono PC Keyboard

A Computer-Style Keyboard Experience for Android

Yono PC Keyboard is an Android keyboard application designed to bring a desktop PC keyboard experience to mobile devices. It combines traditional mobile typing with computer-style keyboard layouts, productivity tools, clipboard management, voice input, translation, and floating keyboard functionality.

The main goal is to make Android typing more powerful, flexible, and closer to the experience of using a physical computer keyboard.

---

🎯 Project Goals

Yono PC Keyboard aims to:

- Bring a complete PC-style keyboard layout to Android.
- Provide a comfortable typing experience in Arabic and English.
- Combine mobile keyboard functionality with desktop keyboard features.
- Make computer-style keys and shortcuts accessible on mobile devices.
- Improve productivity through clipboard management and translation.
- Provide flexible keyboard layouts and customizable sizes.
- Support floating keyboard experiences to save screen space.
- Make advanced keyboard functionality accessible without requiring root access.

---

✨ Features

1. PC-Style Keyboard Layout

A computer-inspired keyboard layout designed for Android.

Features include:

- QWERTY keyboard layout.
- Arabic and English characters.
- Uppercase and lowercase letters.
- Numbers and symbols.
- Function keys (F1–F12).
- Arrow keys.
- Computer-style modifier keys:
  - Ctrl
  - Alt
  - Shift
  - Windows
  - Caps Lock
- Individual key buttons with a desktop-inspired appearance.

Some advanced modifier combinations and system-level key operations are still under development.

2. Standard Keyboard Layout

A traditional mobile keyboard layout alongside the PC layout.

- Switch between standard and PC keyboard modes.
- Arabic and English typing.
- Separate keyboard layouts.
- Adjustable keyboard size.
- Easy switching from the keyboard toolbar.

3. Arabic and English Language Support

Yono PC Keyboard supports two primary typing languages:

- Arabic (AR)
- English (EN)

Language functionality includes:

- Switching between Arabic and English.
- Language-aware keyboard layouts.
- Arabic and English character input.
- Language-dependent voice input.
- Localized keyboard interface.

The application is designed to translate its interface according to the selected language without modifying the original language of copied clipboard content.

4. Smart Clipboard Manager

A built-in clipboard manager inspired by modern productivity keyboards.

Features:

- Automatically capture copied text.
- View clipboard history.
- Store up to 50 clipboard entries.
- Paste previously copied text.
- Pin important clipboard entries.
- Unpin entries.
- Delete individual entries.
- Manage clipboard history.

Pinned entries are designed to remain available until manually removed.

Clipboard data is stored locally on the device.

5. Text Translation

An integrated translation feature designed to translate text between Arabic and English.

Features:

- Arabic-to-English translation.
- English-to-Arabic translation.
- Online translation support.
- Translation preview inside the keyboard.
- Apply button to insert translated text.
- Close button to cancel translation.
- Preserve the original text until the user chooses to apply the translation.

Translation is an explicit user action. Text is not supposed to be sent for translation automatically while typing.

6. Voice Typing

Voice input functionality integrated into the keyboard.

Features:

- Microphone button.
- Speech recognition.
- Partial speech results.
- Final recognized text.
- Language-aware voice recognition.
- Insert recognized text into the active input field.

Microphone access requires the appropriate Android permission.

7. Floating Keyboard

A floating keyboard experience designed to provide more flexibility while using other applications.

Planned and developing functionality includes:

- Movable keyboard window.
- Drag-and-drop positioning.
- Floating keyboard controls.
- Minimize and restore functionality.
- Independent floating keyboard customization.
- Preserve the user's preferred configuration.

8. Keyboard Customization

Yono PC Keyboard is designed to allow users to personalize their typing experience.

Customization includes:

- Adjustable keyboard dimensions.
- Separate size settings for different keyboard modes.
- Persistent user preferences.
- Keyboard language selection.
- Keyboard layout selection.
- Floating keyboard positioning.

The standard keyboard and floating keyboard are intended to maintain independent customization settings.

9. Keyboard Execution Mode

A computer-oriented input mode designed to make desktop-style key operations accessible from Android.

The project explores Android KeyEvent-based input and optional Shizuku integration for advanced operations.

The goal is to support:

- Computer-style keys.
- Function keys.
- Navigation keys.
- Modifier keys.
- Keyboard shortcuts.
- Text and command-oriented input.

Execution capabilities depend on Android restrictions, the target application, and the available permissions.

---

🖥️ User Interface

Yono PC Keyboard uses a dark, computer-inspired interface.

Design principles:

- Desktop-inspired keyboard appearance.
- Clearly separated individual keys.
- Easy-to-access toolbar.
- Compact and flexible controls.
- Arabic and English interface localization.
- Simple navigation between keyboard modes.
- Productivity-focused layout.

The keyboard toolbar provides access to features such as:

- Clipboard.
- Translation.
- Voice input.
- Language switching.
- Keyboard layout switching.
- Keyboard resizing.
- Floating keyboard controls.

---

📱 Compatibility

Requirement| Compatibility
Platform| Android
Minimum Android| Android 8.0 (API 26)
Target SDK| Android 12 (API 32)
Compile SDK| Android 15 (API 35)
Architecture| Android-compatible CPU architectures
Root access| Not required
Arabic| Supported
English| Supported
Internet| Required for online translation
Microphone| Required for voice input
Shizuku| Optional for supported advanced operations

Compatibility with specific applications and advanced keyboard operations may vary depending on the Android version and application restrictions.

---

⚙️ Technical Requirements

Development Environment

- Android SDK.
- Android SDK Build Tools.
- Java.
- Gradle.
- Android development environment.
- Android-compatible device or emulator.

Android Permissions and Services

Depending on the enabled features, the application may use:

- Input Method Service (IME).
- Internet permission.
- Microphone permission.
- Speech recognition services.
- System overlay permission for floating windows.
- Clipboard access through Android APIs.
- Shizuku integration for supported advanced operations.

The application does not require root access for normal keyboard functionality.

---

🔐 Privacy and Security

Privacy is an important part of the Yono PC Keyboard project.

Design principles:

- Clipboard history is stored locally.
- Translation requires an explicit user action.
- Voice input requires microphone permission.
- Floating windows require appropriate Android authorization.
- No automatic translation of every typed character.
- No intentional transmission of clipboard history for translation.
- Advanced system operations require appropriate authorization.

Online services may process information explicitly submitted by the user to those services.

---

🛠️ Project Technology

Yono PC Keyboard is developed as a native Android application.

Main project components include:

- Java.
- Android SDK.
- Android Input Method Framework.
- Android KeyEvent APIs.
- Android Speech Recognition.
- Android Clipboard APIs.
- Android SharedPreferences.
- Android Window and Overlay APIs.
- Optional Shizuku integration.

Main Source Files

- "KeyboardImeService.java" — Keyboard input method service.
- "KeyboardSurface.java" — Keyboard interface, layouts, and interactive controls.

---

🚀 Installation

Install the APK

1. Download the available APK from the GitHub Releases section.
2. Install it on a compatible Android device.
3. Open Yono PC Keyboard.
4. Enable Yono PC Keyboard in Android keyboard settings.
5. Select Yono PC Keyboard as the active input method.
6. Grant the permissions required by the features you want to use.

Build from Source

Clone the repository:

git clone https://github.com/yonukitube/YonoPCKeyboard-Termux.git

Open the project directory:

cd YonoPCKeyboard-Termux

Build the debug APK:

gradle assembleDebug

The generated APK is normally located at:

app/build/outputs/apk/debug/app-debug.apk

---

📌 Development Status

Yono PC Keyboard is an actively developing project.

The current implementation includes the core keyboard interface, Arabic and English layouts, standard and PC keyboard modes, clipboard management, voice input, and keyboard customization.

Some advanced capabilities are still being improved.

Feature| Status
Android keyboard integration| Implemented
Arabic keyboard| Implemented
English keyboard| Implemented
Standard keyboard layout| Implemented
PC keyboard layout| Implemented
Keyboard toolbar| Implemented
Clipboard history| Implemented
Clipboard pinning| Implemented
Clipboard deletion| Implemented
Keyboard resizing| Implemented
Voice input| Implemented
Translation preview| Implemented in the current development work
Translation service integration| Under development
Advanced Ctrl/Alt combinations| Under development
Advanced PC key execution| Under development
Full floating typing experience| Under development
Independent floating keyboard customization| Under development

Implementation status may change as development progresses.

---

🔮 Future Development

Planned improvements include:

- More complete PC keyboard functionality.
- Improved Ctrl, Alt, Shift, and Windows key combinations.
- Better application compatibility.
- Improved floating keyboard experience.
- Independent floating and standard keyboard settings.
- More customization options.
- Improved translation reliability.
- Better keyboard performance.
- Additional language support.
- Improved accessibility and usability.

---

👨‍💻 Developer

Project: Yono PC Keyboard
Developer: Yonuk
GitHub: https://github.com/yonukitube

---

📜 License

The project's license and redistribution terms should be specified in the repository's LICENSE file.

---

⭐ Support the Project

If you find Yono PC Keyboard useful:

- Star the repository.
- Report bugs through GitHub Issues.
- Suggest new features.
- Share feedback.
- Contribute to development.

Yono PC Keyboard — Bringing the PC Keyboard Experience to Android.
