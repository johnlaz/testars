<div align="center">

# ⬡ ARMORY
### *Firearms Inventory System*

**v3.0 · Professional Grade · Offline-First · AI-Powered**

---

*Your collection deserves better than a spreadsheet.*

</div>

---

## What Is ARMORY?

ARMORY is a full-featured, AI-powered firearms inventory system built as a Progressive Web App — installable on Android, iOS, Windows, and macOS without an app store. It runs entirely on your device. Your data never leaves your hands.

Built by a collector, for collectors — ARMORY bridges the gap between the physical firearm in your safe and the professional digital record your insurance company needs on day one.

---

## The Problem It Solves

Most collectors reach what I call the **Excel Plateau** — a half-finished spreadsheet that's tedious to maintain and offers zero peace of mind. Every new acquisition brings the same questions:

- *Do I have the serial number recorded correctly?*
- *What's this collection actually worth right now?*
- *If something happened today, would my documentation hold up?*

ARMORY answers all three. Immediately.

---

## Core Features

### 📸 One-Scan Intake
Point your camera at any firearm or its markings. The AI identifies the make, model, caliber, and technical specifications automatically — no typing required. Add a new piece to your vault in under 60 seconds.

### 🤖 The Intelligence Layer
Powered by Groq's large language model API, ARMORY generates rich AI descriptions and manufacturer histories for every firearm in your vault. A serial number becomes a story. Specs fill themselves in. The intelligence layer runs on demand — tap **AI UPDATE SPECS** in any detail view and watch it work.

### 📋 Professional Spec Sheets
Every firearm gets a complete, structured record:

| Field | Field | Field |
|-------|-------|-------|
| Make & Model | Caliber | Action Type |
| Barrel Length | Overall Length | Weight |
| Capacity | Finish | Year of Manufacture |
| Condition | MSRP / Est. Value | Purchase Date |
| Storage Location | Notes | Serial Number |

### 📷 Photo Gallery
Each firearm supports a **hero photo** plus an **unlimited gallery** of additional images — markings, accessories, modifications, condition documentation. Tap any thumbnail for a fullscreen lightbox viewer with swipe navigation.

### 💰 Live Vault Dashboard
The header displays your vault at a glance, always up to date:

- **Firearm count** — total pieces in inventory
- **Vault Value** — running MSRP / estimated total across all firearms
- **Rounds Fired** — total rounds logged across your entire collection, tap to filter

### 🎯 Range Log
Track every range session per firearm. Log rounds fired, view session history, and watch the vault-wide total update in real time. Filter your entire inventory to show only firearms with active range data.

### 🔧 Maintenance Records
Per-firearm service tracking with:
- Last service date picker
- 8-task maintenance checklist (clean barrel, lubricate, inspect feed, check headspace, and more)
- Timestamped maintenance log with free-form notes
- Full history preserved across sessions

### ⚙️ Accessories Tracker
12 standard accessory checkboxes plus a custom field per firearm — red dot, magnified scope, suppressor, bipod, sling, laser, trigger upgrade, and more.

### 📄 Insurance-Ready Exports

**Single Firearm Report** — open any detail view and tap **Insurance Export** to generate a print-ready HTML document with the firearm's photo, complete spec sheet, purchase date, estimated value, and a generation timestamp. Open in any browser, print to PDF.

**Full Vault Report** — one tap generates a consolidated insurance document covering every firearm in your collection with a vault summary (total count, total estimated value) at the top.

### 💾 Full Backup & Restore
A single JSON export captures everything:
- All firearms with full specifications
- All photos (base64 embedded)
- Range logs, maintenance records, accessories
- AI descriptions
- Your API key and preferences
- Notes and feedback entries

**Restore** on any device — choose Merge (upsert by serial number) or Replace All. Your vault travels with you.

### 🔍 Search, Filter & Sort
Find anything in your collection instantly:

**Filters** — Type · Caliber · Storage Location · Rounds (active filter)

**Sort options:**
- Name A→Z / Z→A
- Make A→Z
- Value: High to Low / Low to High
- Year: Newest / Oldest
- Rounds: Most Fired
- Purchased: Newest / Oldest

### 🗂 Storage Location Tracking
Assign every firearm to a named location — Safe A, Safe B, Vault, Case, Locker, Bedside, Range Bag, Vehicle — and filter your entire inventory by location in a single tap.

---

## The AI Stack

ARMORY connects to [Groq](https://console.groq.com) — the fastest AI inference platform available — using a **free API key** that takes about 60 seconds to obtain.

| Capability | Model Used |
|-----------|-----------|
| Spec research & AI descriptions | `llama-3.3-70b-versatile` |
| Camera identification & vision | `meta-llama/llama-4-scout-17b` |
| Fast fallback (rate limit) | `llama-3.1-8b-instant` |

The app auto-falls back to a faster model if rate limits are hit, and all AI features degrade gracefully without a key — the rest of the app works fully offline.

---

## Privacy Architecture

ARMORY is built on a **local-first, zero-trust** architecture:

- ✅ All firearms data stored in browser localStorage — never on a server
- ✅ Photos stored as base64 on your device
- ✅ API key stored locally — sent only to Groq's API, never to any other endpoint
- ✅ No accounts, no sign-up, no cloud sync
- ✅ Works fully offline after first load
- ✅ Service worker caches all assets for offline use
- ✅ Full JSON export gives you 100% data portability at any time

---

## The Vault Experience

ARMORY presents your collection through three optimized views:

**Grid View** — Full photo cards with brand, model, caliber chips, and value at a glance

**Small Tiles** — Maximum density — see your entire collection at once

**List View** — Horizontal rows with inline spec chips — optimized for long collections

The glassmorphism dark UI — gold accent system, frosted glass cards, neon glow on primary actions — makes every interaction feel premium. Your vault looks as good as it performs.

---

## Feature Summary

| Category | Features |
|----------|----------|
| **Intake** | Manual entry · AI camera scan · AI spec fill · Manufacturer logo picker |
| **Records** | Full spec sheets · Photo gallery · Notes · Purchase date · Storage location |
| **Operations** | Range log · Maintenance records · Accessories tracker |
| **Intelligence** | AI descriptions · Spec research · Camera identification |
| **Vault** | Live value total · Round count · Firearm count · Multi-sort · Multi-filter |
| **Exports** | Single insurance PDF · Full vault PDF · Excel · CSV · JSON backup |
| **Security** | Local-only storage · No accounts · Offline-capable · Full data export |
| **Platform** | PWA — Android · iOS · Windows · macOS · Desktop browser |

---

## About

ARMORY was built by a collector who got tired of the Excel Plateau. What started as a personal utility — a way to bring order to a growing investment — became a platform built on two principles: **utility** and **privacy**.

The technical rigor of a developer. The passion of a collector. The peace of mind of a professional.

*Built on the Lazzaro Standard.*

---

<div align="center">

**ARMORY v3.0** · © 2025 Lazzaro Standard · All data stays on your device

</div>
