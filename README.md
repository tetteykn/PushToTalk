# Push To Talk – Your Universal Microphone Control Tool

**Push To Talk** is an intuitive and feature-rich application that offers comprehensive microphone control across all your apps and games. Whether you are a gamer, streamer, or a professional, this app enables you to configure and manage your microphone with ease, ensuring consistent performance without the need for app-specific settings.

---

## Key Features

### Multiple Control Modes
- **Push to Talk (PTT)**: Hold to speak
- **Push to Mute (PTM)**: Hold to mute
- **Toggle Mode**: Switch between muted and unmuted states

### Customizable Hotkeys
- Assign unique hotkeys for each control mode
- Support for single keys and multi-key combinations (up to 4 simultaneous keys)
- Distinguishes between Left and Right modifiers (e.g. LeftCtrl ≠ RightCtrl)
- Global hotkey recognition across all applications and games

### Input Methods
Choose from four input backends to suit your use case and game compatibility:
- **Windows Hotkeys**: Lightweight, works when the app is minimized
- **DirectInput**: Low-level keyboard hook — works in most games, captures all keys globally
- **Raw Input**: Windows Raw Input API — reliable in games that block other hooks
- **Polling**: Actively polls key state every 50ms — maximum compatibility fallback

### Profile Auto-Switch
Automatically detects the active (foreground) window and loads the matching saved process profile in real time — no manual switching required.
- Monitors the active window every 250ms
- Instantly applies the matched profile's hotkeys, mic mode, input method, overlay settings, and volume
- Falls back to the global profile when no process-specific profile is found
- Uses an in-memory cache for fast, zero-disk-I/O profile switches

#### Per-Process Profile Management
- **Pick Process**: Browse and select any running application via the Window Picker
- **Get Profile**: Load an existing saved profile for the selected process into the UI for editing
- **Save Process Profile**: Save the current settings as the profile for the selected process

### Advanced Microphone Management
- Precise microphone volume control via Windows Core Audio
- Support for multiple simultaneous microphones
- Option to apply mic state to all non-selected microphones
- Option to mute all non-selected microphones by default on startup
- Right-click the microphone selector to enable or disable devices directly *(requires administrator privileges)*
- Toggle visibility of disabled devices in the microphone list
- Mic state is restored on next launch from the last saved state

### User-Friendly Interface
- Clean and intuitive design
- Easy-to-use controls with system tray integration
- Three built-in themes: **Dark**, **Grey**, and **Light** — applied instantly at runtime

### System Integration
- Auto-start with Windows
- Run minimized to tray on startup
- Minimize to tray and close to tray functionality
- Always run as administrator option with automatic UAC elevation
- Single-instance enforcement to prevent duplicate instances
- System tray icon with right-click context menu (Open, Restart as Admin, Exit)
- Sound feedback for mic state changes
- Mic state is restored on startup to the last known state

### Overlay Feature
- Displays microphone state visually, even in minimized or borderless apps
  *Note: Does not work in fullscreen mode*
- Always on top of other windows
- Draggable and lockable — reposition freely; position is saved per profile
- Customizable color (Blue, Green, Red, Yellow, White, Purple, Orange) and size (Small, Medium, Large, Extra Large)

### Profile Management
- Save and load complete configuration profiles to/from `.ptt` files
- Profiles include hotkeys, mic mode, input method, overlay settings, volume, theme, and all flags
- Seamlessly switch between different setups without reconfiguration

### Mic State Monitor
A background watchdog that re-applies the correct mute state every 500ms, ensuring the microphone state is never silently overridden by other applications or system events.

---

## Trial Information
Push To Talk offers a **7-day free trial** during which users can access all features of the app without any limitations.
After the trial period, the app will no longer function unless a **one-time purchase of $5** is made to activate the app permanently.
This ensures that users can fully experience the app's capabilities before deciding to purchase.

---

## Why Choose Push To Talk?
Push To Talk eliminates the hassle of managing microphone settings for each app. With a single, unified control scheme, you can switch effortlessly between gaming, streaming, or professional work without any need for reconfiguration. The Profile Auto-Switch feature takes this even further by automatically adapting your entire configuration the moment you switch between applications.

---

## Support & Contact
For support or inquiries, contact us at:

- **Email**: [phonetettey@gmail.com](mailto:phonetettey@gmail.com)
- **Discord**: [Join our Discord](https://discord.com/invite/jRnaeTJ)
- **GitHub**: [PushToTalk Repository](https://github.com/tetteykn/PushToTalk)
- **YouTube**: [Our Channel](https://www.youtube.com/channel/UCksGhlnuOhirbMzMG3yYJmg)
