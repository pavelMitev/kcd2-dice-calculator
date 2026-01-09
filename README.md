This is a strategy tool for the Farkle mini-game in Kingdom Come: Deliverance II. It helps you figure out the best dice combinations to use based on the actual math behind the game.

Check it out here: https://kcd2-dice-calculator.vercel.app/

**How it Works (The Math)**
Most guides out there just give you rough averages or "vibes." This tool is deterministic.
When you pick a set of 6 dice, the engine runs through every single possible outcome of a roll—all 46,656 permutations ($6^6$). For every one of those rolls, it calculates the highest possible score you could get according to the game's scoring hierarchy. Because it looks at every single possibility instead of just "guessing" with random samples, the stats you see (Expected Value, Bust Rate, and Hot Dice chance) are mathematically absolute.

**The Joker (Devil's Head)**
The Devil's Head die is unique because it has a Joker on the 1. This tool doesn't just treat it as a random face; it actually solves for the best use of that Joker in every roll. It calculates whether the Joker should finish a straight first (for high guaranteed points) before trying to use it to double a set (like a 4-of-a-kind).

**Features**
The Treasury: A searchable archive of all the dice found in the game.
The Satchel: You can add the specific dice you own in-game to your inventory to see your personal odds.
Regular Die Filler: If you have fewer than 6 special dice, the tool automatically fills the gaps with Regular Dice so the simulation stays accurate.
Mobile Optimized: Designed to be used on your phone while you're actually sitting at the tavern table in-game.

**Disclaimer**
This is a fan-made tool. It is not affiliated with Warhorse Studios or Deep Silver. All game assets and names belong to their respective owners.
