# Raider GS — `kyiro` branch (Fortnite v4.5 / Chapter 1 Season 4 — Kyro's Fork)

> **Nightly build:** check the [Releases](../../releases) tab for `nightly-kyiro` — grab `Raider-kyiro.dll` and inject.

This is the **kyiro** branch of Raider GS, targeting **Fortnite v4.5** (Chapter 1, Season 4, late patch).  
This is Kyro's personal fork with their own fixes and additions for the v4.5 client.

---

## What is this?

Raider GS is a custom game-server DLL that hooks into an offline Fortnite client, routing gameplay traffic locally so you can host private matches without Epic's servers.

This branch was forked by **Kyro** from the raider base and adapted specifically for Fortnite v4.5.

---

## Supported build

| Target | Version |
|--------|---------|
| Fortnite | v4.5 |
| Season | Chapter 1, Season 4 |
| Engine | Unreal Engine 4.20 |

---

## Usage

1. Download `Raider-kyiro.dll` from the [latest nightly release](../../releases/tag/nightly-kyiro).
2. Launch your Fortnite v4.5 client offline.
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
