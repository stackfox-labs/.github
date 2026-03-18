# StackFox Labs

Backend infrastructure and developer tools for Roblox.

StackFox Labs builds a cohesive ecosystem for developing Roblox games, from backend services to developer tooling and runtime infrastructure, all designed around **Luau**.

---

## StackFox Platform

A Luau-native backend platform for Roblox games.

Track events, store records, and manage your game data through a simple SDK — without running servers or managing infrastructure.

```lua
StackFox.events:track("player_join", {
  userId = tostring(player.UserId),
  username = player.Name,
})

StackFox.records:set("players", userId, {
  coins = 100,
  level = 5,
})
```

* Hosted backend services
* Event tracking and ingestion
* Persistent record storage
* Real-time dashboard
* Zero infrastructure

---

## Developer Tooling

### luau-skills

Agent skills for Luau and Roblox development.

* Improve coding agents (Codex, Claude Code, Cursor)
* Structured knowledge for Luau and Roblox workflows
* Practical, reusable development patterns

---

## Runtime & Ecosystem

### lupe

A modular Luau runtime with installable libraries and native extensions.

* Extensible runtime design
* Compatible with upstream Luau
* Foundation for advanced tooling
