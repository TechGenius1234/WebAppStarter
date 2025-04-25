# WebAppStarter

A lightweight starter template for ASP.NET Core web apps.  
Modified from the actual Microsoft template. Enjoy! 😄

It does have a email verification part but that isnt coded in,
you will have to do it yourself!

---

## 🚀 Features

- ASP.NET Core MVC project structure  
- Cross-platform compatibility (Windows & Linux)  
- Quick-start for new web app ideas  
- **User Account System**: Email and password login for registered users.

---

## 🖥️ How to Run

### ✅ Requirements

- [.NET SDK 7.0 or newer](https://dotnet.microsoft.com/en-us/download)
- Must have Windows Or Linux
---

### 🪟 Windows

1. Open a terminal (CMD, PowerShell, or VS Code terminal)
2. Navigate to the project folder  
3. Run the app:
   ```bash
   dotnet run
   ```
4. Open your browser and go to `http://localhost:5000` (or the printed URL)

---

### 🐧 Linux (Ubuntu, Debian, Fedora, Arch, etc.)

#### 1. Install the .NET SDK

- **Ubuntu / Debian**:
  ```bash
  sudo apt update
  sudo apt install dotnet-sdk-7.0
  ```

- **Fedora**:
  ```bash
  sudo dnf install dotnet-sdk-7.0
  ```

- **Arch Linux**:
  ```bash
  sudo pacman -S dotnet-sdk
  ```

> Or visit [https://dotnet.microsoft.com/download](https://dotnet.microsoft.com/download) for the latest instructions.

#### 2. Run the app

```bash
cd WebAppStarter
dotnet run
```

Then visit `http://localhost:5000`
#### If your running as a server in your local network or externally then use the ip on another device
#### If you dont have another device then do local HOST

---

## 🧑‍🤝‍🧑 User Accounts

This app supports user accounts with **email** and **password** authentication.

### ✅ Register

To register for an account:
1. Visit the "Register" page in the app.
2. Provide your email and password.
3. Click **Submit** to create your account.

### 🔐 Login

To log in:
1. Visit the "Login" page.
2. Enter your registered email and password.
3. Click **Log In** to access your account.

> If you forget your password, use the "Forgot Password" link on the login page to reset it.

### 🔄 Password Management

If you need to **reset** your password:
1. Click the "Forgot Password" link on the login page.
2. Enter your email address, and a reset link will be sent to you.
3. Follow the instructions in the email to set a new password.

---

## 🙌 Author

**TechGenius1234**  
Modified from the actual MS template. Enjoy!

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
```
