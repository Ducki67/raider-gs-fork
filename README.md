# Raider GS — `stable` branch (Fortnite v3.5 / Chapter 1 Season 3)

> **Nightly build:** check the [Releases](../../releases) tab for `nightly-stable` — grab `Raider-stable.dll` and inject.

This is the **stable** branch of Raider GS, targeting **Fortnite v3.5** (Chapter 1, Season 3).  
It is the primary supported fork and receives the most testing.

---

## What is this?

Raider GS is a custom game-server DLL that hooks into an offline Fortnite client, routing gameplay traffic locally so you can host private matches without Epic's servers.

This branch was based on [kem0x/raider3.5](https://github.com/kem0x/raider3.5) and has been extended and maintained as a fork.

---

## Supported build

| Target | Version |
|--------|---------|
| Fortnite | v3.5 (CL 3724489) |
| Season | Chapter 1, Season 3 |
| Engine | Unreal Engine 4.20 |

---

## Usage

1. Download `Raider-stable.dll` from the [latest nightly release](../../releases/tag/nightly-stable).
2. Launch your Fortnite v3.5 client offline.
3. Inject the DLL with your preferred injector.
4. Start a backend (e.g. DuckiServer, LawinServer) and connect.

---

## Building from source

**Requirements:** Visual Studio 2022, v143 toolset, Windows SDK 10.0

```
msbuild /m /p:Configuration=Release Raider.sln
```

Output: `Raider\bin\Release\Raider.dll`

---

## Disclaimer

This is an unofficial fan project made for nostalgic purposes. It is not affiliated with, endorsed by, or connected to Epic Games in any way. No paid cosmetics are supported or allowed. If you are an Epic Games employee with concerns, please contact `kareemolim@gmail.com`. We will honour takedown requests.

Licensed under the [MIT License](LICENSE).
