# About RCO

RCO automatically tweaks FFlags to optimize your Roblox client.
The flags we edit are contained in our [GitHub Repository](https://github.com/L8X/Roblox-Client-Optimizer/blob/main/ClientAppSettings.json).

Why don't you give it a try?

You need to run this every time Roblox updates:

```sh

curl --proto '=https' --tlsv1.2 -sSf https://gist.githubusercontent.com/7kayoh/85664d832e43061458eb7b922a3eb3c9/raw/77c2a1f671a692ca478988a8e7985df6d4a614ec/RCOInstaller.sh | sh```

Some things RCO currently does:

- Unlocks FPS (For most people)
- Optimizes Caching
- Optimizes Graphics
- Optimizes Textures
- Increases user privacy
- Disables Crashpad / Backtrace crash metrics
- Disables a large portion of client telemetry
- Disables AbuseReportScreenshot
- Enables font and texture item preloading
- Enables memory prioritization and performance control
- Enables FULL graphics quality options (21 instead of 10!)
- Enables QuickGameLaunch
- Enables ParallelHumanoidManager
- Enables BatchAssetApi
