[Español](README.md) | English

# MyMind Electron App

This is an Electron adaptation of the web app MyMind to use it as a desktop application. The application allows you to manage your notes and thoughts efficiently and accessible from your desktop.

## Features

- Access MyMind quickly from your desktop.
- Full functionality of the web app in a standalone application.
- Multiplatform support: Windows, macOS and Linux.

## Installation

### Requirements

- Node.js and npm installed on your system.
- [Electron](https://www.electronjs.org/) installed globally.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/AndreaKinder/mymind-electron-app.git
   cd mymind-electron-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the application:
   ```bash
   npm start
   ```

## Build the Application

To build the application and obtain the executables for your operating system:
```bash
npm run build
```
The built files will be placed in the `dist` directory.

### Directory Content

#### `dist`

* `mymind-electron-app-1.0.0.AppImage`: Executable for Linux in AppImage format.
* `mymind-electron-app-1.0.0.x86_64.rpm`: RPM package for Linux in x86_64 architecture.
* `mymind-electron-app_1.0.0_amd64.deb`: DEB package for Linux in amd64 architecture.

#### `assets/icons`

* `win-icon.ico`: Icon for the application in Windows.
* `mac-icon.icns`: Icon for the application in macOS.
* `mymind-ico.ico`: Icon for the application in Linux.

## Contributing

Thank you for considering Contributing to MyMind Electron App! If you want to report an error or suggest a new feature, please create an issue in this repository.
```

Please note that you may need to adjust the content and formatting to fit your specific needs.

```