# OneWoW Suite (player repo)

Addon folders only for **World of Warcraft Retail**. Clone this repository and `git pull` when you want the latest files. You do not need the full development tree.

**Website:** https://wow2.xyz/

**Player docs:** [Suite wiki](https://github.com/kellewic/OneWoW_Suite/wiki)

**Full source, docs, and tools:** [kellewic/OneWoW_Suite](https://github.com/kellewic/OneWoW_Suite)

This repo is a **mirror**. Addon code is maintained on the Suite repo. Please do not open issues or pull requests here.

---

## Install

1. Clone (latest snapshot only; skip Git history):

   ```text
   git clone --depth 1 https://github.com/MichinMigugin/OneWoW_Suite_PlayerRepo.git
   ```

2. Copy the `OneWoW` and `OneWoW_*` folders into:

   ```text
   World of Warcraft\_retail_\Interface\AddOns\
   ```

   You do not need every folder. `OneWoW` is required. Copy the feature folders you use, plus their companion data folders (Catalog and AltTracker).

3. At the character select screen, enable **OneWoW** and any optional modules you copied.

4. Log in (or `/reload`) and type `/1w`.

**GitHub zip** works the same way: download the repo zip, unpack, then copy the addon folders. A zip is a full snapshot each time, not an incremental update.

**CurseForge** and the Discord community zip remain supported if you do not want Git.

### Stay up to date

```text
cd OneWoW_Suite_PlayerRepo
git pull
```

Then copy the folders into `AddOns` again (overwrite). If you **junction** each `OneWoW*` folder from this clone into `AddOns`, `git pull` is the whole update.

A scheduled GitHub Action copies the addon folders from [kellewic/OneWoW_Suite](https://github.com/kellewic/OneWoW_Suite). You can also run **Actions → Sync from Suite → Run workflow**.

---

## What is in this repo

| Kind | Folders |
|------|---------|
| **Required** | `OneWoW` |
| **Features** | `OneWoW_Bags`, `OneWoW_QoL`, `OneWoW_AltTracker`, `OneWoW_Catalog`, `OneWoW_Trackers`, `OneWoW_Notes`, `OneWoW_ShoppingList`, `OneWoW_Mail`, `OneWoW_DirectDeposit` |
| **Catalog data** | `OneWoW_CatalogData_Journal`, `OneWoW_CatalogData_Vendors`, `OneWoW_CatalogData_Tradeskills`, `OneWoW_CatalogData_Quests` |
| **AltTracker data** | `OneWoW_AltTracker_Storage`, `OneWoW_AltTracker_Character`, `OneWoW_AltTracker_Professions`, `OneWoW_AltTracker_Collections`, `OneWoW_AltTracker_Endgame`, `OneWoW_AltTracker_Auctions`, `OneWoW_AltTracker_Accounting` |
| **Optional tool** | `OneWoW_Utility_DevTool` — in-game inspector (`/1wdt`). Not required to play. |

Enable features in the hub under **Manage Features**. If Catalog or AltTracker looks empty, confirm the matching data folders are also in `AddOns` and enabled.

---

## What is not here

The Suite repo also has engineering docs, locale tooling, DB2 extracts, wiki source, Cursor/agent files, and the Account Sync desktop app. You do not need those to play.

Want to contribute or read architecture docs? Use [kellewic/OneWoW_Suite](https://github.com/kellewic/OneWoW_Suite).

---

## Support

https://wow2.xyz/support/

---

**Author:** MichinMuggin / Ricky

**Website:** https://wow2.xyz/

**All rights reserved.**
