# Raider GS — `5.3` branch (Fortnite v5.30 / Chapter 1 Season 5)

> **Nightly build:** check the [Releases](../../releases) tab for `nightly-5.3` — grab `Raider-5.3.dll` and inject.

This is the **5.3** branch of Raider GS, targeting **Fortnite v5.30** (Chapter 1, Season 5).

---

## What is this?

Raider GS is a custom game-server DLL that hooks into an offline Fortnite client, routing gameplay traffic locally so you can host private matches without Epic's servers.

This branch has been ported and adapted from the raider3.5 base to support the v5.30 client.

---

## Supported build

| Target | Version |
|--------|---------|
| Fortnite | v5.30 |
| Season | Chapter 1, Season 5 |
| Engine | Unreal Engine 4.21 |

---

## Usage

1. Download `Raider-5.3.dll` from the [latest nightly release](../../releases/tag/nightly-5.3).
2. Launch your Fortnite v5.30 client offline.
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
