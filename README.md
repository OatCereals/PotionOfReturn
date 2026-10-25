# Potion of Return

A [7 Days to Die](https://7daystodie.com/) mod inspired by Terraria's Potion of Return.

Drink the potion to snap home to your bed or bedroll, then step on a **Return Pad** to go back to where you were.

**Author:** Oats · **Version:** 1.0.0 · **Game:** 7DTD v3.1–v3.3

---

## How it works

1. Drink a **Potion of Return** while you have a placed bed or bedroll.
2. Your current position is saved and you teleport to your bed/bedroll.
3. You get the **Potion of Return Recall** buff (purple bed icon). While that buff is active, your return point stays saved.
4. After any teleport (potion or pad), you get **Teleport Sickness** for 5 seconds (purple concussion icon with timer). You cannot eat or drink until it wears off.
5. Step on a **Return Pad** (does not require electricity) to teleport back to the saved spot. The recall buff is cleared and the round trip ends.

**Notes**

- Drinking another potion replaces any previous saved return point with your new location.
- No bed or bedroll placed means the potion will not work.

---

## Unlock / crafting

| Item | Crafting skill | Station |
|------|----------------|---------|
| Potion of Return | Food level **51** | Campfire with cooking pot |
| Return Pad | Electrician level **45** | Workbench |

### Recipes

**Potion of Return**

- 1× Boiled Water
- 50× Nitrate Powder
- 1× Honey

**Return Pad**

- 100× Electric Parts
- 10× Mechanical Parts
- 50× Forged Steel
- 5× Stun Baton Repulsor Mod

---

## Where to get it

- Craft it yourself
- Find the potion in medical-style loot
- Buy the potion from traders (medicine stock)

---

## Install

### Multiplayer

**Server-side only.** Put the `PotionOfReturn` folder on the dedicated server. Clients do **not** need the mod folder.

### Singleplayer

Install the mod on the client (same `Mods` folder as usual).

### Requirements

- Official **TFP Harmony** mod (`0_TFP_Harmony`)
- Does **not** require Easy Anti-Cheat to be turned off

### Folder layout

```
Mods/
  0_TFP_Harmony/
  PotionOfReturn/
    ModInfo.xml
    PotionOfReturn.dll
    Config/
```

---

## Compatibility

Built for **7 Days to Die v3.1 through v3.3**.

---

## Credits

Inspired by the Potion of Return from *Terraria*.
