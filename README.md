# Ninja Duel Game

This project simulates a card-based duel game between ninja units and effects. The game demonstrates object-oriented programming principles using JavaScript classes and includes a simple gameplay scenario.

## Files

- `Unit.js`: Contains the definition of the `Unit` class.
- `Effect.js`: Contains the definition of the `Effect` class.
- `Main.js`: Contains the gameplay logic and demonstrates the interaction between units and effects.

## Classes

### Unit

Represents a ninja unit with attributes for name, cost, power, and resilience.

#### Attributes

- `name`: The name of the unit.
- `cost`: The cost to deploy the unit.
- `power`: The attack power of the unit.
- `resilience`: The resilience (health) of the unit.

#### Methods

- `attack(target)`: Attacks the target unit, reducing its resilience by the attacker's power.

### Effect

Represents an effect card that can modify a unit's attributes.

#### Attributes

- `name`: The name of the effect.
- `cost`: The cost to play the effect.
- `text`: Description of the effect.
- `stat`: The attribute of the unit that the effect modifies.
- `magnitude`: The amount by which the effect modifies the attribute.

#### Methods

- `play(target)`: Applies the effect to the target unit, modifying its attribute by the specified magnitude.

## Gameplay Scenario

The following scenario is played out in `Main.js`:

1. Create an instance of "Red Belt Ninja".
2. Create an instance of "Hard Algorithm" and play it on "Red Belt Ninja".
3. Create an instance of "Black Belt Ninja".
4. Create an instance of "Unhandled Promise Rejection" and play it on "Red Belt Ninja".
5. Create an instance of "Pair Programming" and play it on "Red Belt Ninja".
6. "Red Belt Ninja" uses the attack method on "Black Belt Ninja".
