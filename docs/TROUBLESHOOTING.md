# Revolution Mobile troubleshooting

Fixes for the problems players run into with the Bee Swarm Simulator macro on Android. Find what you see on your screen, then follow the fix. If yours isn't here, ask in the [Discord](https://discord.gg/revolutionmacro).

**On this page:** [Install](#install) · [Setup and pairing](#setup-and-pairing) · [Connection](#connection) · [Starting the macro](#starting-the-macro) · [While it runs](#while-it-runs) · [Send a report](#send-a-report)

## Install

| What you see | Fix |
|---|---|
| Your browser isn't allowed to install apps | Allow it when Android asks, then open the downloaded file again. |
| Play Protect warns about the app | Revolution Mobile isn't on the Play Store, so Android warns about it like any app installed from a file. Choose to install anyway. Only install the APK from this repository's [Releases](https://github.com/nosyliam/RevolutionMobile/releases/latest). |
| "App not installed" | Your phone needs Android 11 or newer and a 64-bit processor. If you're updating, install over the app you have. Don't uninstall first, or you'll have to pair again. |

## Setup and pairing

| What you see | Fix |
|---|---|
| Developer options doesn't appear | Tap **Build number** 7 times. On a Samsung phone it's under **About phone › Software information**. |
| There's no **Revolution Mobile setup** notification | Notifications are off for the app. Turn them on in your phone's Settings, then tap **Start pairing** again. |
| The notification has no **Enter code** button | Tap the **⌄** arrow on the notification to open it up. |
| `That code didn't work` | Check the 6 digits in the pairing window and type them again. Each code works once. |
| `The pairing window closed` | Android closes it when you leave Settings. Tap **Pair device with pairing code** again and stay in Settings while you type the code into the notification. |
| `Pairing timed out` | Open Revolution Mobile and tap **Start pairing** to try again. |
| **Can't see Wireless debugging** | Turn Wireless debugging off and on again. The app connects by itself after that. |
| Setup stops at **Setup didn't finish** on a Xiaomi, Redmi or POCO phone | In Developer options, turn on **USB debugging (Security settings)**, then tap **Try again**. |
| Setup stops at **Setup didn't finish** on an OPPO, OnePlus or realme phone | In Developer options, turn on **Disable permission monitoring**, then tap **Try again**. |

## Connection

| What you see | Fix |
|---|---|
| **Wireless debugging is off** | It turns off after a restart or a Wi-Fi change. Tap **Open Developer options** and turn it on again. You don't have to pair again. |
| **Wi-Fi disconnected** | Wireless debugging only works on Wi-Fi, not mobile data or a hotspot. Reconnect to Wi-Fi. |
| **Couldn't connect** | Tap **Retry**. If it keeps failing, type the port shown under **Wireless debugging › IP address & Port** (the number after the colon) into the port box and tap **Connect**. |
| It worked yesterday and won't connect today | Check that Revolution Mobile is still listed under **Wireless debugging › Paired devices**. If it's gone, pair again. Restarting the phone and turning Wireless debugging back on fixes most of the rest. |
| It disconnects whenever Wi-Fi drops | Under **Settings › When Wi-Fi drops**, turn on **Keep input running when Wi-Fi drops** and **Turn Wireless debugging back on**. |

## Starting the macro

| What you see | Fix |
|---|---|
| The floating controls don't show | Android is blocking them. On the **Control** tab, follow the **Allow floating controls** card: open **App info**, tap **⋮ › Allow restricted settings**, then tap **Start Macro** again. |
| `Screen capture wasn't allowed` | The macro can't see the game without it. Tap **Start Macro** again and allow screen capture when Android asks. |
| `Roblox isn't installed on this phone` | Install Roblox from the Play Store and open Bee Swarm Simulator once. |
| **Couldn't join the server** | Check your private server link under **Settings › Servers**. A link for another game or an expired link won't join. |
| **No free hive** | The server is full. Use a private server, or start again to join another public server. |
| **No access yet** or **Can't check your access** | Check your internet connection and tap **Try again**. Make sure you signed in with the account you meant to use. |

## While it runs

| What you see | Fix |
|---|---|
| Your character curves off the route or walks into the wrong field | The Roblox camera isn't on Classic. Open the panel, tap **More**, then **Fix Camera**, or set **Camera Mode** to **Classic** in Roblox's settings yourself. |
| Walks stop short of the field, or go past it | **Move speed** is wrong. Under **Settings › Hive and gear**, set it to your base speed as the game shows it, with no buffs. |
| It keeps resetting at the hive or can't find the hive | Check **Hive slot** under **Settings › Hive and gear**, and make sure the camera is on Classic. |
| The macro paused when you opened the panel | That's on purpose. Close the panel or tap **Resume** and it carries on. |
| **Waiting for the helper** | The input helper stopped. Open the panel, tap **More**, and tap **Start** under **Input helper**. If that doesn't do it, check Wireless debugging. |
| **Cooling down** | Your phone hit its heat limit, so the macro closed the game to let it cool. It rejoins by itself. Change the limits under **Settings › Display › Phone heat**. |
| It slows down or stops after a few hours | Allow **Unrestricted battery use** for Revolution Mobile (the app shows a card for it on the **Control** tab), keep the phone plugged in, and keep it cool. |
| The screen goes black while it runs | **Dim the screen while running** is on. Tap the screen to wake it. The macro keeps going underneath. |
| Samsung dims and locks the game after a few minutes | That's Game Booster's touch protection. Drag its lock icon to unlock. It doesn't lock while the macro is pressing keys. |

## Send a report

If Revolution staff give you a support code, open **Settings › Help › Send diagnostics to support**, type the code and tap **Send**. That sends your log and setup details so someone can see what went wrong.

When you ask for help in the [Discord](https://discord.gg/revolutionmacro) or open an [issue](https://github.com/nosyliam/RevolutionMobile/issues), include:

- your phone model and Android version,
- the app version from **Settings › About Revolution Mobile**,
- what you tapped and what the app said.

[Back to the README](../README.md)
