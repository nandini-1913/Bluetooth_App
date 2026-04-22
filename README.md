# 📡 Rio Smart — Bluetooth Meter Configuration App

> A Flutter-based mobile application for wireless configuration of smart meters and IoT devices over Bluetooth.

---

## 🔍 Overview

**Rio Smart** is an Android/iOS mobile application built with Flutter that enables field engineers and technicians to configure smart meters and IoT-connected electronic devices wirelessly via Bluetooth. It eliminates the need for physical wired interfaces during device setup, making on-site meter configuration faster, safer, and more efficient.

---

## ✨ Features

- 🔵 **Bluetooth Device Discovery** — Scan and detect nearby smart meters and IoT devices
- 🔗 **Wireless Pairing & Connection** — Seamlessly connect to target devices over BLE (Bluetooth Low Energy)
- ⚙️ **Meter Configuration** — Read and write configuration parameters directly to the device
- 📊 **Real-time Data Exchange** — Send and receive configuration data packets in real time
- 📱 **Cross-Platform** — Runs on both Android and iOS from a single Flutter codebase
- 🔒 **Secure Communication** — Controlled access to device configuration over Bluetooth

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Flutter (Dart) |
| Communication Protocol | Bluetooth / BLE |
| Target Devices | Smart Meters, IoT Devices |
| Platform Support | Android, iOS |

---

## 📁 Project Structure

```
Bluetooth_App/
├── lib/                        # Main Flutter source code
├── pubspec.yaml                # Project dependencies & metadata
├── pubspec.lock                # Locked dependency versions
├── analysis_options.yaml       # Dart linting rules
├── devtools_options.yaml       # Flutter DevTools config
├── .flutter-plugins-dependencies  # Flutter plugin registry
└── rio_smart.iml               # IntelliJ/Android Studio module file
```

---

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.x or above)
- Dart SDK (included with Flutter)
- Android Studio / VS Code with Flutter extension
- A physical Android or iOS device (Bluetooth required — emulators won't work)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nandini-1913/Bluetooth_App.git
   cd Bluetooth_App
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

> ⚠️ Make sure Bluetooth is enabled on your device and you have granted Bluetooth and location permissions to the app.

---

## 📲 Permissions Required

- `BLUETOOTH` / `BLUETOOTH_SCAN` / `BLUETOOTH_CONNECT` — For BLE device communication
- `ACCESS_FINE_LOCATION` — Required by Android for Bluetooth scanning

---

## 🌐 Use Case

This application is designed for configuring **smart meters** — electronic IoT devices used in energy metering, water measurement, or industrial sensing — without requiring a physical port or manual wiring. It is particularly useful in:

- Smart grid energy meter deployments
- Water/gas meter installations
- Industrial IoT device provisioning
- Field service & maintenance operations

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

---

## 👩‍💻 Author

**Nandini**
- GitHub: [@nandini-1913](https://github.com/nandini-1913)

---

## 📄 License

This project is open source. Feel free to use and contribute.

---

> Built with ❤️ using Flutter | Powering smarter IoT device configuration
