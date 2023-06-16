## 4.0 Sword

This is the first of the two main subsystems.

### 4.1 Combat Basics

1. Combat happens in Rounds, and each Round has 3 phases in order:
	- 1st (fast) Party phase
	- Monster phase
	- 2nd (slow) Party phase
2. Start each round by declaring Stance (if you’re using those rules). Then roll Initiative on Dex. If you pass, you get to act before the Monsters in the 1st Party phase, otherwise you act after in the 2nd Party phase.
3. On each Party phase, the protagonists act by hitting, moving etc. Roll attack rolls and work out damage to Monsters.
4. On the Monster phase any Monster that can target and strike at the Party will do so. Roll defence rolls and work out damage to the Harm track.
5. Repeat this until one side quits/flees/is dead etc.

### 4.2 Attacks on Monsters

Roll the attack roll (usually Str). If you get a hit, work out damage by

* taking the number on the d20 die
* subtracting the Monster’s Armour Class
* rolling and adding weapon damage dice

### 4.3 Defences against Monsters

Roll defence (usually Dex). If it’s a miss, take damage:

* roll all the Monster's damage dice per its stat block
* Compare each die to the protagonist's Armour Class
	* If the roll is lower than the worn AC, there's no damage
	* If the roll is up to 2 points higher than AC, mark Fatigue
	* If the roll is 3 or more points higher than AC, mark a Wound

### 4.4 Weapons

All weapons have one or more dice; typically d4 for small weapons, d6 for medium and d8 for large. Where a weapon has more than 1 die (some large weapons, and also Demon weapons) it's possible to attack more than 1 Monster die in a horde.

Monsters have damage dice listed. Where there's more than one die it could be a claw/claw/bite attack, for example, or just a very large or Demon weapon on the monster's side.

### 4.5 Armour

Armour runs on the same Armour Class scale for both Monsters and Protagonists. The absolute limit for most humans is Heavy armour. Monsters can be bigger, tougher, and alien so they're not so limited.

| AC | Example                                                      |
|:---|:-------------------------------------------------------------|
| 0  | Thin clothes (or no clothes)                                 |
| 1  | Thick travelling clothes                                     |
| 2  | Light armour (padding, leather)                              |
| 3  | Medium armour (chain, scale)                                 |
| 4  | Heavy armour (plate)                                         |
| 5  | Very heavy (special training to wear, very limited movement) |
| 6+ | Monsters only                                                |

### 4.6 Harm and Healing

Protagonists have a Harm track of boxes. When you take a hit, tick one box if it's Fatigue and mark a cross if it's a Wound.

In general: the Harm Track is numbered and each box is separate. If Fatigue is healed you wipe away ticks but leave any crosses where they are. New damage will be filled in on the next empty box.

#### Healing

**Fatigue** gets wiped away with rest, starting right after the combat. Half an hour might be enough to wipe out 3 fatigue boxes right there (maybe less if the PCs are on a forced march) and a night's rest should pretty much clear all Fatigue.

**Wounds** need time to heal though, and successful rolls on Con (if you're on your own) or some Doctor skill (if being treated). Note that the Harm Track is numbered and the boxes start at 1 and go up to the character's Con; so when you're trying to clear a wound, you need to make a roll equal to or better than the number on the box.

A PC is allowed one Con roll per night to recover one wound. They don't need to target a specific wound box, they just restore the best result they achieve. Medicines may give some Advantage.

When they're being looked after the chances are better:

1. The doctor may roll more than once per day, depending on resources
2. The doctor may have access to medicine that gives Advantage on the roll.

#### Deep Wounds, Festering Wounds, Incapacity and Death

Mark a Deep Wound with a Star. This needs special treatment to shift. Deep wounds could be gained by a few ways:

1. If the PC has failed 3 healing rolls in a row, one of their wounds may be Deep and need treatment. Make a d20 roll; the wound closest to the rolled number is the one infected.
2. Some Monsters inflict Deep Wounds (but Fatigue as normal). Deep Wounds might be specific to one source (e.g. bite, but not claws).
3. When the Harm Track gets filled, more damage turns Fatigue into Wounds and potentially Wounds into Deep Wounds.

Deep wounds can Fester. If a person continues to fail healing rolls, the Deep Wound spreads to the next Wound down (change the cross to a star).

Should the Harm track get filled up, this happens:

1. Roll a Con save. If you beat the worst wound, you take it in your stride. If you pass, but you don't beat the worst wound, you're briefly out of action but you'll come back in a round or two. If you fail, you're incapacitated.
2. If you're still moving about and taking damage on a full Harm track, start marking off full boxes from the lowest point. Any damage will turn Fatigue into a Wound and a Wound into a Festering Wound. Repeat until you stop getting thumped or you're incapacitated.
3. Speaking of which, if you're incapacitated you need to be stabilised. Either roll Con or the person helping you rolls a relevant roll vs. the worst Wound. Clearing the Wound means you're stable. Success means no change. Failure means you turn another Fatigue box into a Wound. Once you're all Wounds, Con failure probably means death.

### 4.7 Stances

Combat Stances are a way of keeping track of what the party is doing in combat. Pick a Stance at the start of a Combat Round. You can change it every round if you wish.

| Stance | Tactics                                       | Monster Priority | Score |
|:-------|:----------------------------------------------|:-----------------|:------|
| Charge | Move towards enemy and strike                 | High             | Str   |
| Guard  | Move with and defend something                | Medium           | Con   |
| Flank  | Move undetected, get the drop on the enemy    | Low              | Dex   |
| Spot   | Keep your distance and call out opportunities | Low              | Int   |
| Cast   | Do something requiring concentration          | Medium           | Wis   |
| Talk   | Communicate with the other side               | High             | Cha   |

Note the Monster Priority. In a mixed group, where the Monster has choice of a few targets, they will always go at the High priority (visibility) ones first.

#### The Stances explained

When you **Charge** you will always get your chance to swing, even if you failed your Initiative and the Monster hits you with something that incapacitates you. You're going to attract the most anger from the Monsters, and you may get separated unless the rest of the Party comes with you.

When you **Guard** you'll stay close to that place/person/thing and as long as you're guarding, the Monsters will have to go through you to get to them/it. If the Monsters aren't coming to you you may not get to hit them, but any Monster coming into range is fair game.

When you **Flank** you're taking advantage of having not been seen yet. If you scored a hit on Initiative, add that damage to your backstab/sniper shot. Getting into this position before combat is easier than doing the same during combat, and delivering the backstab is likely to draw attention unless you killed your target on the spot (e.g. with a 10+ hit, the Ref might allow you to keep your hidden status), so more likely than not you need to change Stance next round. If you want to hide again, take a round to Spot, and use that time to hide and sneak.

When you **Spot** you're not attacking (but you still defend whenever targeted). You're looking for opportunities. If you call out to an ally you can give them Advantage on a roll (including defence rolls); if you have Initiative, you can do this twice, and if not, just the once. You can also use this time to reposition.

When you **Cast** you may be doing magic, or you might be fiddling with a device, or picking a lock, or rifling through treasure for a certain ring. You're not attacking, but you still get to defend, of course. The Ref may ask for a separate roll while you're doing this, and possibly set a Dice Clock if the task is difficult.

When you **Talk**, you're trying to communicate (impress, taunt, distract, appeal for a truce, etc.). The outcome of this is unpredictable and of course standing in the front and talking makes you a priority to Monsters, who might not be in the mood for talking. But if you think they have some reason they might listen to you, then the effect could end up changing their intentions. If it doesn't work out, you still get to defend (but not attack).

