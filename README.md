# Brevent-fps-boost
⚠️ Important Warnings & How to Use

⚠️ Warnings

- Make sure Brevent is running and the required permissions are granted.
- Replace "<PACKAGE_NAME>" with the exact package name of your game. Do not include the angle brackets.
- Run commands one at a time.
- Some commands may not be supported on certain Android versions or devices.
- The Game Mode features are available on selected Android 12 devices and Android 13 or newer. They may not work on Android 10 or older versions.

📌 How to Use

1. Find your game's package name.
2. Replace "<PACKAGE_NAME>" with your game's package name.
3. Run the commands one by one.

Commands

```cmd package compile -m speed -f <package.name>```

```cmd package bg-dexopt-job```

```cmd device_config put game_overlay <package.name> mode=2,fps=60:mode=3,fps=30```

```cmd game mode set performance <package.name>```

```cmd game set --downscale 0.9 <package.name>```

```cmd activity set-standby-bucket <package_name> active```


★ ADB Fix: Enable These Settings First!

SAMSUNG (All Galaxy Series)
Go to: Settings Security and Privacy

Turn OFF: Auto Blocker

XIAOMI / REDMI / POCO /BLACK SHARK
Go to: Developer Options

Turn ON: USB Debugging (Security Settings)

OPPO / REALME / ONEPLUS
Go to: Developer Options

Turn ON: Disable permission monitoring

VIVO/IQOO
Go to: Developer Options

Turn ON: USB Debugging

(Security Settings) & Simulate Input
