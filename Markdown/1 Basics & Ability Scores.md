#Basics#

A character has some basic values that describe his or her abilities.
The most important ones are description and ability scores.

##Description##

This includes basic,mostly unchanging information like name, age and race.

- Name
- Age
- Gender
- Race
- Appearance
- Morality

##Ability Scores##

Ability Scores are the basic numeric statistics that are referred to by the rules. They covern a characters physical and mental strengths.
Most other statistics are calculated from these.

The abilities are:
- Strength (STR)
- Dexterity (DEX)
- Charisma (CHA)
- Intelligence (INT)
- Condition (CON)

STR and DEX are a characters physical brute force and quickness respectively. CHA and INT fill those roles for mental activities. CON defines the general state and health of the characters body and mind.

The ability scores have numerical values. 0 means no talent, hardly there. 3 is basic human ability. 6 is human paragon/genius ability. Anything from 7 on is absolutely exceptional or superhuman ability.

##Tier and Tokens##

As a character gains experience he or she gains levels. Every 4 Levels the character enters a new Tier. Level 1 characters start at Tier 1.

A character also has several levels of training and expertise in different broad fields. Those fields are the token categories. They are:

- Martial (M)
- Cunning (C)
- Arcane (A)
- Divine (D)
- Psychic (P)

For each category a character can have a number of Tokens.
a Category Level which typically is the number of Tokens in a field the character possesses. From this Level a Bonus can be calculated.

So, for each category a character has Tokens in, he or she has a Token Level and a Token Bonus.

##Character Statistics##

Every Character has some statistics that are very commonly used. 

###Fighting Statistics###

For normal Fighting, there are the following attack and defense statistics:

    Attack Bonus      = Martial Bonus + (STR or DEX)
    Deflection (DEFL) = 10 + (1/2 * Martial Bonus) + DEX
    Surprised DEFL    = 10 + (1/2 * Martial Bonus)

Attack Bonus and DEFL are increased by 1 for each size category smaller than medium and reduced by 1 for each size category larger than medium.

###Ability Defenses###

When a special ability is attacked directly the following defenses are used.

Every ability defense has a base value and a threshold. To fully succeed with an attack, it has to overcome base value + threshold. If the attack only overcomes the base value it is a partial success.

Some defenses count as strong defenses. Those have 1 + the characters TIER added.

    STR defense = 10 + STR (+1 + Tier if strong)
    DEX defense = 10 + DEX (+1 + Tier if strong)
    CHA defense = 10 + CHA (+1 + Tier if strong)
    INT defense = 10 + INT (+1 + Tier if strong)
    Threshold   = CON

STR defense protectets against attacks that target your bodily functions, you stability or your life energies directly (Poison, Shockwaves, Death Magic).

DEX defense protects against massive effects that can't be blocked directly or situations where reflexes are important. (Fire, Falling, Tremors).

CHA defense protects against attacks that try to damage, influence or possess your mind, sanity and soul. (Charm Magic, Symbols, Insanity).

INT defense protects against effects that can be overcome with logic or quick wits and and attacks that try to fool you. (Bluffs, Illusions, Confusion).

###Health, Stamina and Exhaustion###

A character has health points (HP) and stamina (STM).

reduced health discribes the serious injuries and damages a character has taken. Stamina describes the amount of vigor and self-protective capabilities a character has. If a character reaches 0 HP he or she is dead.

Any normal damage is first taken from STM and then from HP. Special direct-HP damage is taken directly from HP.

    HP        = Racial HP + Tier + CON + STR
    Threshold = CON
    STM       = CON + CHA + STM from Tokens

When you take damage or take a Standard Action and have mor HP damage than your HP threshold afterwards, throw a d20 + HP damage over your threshold. At partial effect you gain 1 HP damage. That doesn't trigger a new injury throw. At full effect you gain an exhaustion level.

####Exhaustion####

Exhaustion has several stages that get worse.

1. -1 to all effective Token Bonusses on die throws, all skill checks and ability all defense thresholds (negative threshold means defense penalty) and cannot sprint
2. penalties above raise to -2, -1 maximum spell level and half speed
3. penalties above raise to -3 -2 maximum spell level and can only take one Standard or Move action + Quick Action each round
4. Unconsious
5. Dead

You gain 1 exhaustion level:

- for each fatigue level (max 2)
- when at 0 STM
- when having more HP damage than your HP threshold
- when fully effected by a injury throw.

###Skills###

You have a basic number of skill points. Skill points can be spent to gain training in a skill field or an individual skill.

A skill throw is always keyed to an ability (STR, DEX, ...) and uses this ability as a bonus. A skill you have training in gets further bonusses.

If you have training in a skill you also have training with tools required for uses with this skill.

    Skill Points = 1 + INT

    Skill Bonus  = (1 when field) + (Tier when skill) + (1 when both) + Ability
    Untrained    = Ability
    Only Field   = 1 + Ability
    Only Skill   = Tier + Ability
    Both Traing. = 2 + Tier + Ability

###Other Training###

Apart from skills, you can also have training in

- Weapons and Implements
- Armors and Shields

####Weapon Training####

When you don't have training with a weapon your primary attacks also count as secondary and get the -4 penalty. Also you cannot make opportunity attacks with this weapon.

Typically characters begin with no weapon training and only naturally gain training with Unarmed at Martial Level 10.

Typically the sequence in gaining weapon training is:

2. All simple weapons
3. 2 martial weapons each further training

####Implement Training####

Without training, an implement is only an ordinary object. With training implements give bonusses to spellcasting and manifestation.

Hands wielding implements count as a free hand for the purposes of spellcasting.

- Wand: +1 bonus to arcane spellcasting. (light handedness, like dagger)
- Symbol: +1 to divine spellcasting. (light handedness, like knuckle)
- Staff: +1 to all spellcasting and +1 to one school (heavy handedness, like quarterstaff)
- Conduct: +1 to manifestation (balanced handedness, like club)

####Armor and Shield Training####

Using an armor without training, you get its check penalty to attack rolls and the spell level reduction is increased by 1.

Using a shield without training gives its check penalty to attack rolls.

Armor Training comes for light, medium and heavy armor. Shield training applies to all shields.

###Attunement###

Attunement is your ability to connect with the energies of magic items you wear or use. If an item has several abilities that each need attunement you must spend an attunement slot (or more for some abilities) for each ability you want to function.

Attuning to a collection of magic items needs a short rest. You have a number of attunement slot equal to your Tier.

###Rest and Healing###

A character has a number of resources that get depleted and regained throughout her career.

The resources are restored as followed:

- HP: HP damage heals at a rate of half your CON per long rest. You heal double that amount (full CON) per full day of rest.
- STM: You regain half your maximum STM per short rest and your maximum STM per long rest.
- Spell Slots: Typically used spell slots are regained after a long rest.
- Inspirations: Used Inspirations are regained after a long rest.

Penalties are removed at the following rate:

- Ability Penalties: Ability penalties are removed a 1 point on each ability per long rest and double that rate with each complete day of rest.
- Fatigue: 1 level of fatigue is removed after each short rest. All fatigue is removed after a long rest.