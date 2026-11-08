# 🚀 Dookie — Enterprise-Grade Multipurpose Discord Bot

**Dookie** is a modular, high-performance, all-in-one Discord bot built with `discord.py` and SQLite. Designed to serve as a complete alternative to bots like Dyno, Dookie packages 28+ fully integrated cogs ranging from dynamic custom command macros to API-level moderation, voice tracking, economy systems, and automated server tools.

---

## 📌 1. Project Ownership & Credits

* **Bot Owner & Creator:** cika_branko
* **Lead Developer:** cika_branko
* **Architecture:** Python 3.x (`discord.py`), SQLite3 Database Engine, Termux Environment
* **Official Repository:** Managed by cika_branko

### Copyright & Intellectual Property
* All original source code, custom macro parsing logic, cog structural blueprints, and bot branding (logos/assets) for **Dookie** are owned by **cika_branko**.
* Third-party libraries used within this project (such as `discord.py`) remain under their respective open-source licenses.

---

## 🎯 2. What is Dookie For?

Dookie was created to provide communities with a self-contained, enterprise-grade bot that eliminates the need for 10+ different single-purpose bots. Key capabilities include:

* **Hybrid Execution:** Native support for both `#prefix` commands and Discord `/slash` interaction trees.
* **Dyno-Style Macro Engine:** Custom commands supporting `{user}`, `{server}`, `{choose:a;b}`, `{delete}`, `{dm}`, and command chaining `{!}`.
* **Moderation & Enforcement:** Complete API-level kick, ban, unban, purge, lockdown, and slowmode management with automated SQLite case logging.
* **Community Engagement:** Voice XP tracking, message leveling, economy, anonymous confessions, birthdays, reaction roles, and ticket support systems.

---

## ⚖️ 3. Rights & Terms

### 👤 Rights of the Users
When interacting with Dookie or servers using Dookie, users have the right to:
1. **Data Transparency:** Know what data is stored (strictly User IDs, Guild IDs, Channel IDs, and game/XP progress needed for bot functions).
2. **Data Erasure:** Request the removal of their stored SQLite data (such as leveling stats, economy balances, or birthday records) by contacting the bot owner or leaving the server.
3. **Privacy:** Use anonymous features (like `#confess`) with the guarantee that public confession outputs will not reveal their identity.
4. **Fair Use:** Access all features provided by the server administrators without unexpected fees or hidden paywalls.

### 👑 Rights of the Bot Owners & Maintainers
The bot owner (cika_branko) retains the right to:
1. **Access Control:** Restrict, block, or blacklist any user, server, or guild from using Dookie if they violate Discord's Terms of Service or attempt to exploit the bot.
2. **Code Updates & Maintenance:** Modify, update, add, or remove cogs, commands, and database structures at any time without prior notice.
3. **Data Management:** Reset or wipe database records (e.g., global economy resets or test environment wipes) during routine maintenance.
4. **Service Uptime:** Provide the bot on an "as-is" basis without guaranteeing 100% continuous uptime.

---

## 📦 4. Module Breakdown (28 Core Cogs)

| Category | Modules Included |
| :--- | :--- |
| **Administration & Mod** | `modcommands`, `permissions`, `purge`, `lockdown`, `slowmode`, `automod`, `logging` |
| **Customization Engine** | `customcommands`, `tags`, `slash_sync`, `embedder`, `automessage`, `broadcast` |
| **Community & Social** | `confessions`, `birthdays`, `reactionroles`, `tickets`, `starboard`, `welcome`, `verification` |
| **Economy & Activity** | `leveling`, `voicexp`, `economy`, `giveaways`, `polls`, `reminders`, `afk`, `fun`, `stats` |

---

## 📜 5. License & Proprietary Rights

This project is **All Rights Reserved**. **Dookie** is a proprietary, closed-source project owned exclusively by **cika_branko**. Unauthorized copying, modification, distribution, or public hosting of this source code—in whole or in part—is strictly prohibited.
