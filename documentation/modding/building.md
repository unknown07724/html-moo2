# Building Your First Mod

it's pretty easy to use JSON/JSON5 so we're going to give you a bit of a crash course into it.

## The Crash Course Of JSON (Javascript Object Notation)

### value types

JSON has different value types or

* strings

```json
"string": "hello world",
```

* numbers

```json
"string": 0,
```

* objects

```json
"object": {"Nested value": "hello"}
```

* arrays

```json
"array": [0,1,2,3,"..."]
```

### rules

usually for value and key pairs that aren't the last have to have a comma afterwards Therefore,

This isn't legal:

```json
"username": "developer001" "creation-date": "1-1-2000 9:00 AM CMT"
```

This is legal:

```json
"username": "developer001",
"creation-date": "1-1-2000 9:00 AM CMT"
```

# Adding a race
a race in the JSON is a big object with multiple smaller objects for organization
Their names are in the race object.

## Images
the portrait is the first thing in this object, what it does is set up the portrait, then there are the colony icons/symbols, aka there are workers, farmers
and researchers and also the military units and special units, their names tell you what they are.

## Diplomacy
despite being in the images object due to a mistake, it is a distinct object. there are only 2 things in here, theme is the theme played during diplomacy and animation is the animation in the middle of diplomacy.

## Names 
Names are for Leaders, Ships and Home star system. 
we have some handy placeholders, # is a random number, (#) is a random number converted to roman numerals and @ is a random latin/english letter.

## Traits
Traits are special bonuses and debuffs for a race, there is special for stuff like charismatic and creative
debuffs and buffs for ship combat, colony stuff and monetary gain.

## Personality
Personality determine behavior, aggression determines whether a race will literally never declare war or declare war for no reason, expansive determines whether a species stays on it's homeworld for the entire game or tries to expand as quickly as possible

## next
(Learning to add buildings)[buildings.md]
