# Raider GS — `dev` branch (Fortnite v3.1–v3.5 / Chapter 1 Season 3 — Development)

> **Nightly build:** check the [Releases](../../releases) tab for `nightly-dev` — grab `Raider-dev.dll` and inject.

This is the **dev** branch of Raider GS, targeting **Fortnite Chapter 1, Season 3** (v3.1 / v3.5 range).

> **Unstable:** this branch is actively developed and may be broken at any time. Use `stable` for a tested build.

---

## What is this?

Raider GS is a custom game-server DLL that hooks into an offline Fortnite client, routing gameplay traffic locally so you can host private matches without Epic's servers.

The `dev` branch is where active development happens for Season 3 support. Changes here get tested before merging to `stable`.

---

## Supported build

| Target | Version |
|--------|---------|
| Fortnite | v3.1 – v3.5 |
| Season | Chapter 1, Season 3 |
| Engine | Unreal Engine 4.19 |

---

## Usage

1. Download `Raider-dev.dll` from the [latest nightly release](../../releases/tag/nightly-dev).
2. Launch your Fortnite v3.x client offline.
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
