# 🩸 KillLosers — CS2 Plugin for CounterStrikeSharp

**KillLosers** is a plugin for Counter-Strike 2 servers using CounterStrikeSharp that automatically kills all players on the losing team at the end of each round.

## 🔥 Features

- Kill all players on the **losing team** at the end of the round
- Works with all default win conditions:
  - Bomb exploded (CTs lose)
  - Bomb defused (Ts lose)
  - Time ran out (Ts or CTs lose depending on objective)
  - Team elimination
- Lightweight and dependency-free

## 📦 Installation

1. Copy `KillLosers.dll` into your server directory:

   ```bash
   cs2/addons/counterstrikesharp/plugins/
   ```

2. Reload plugin or restart the server:

   ```bash
   css_reload KillLosers
   ```

## 💻 Build from source

If you want to build the plugin manually:

```bash
dotnet restore
dotnet build -c Release
```

Output will be in:
```
bin/Release/net8.0/KillLosers.dll
```

## ✅ Requirements

- CS2 dedicated server
- MetaMod & [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)


## 📝 License

MIT — Free to use and modify.
