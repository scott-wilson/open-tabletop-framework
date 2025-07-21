# Rules

## Basic Rules

1. TODO: Figure out basic rules.

## Definitions

- **Actor**: A character that is either controlled by a player, or controlled by the Game Master.
- **Game Master**: A player that acts as the story teller.

## Challenge Events

Challenge Events are events where an actor's skill is tested. For example, a knight fighting a deadly dragon, or a thief trying to avoid traps in a dark dungeon.

When issuing a challenge, the challenger is not attacking a health pool of a target, but instead they are trying to create or remove opportunities until their target is in a "checkmate" position. This isn't limited to traditional combat, and can include cases such as negotiations, haggling, finding a location, etc.

The events follow the pattern **Challenge**, **Response**, **Resolve**.

### Challenge

The **Challenge** step introduces a problem to be solved. This could be either explicitly defined, or partially defined to hide details from players (to be found out at a later time). For example, a goblin needs to climb a cliff, a warrior is fighting against a wizard, a secret agent is trying to sneak past a guard, etc. See [Challenge Resolution](#challenge-resolution) for more information on how to resolve a challenge.

### Response

The **Response** step is an actor's response to the challenge (the **Responder**). If the goblin needs to climb a cliff, then they might try to climb it or spend some time looking for an easier route. If a warrior is fighting against a wizard, they might try to charge the wizard, or find a way to prevent the wizard from turning them into a charred suit of armor before attacking them. If the secret agent is trying to sneak past the guard, then they might try to pick up a disguise, turn off all the lights, etc.  See [Challenge Resolution](#challenge-resolution) for more information on how to resolve a challenge.

### Resolve

The **Resolve** step will resolve who wins the challenge, by how much, and how by subtracting the **Challenger**'s traits, dice roll, and difficulty modifier from the **Responder**'s traits, dice roll, and difficulty modifier. If there is a tie, then the **Responder** wins the challenge. The results of the challenge are based on the following table:

### Challenge Resolution

When resolving a challenge, the **Challenger** or **Responder** (based on which phase the turn is in) will roll `1d10`. They will then gather the traits that will positively or negatively affect the roll. Traits can be stacked if they both are similar or the same (swordsman and combat veteran), or have some overlap (assassin and surgeon). Finally they roll a `d6` per trait and per trait rank and then either add or subtract those values to the original roll to get the result of the challenge by subtracting the **Responder**'s result from the **Challenger**'s. If the number is positive, then the action is at least partially successful. If the number is equal or negative, then the action has at least partially failed. The larger the difference, the more of a success or failure the result is. See the chart below.

#### Challenge Difficulty Modifiers

When an actor tries to succeed at a challenge, they can either decide to try to make it easier or harder to either make it more likely that they'll succeed, or make the result more effective/affect more targets. For example, if the actor is a sniper, they could sacrifice one or more turns to increase the chance that their shot will hit the target (making the challenge easier). Or they could try to perform a trick shot and hit multiple targets at once, hit a target from a farther range, etc. Each modifier will either add or subtract `d6` to their challenge response depending on how much more easy or difficult the challenge has become.

Actors can also sacrifice their traits to add a `d20` to the roll. Once a trait is sacrificed, then it cannot be used to positively affect a challenge (but can be used to negatively one). The actor will not be able to recover the trait until they've done something significant to recover it. For example, a pacifist priest calls upon their god to smite an enemy, leaving them shaken to their core. They will need to go on a pilgrimage to recover their priesthood trait.

#### Challenge Resolution Table

| Value     | Result         | Example                                                                                                                       | Example                                                                                                                                              |
| --------- | -------------- | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| 16+       | Success, and + | The action is successful, and multiple positive modifiers are applied. A positive modifier is added for every 5 values.       | A dragon breathes fire on a peasant, instantly killing them, setting the field they are in on fire, and destroy the nearby village.                  |
| 11 - 15   | Success, and   | The action is successful, and a positive modifier is applied.                                                                 | A pirate successfully shoots a captain and the captain falls off the ship they're on into the water.                                                 |
| 6 - 10    | Success        | The action is successful, and no other modifiers are applied.                                                                 | A cybernetically enhanced warrior stabs a target with their wrist blades.                                                                            |
| 1 - 5     | Success, but   | The action is successful, but a negative modifier is applied.                                                                 | A martial artist successfully grapples their foe, but the foe manages to land in a punch as well.                                                    |
| 0 - -5    | Fail, but      | The action is not successful, but a positive modifier is applied.                                                             | An assassin tries to stab a target with a poisoned dagger. They just graze the target's skin, poisoning them. But they don't successfully stab them. |
| -6 - -10  | Fail           | The action is not successful, and no other modifiers are applied.                                                             | A cop investigating a cult sees an unknowable being and loses their will to continue.                                                                |
| -11 - -15 | Fail, and      | The action is not successful, and a negative modifier is applied.                                                             | A goblin slips while climbing a cliff and breaks their lucky ceramic pot.                                                                            |
| -16+      | Fail, and +    | The action is not successful, and multiple negative modifiers are applied. A negative modifier is applied for every 5 values. | An adventurer fails to find a trap, setting it off. It immediately poisons them, locks off the exit, and releases the undead in the chamber.         |

## Traits

Traits define all the attributes of an actor. If the actor does not have a specific trait, then it is assumed that they have the trait of the most average entity in the setting. For example, if the setting takes place in a forest full of elves, and the actor has no race trait, then it can be assumed that they're an elf. Traits can be generally positive, negative, neutral, or depending on the context. It is recommended that the Game Master decides on a limit of traits to start a campaign with. Traits can be added or removed during the campaign as a way to "level up", or as a natural result of an action. For example, if a warrior trains with a sword, then they can get a trait that makes them proficient with swords.

Traits can have different levels or ranks depending on how powerful the trait is for a given context. For example, if the actor is a beginner level mechanic, then they wouldn't be as good of a mechanic as a master mechanic that has been working on cars for the past 30 years.
