# FrameBuddy

**Your Warframe account on your desktop: what to farm, what to build, what to
sell, and how close you are to the Steel Path.**

FrameBuddy is a Windows app that works alongside
[AlecaFrame](https://www.overwolf.com/app/AlecaFrame). It takes the inventory
AlecaFrame already keeps on your PC and turns it into searchable lists,
progress trackers, a crafting planner and market tools, and it keeps itself up
to date while you play.

---

## What you'll need

- **Windows 10 or 11** (64-bit)
- **[.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)**,
  a free download from Microsoft, if you don't already have it
- **[Overwolf](https://www.overwolf.com/)** with the
  **[AlecaFrame](https://www.overwolf.com/app/AlecaFrame)** app installed
- Play Warframe at least once with AlecaFrame running, so it has your
  inventory to share

## Installing

1. Download the latest **FrameBuddy.Installer.msi** from the
   [Releases page](https://github.com/rfellows-ops/FrameBuddy/releases).
2. Run it and follow the setup steps.
3. Open **FrameBuddy** from the Start Menu or the desktop shortcut.

That's it. Each time you open FrameBuddy it checks for a newer version and
updates itself before starting. If you're offline, it just opens the version
you have.

---

## What it does

### Progress

- **Star Chart.** Every node you've cleared, planet by planet, and how many
  are left before the **Steel Path** unlocks. Sort by "closest to done" to
  find the quickest wins, or group by mission type ("how many Defense nodes
  are left?"). Each remaining node shows its mission type, faction and enemy
  level.
  - **Updates as you play.** When you finish a mission, it appears within
    seconds in **purple** ("cleared this session"). It turns green once
    AlecaFrame catches up.
  - A **live bar** shows the mission you're in, or the last one you won.
  - Counts the same 238 nodes the game does (Zariman included). Open worlds,
    Albrecht's Laboratories, Duviri and Höllvania are listed separately so
    they don't skew the count.
  - Shows **the game's own tally** next to FrameBuddy's, so you can tell at
    a glance that the numbers agree.
- **Mastered.** What you've mastered and what's still to go, for Warframes,
  weapons, companions and Archwing.
- **Collection.** Every Warframe and weapon in the game, sorted by how close
  you are to building it.
- **Intrinsics.** Your Railjack and Drifter intrinsic ranks.

### Crafting & Foundry

- **Crafting: weapons.** A **Keep or Sell** verdict for every weapon, with the
  reason. If a weapon is still needed to build something you haven't mastered
  (Broken War → War, for example), FrameBuddy tells you. You can override the
  verdict and add your own notes.
- **Crafting: Warframes.** Owned and mastered status, what each frame is used
  to build, and the ability it gives the Helminth.
- **Foundry.** What's building and when it's ready, plus every blueprint you
  own.

### Planning

- **Planner.** Pick any Warframe, weapon or other craftable and see everything
  it takes to build, down to the last resource for every part, checked
  against what you already own. You get a "still need" shopping list showing
  where to get each piece: relic drops, mission drops, market prices,
  vendors, and the wiki's recommended farming spots for common resources.
  Prime items show whether they're currently vaulted. Track goals and watch
  them progress as your inventory changes.
- **Arbitration.** The upcoming Arbitration rotation, days ahead, in your
  local time. Filter by reward tier to see only the ones worth logging in for.

### Inventory

- **Dashboard and Player Summary:** credits, platinum, endo, Mastery Rank and
  trades left today, plus your mastery points and how many more you need for
  the next two ranks.
- **Relics:** every relic you own and everything it can drop, with rarity and
  chance.
- **Prime parts:** which item each part belongs to and whether you've already
  mastered it, so spare parts you can sell stand out.
- **Mods:** ranked and unranked, with type, rarity and max rank.
- **Resources:** with type (resource, gem, plant, fish, captura…) and whether
  each can be traded.
- **Sentinels and pets.**

### Market (warframe.market)

- **Market Browser:** live buy and sell orders for any item, with each
  seller's reputation. Jump from a part to its set and back. Pop it out into
  its own window to keep it open next to the rest of the app. Once you sign
  in to warframe.market you can also:
  - **Sell** an item: pick the price, quantity and rank, check the summary,
    then post.
  - **Set your status** to Online in game, Online or Invisible. FrameBuddy
    keeps it while it's open, so buyers can find you.
  - **Give a seller reputation** (opens their warframe.market profile).
- **My Orders:** all your warframe.market orders, with the cheapest other
  seller next to each so you can see when you've been undercut. Change the
  price or quantity, hide or show an order (or all of them at once), or
  remove it. When you sell something in a trade, FrameBuddy marks the order
  sold for you, including sets once every part has been traded.
- **Wishlist:** keep a list of things you want to buy.
  - **Group items by goal**, such as a weapon, a Warframe or a mod build,
    and show one goal at a time with its remaining cost. A mod you need for
    several builds can belong to all of them.
  - Add things you can't buy too: tick **Include items not on
    warframe.market** and they go on as **Farm** items.
  - **Fetch prices** gets the cheapest live in-game sellers.
  - **Copy whisper** puts a ready-to-paste message for the cheapest seller on
    your clipboard.
  - Items you can't use yet are flagged **Needs MR 14** (or whatever rank
    they need).
  - From the Planner, add everything still missing for an item in one go.
    Parts you can only farm are added as **Farm** reminders, with how many
    you still need.
  - See **which relics drop the item**, and whether you already own any to
    crack.
  - Items tick themselves off as **Acquired** once they're in your inventory.
    Click a row to see exactly what you have: each mod copy by rank, or each
    part of a set.
  - Add items from the Wishlist page, by right-clicking almost anything in
    FrameBuddy, or straight from a Planner shopping list.
- **Sell Order Ranges:** the price range you could realistically list an item
  at right now.
- **Average Prices:** typical prices for mods, arcanes and sets, to help you
  decide whether to buy or farm.
- **Market History:** 90 days of trading, ranked by what actually sells, with
  a price chart for each item.

### Everywhere

- **Keeps itself up to date.** Whenever AlecaFrame syncs, FrameBuddy refreshes
  in the background. There's no loading screen, and you stay where you were.
- **Search, sort and filter** every list.
- **Right-click any item** to look it up on the Warframe wiki or in the Market
  Browser, add it to your Wishlist, or copy it.
- **Documentation:** built-in guides (getting started, Archon Hunts,
  syndicates, farming, builds) plus your own notes.
- **Dark and Light themes.**

---

## Good to know

**Why is my data a bit behind?**
FrameBuddy gets your inventory from AlecaFrame, which saves it at its own
pace. The status box at the top left of FrameBuddy shows how old the data is.
If it's been a while, opening the AlecaFrame overlay or going back to your
orbiter usually prompts a sync. The Star Chart doesn't wait: missions you win
show up straight away from the game itself.

**A new Warframe or item is missing.**
Item names and recipes come from AlecaFrame's game database. Brand-new items
appear once AlecaFrame updates it, usually within a few days of a game update.

**What does purple mean on the Star Chart?**
You cleared that node this session and the game confirmed it, but AlecaFrame
hasn't caught up yet. It turns green on AlecaFrame's next sync.

## Privacy

**Your inventory never leaves your PC.** FrameBuddy reads it from your own
computer and doesn't upload it anywhere. It only goes online for:

| Service | Used for |
|---|---|
| warframe.market | Market pages, the Wishlist and Planner prices. Signing in is optional; your login goes only to warframe.market and is stored securely on your PC. |
| browse.wf | The Arbitration schedule, and crafting recipes for the Planner (downloaded about once a week) |
| GitHub | Checking for FrameBuddy updates |
| Warframe wiki / Google | Only when you choose "Open in wiki" or "Keep or sell?" |

---

*FrameBuddy is a fan-made tool and isn't affiliated with Digital Extremes,
Overwolf or AlecaFrame.*
