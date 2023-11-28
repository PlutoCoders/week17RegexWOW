# Explaining Regex for Emails

If you've ever used cheatcodes in videogames to look for stuff or access stuff, the concept is pretty similar to that of a Regex.

**What is Regex?**
 - Regex is short for regular expression, which allows users like us navigate user input and validate for stuff.
 - It's like a set of codes that helps you hunt down specific stuff in a huge pile of text.
 - It's got these cool symbols and rules, like secret sauce for finding things. You can hunt for patterns or exact words, kinda like seeking out Easter eggs in video games.

**Why is it useful?**
 - This is useful because its a much simpler, shorter, and more efficient way of validating and searching through sets of strings and inputs manually.
 - You can also track down things (text/input) that follow certain rules which you can set the parameters for.

# Link
Link: https://github.com/PlutoCoders/week17RegexWOW
- [Note](#note)

## Summary

As someone who loves video games, I will provide some quick metaphors to help explain Regex.

A regular expression is your ultimate cheat code in a video game. It's like having a bunch of codes and hints that help you navigate through the game world to find gear, missions, or easter eggs.

The regex i'm using is for **validating emails**, which checks to see if the user input matches the standard structure of an email.
This is useful because you don't want users to input emails that don't even match any kind of email structure, especially if they had a typo.
This will allow the user correct their mistake and input something valid.
Note: This does NOT check if the email itself is a valid email that the user can also confirm (through a code or link sent to the email).
This code simply makes sure that the input matches standard email structure.

Here is an **example of a basic emailRegex code.**
let emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

Please refer to this example code as you go through the contents if you need to. Some snippets of email rejex will also be provided below.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
    Imagine that the componenets of your regex expression was like that of a video game character who is a wizard, and they are powerful symbols for special spells.
    Each component is necessary to build the structure of the Regex spell, to get it to work, and to specify what the spell does. 
    
### Anchors
    There are two anchors in a Regex.
    The first is the beginning or start anchor, which marks the start of the input string and begins the validation from this point
    The second is the ending anchor, which marks the end of the input string, and all validation occurs until and up to that final point of string.

    An **example of the start** is: ^ 
     The arrow ^ is your starting point. It's like a marker that tells the spell to begin searching right from the beginning of the level.
    An **example of the end** is: $
    The dollar $ is like your destination. It tells the spell to keep searching until it reaches the very end of the level.

### Quantifiers

### Grouping Constructs
 The parentheses () are like grouping items together. They're a way to treat multiple items as one big treasure, making the spell's search more focused.

### Bracket Expressions
 The square brackets [] act like specific quests or challenges you set for the spell. It's like telling it to only search for red potions or green shields.

### Character Classes
 The dot . is like a spell that says, "Hey, find anything here!" It's not picky, just wants to discover any treasure or item in that spot.
 The backslash \, which is like your decoder ring, helping the spell understand other special symbols or rules.
 
### The OR Operator
 Although we don't use the Or operator in our specific email regex, this is what it does:
 | is your "or" option. It’s like saying, "Find this treasure or that one."

### Flags

### Character Escapes

### Sources
These are the various resources I used to learn about Regex
- https://www.abstractapi.com/tools/email-regex-guide
- https://www.variables.sh/what-is-regex/
### Youtube video resource links below
- FireShip
- - https://youtu.be/sXQxhojSdZM?si=TllHtMPSlYjkPv9O
- Crack Concepts
- - https://youtu.be/9RksQ5YT7FM?feature=shared
- Net Ninja
- - https://youtu.be/QxjAOSUQjP0?feature=shared
- Simplilearn
- - https://youtu.be/nRHCoOVSu5k?feature=shared




## Author
https://github.com/PlutoCoders?tab=repositories

### note
- I tried to make a gist setup, but kept having issues with pushing my changes to to it
- gist link here: (not updated) 
https://gist.github.com/PlutoCoders/ec179105a4e9f34fe23f1e2c3840bc65
