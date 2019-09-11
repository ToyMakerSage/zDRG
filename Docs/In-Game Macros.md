# In-Game Macros for Button Bloat Reduction
The macros below need to be made in FFXIV for zDRG to be able to correctly control your hotbars.

The syntax for /hotbar is `/hotbar set <Ability Name> <Hotbar> <Hotbar Button>`

You don't have to use the suggested KeyBinds, but be aware that zDRG as of v0.73 expects the following keybinds to lead to the expected macros and you will need to modify the triggers in zDRG's Bloat folder to point them to the correct keybind if you choose to use different keys.

## Vorpal to Full (F2)
```
/micon "Vorpal Thrust"
/hotbar set "Full Thrust" 9 5
```

## Full to F&C (F3)
```
/micon "Full Thrust"
/hotbar set "Fang and Claw" 9 5
```

## FCtoWT//1 (F4)
```
/micon "Fang and Claw"
/hotbar set "Wheeling Thrust" 9 5
```

## Disembowel to CT (F5)
```
/micon Disembowel
/hotbar set "Chaos Thrust" 9 4
```

## CTtoWT (F6)
```
/micon "Chaos Thrust"
/hotbar set "Wheeling Thrust" 9 4
```

## WTtoFC//2 (F7)
```
/micon "Wheeling Thrust"
/hotbar set "Fang and Claw" 9 4
```

## TTReset (F8)
```
/micon "True Thrust"
/hotbar set "Disembowel" 9 4
/hotbar set "Vorpal Thrust" 9 5
/hotbar set "Doom Spike" 9 6
```

## DStoST (F9)
```
/micon "Doom Spike"
/hotbar set "Sonic Thrust" 9 6
```

## STtoCT (F11)
```
/micon "Sonic Thrust"
/hotbar set "Coerthan Torment" 9 6
```

## CTtoDS (F12)
```
/micon "Coerthan Torment"
/hotbar set "Doom Spike" 9 6
```

## Jump -> Mirage Dive (Insert)
```
/micon "Mirage Dive"
/hotbar set "Mirage Dive" 9 8
```

## Mirage Dive -> Jump (Home)
```
/micon "Jump"
/hotbar set "Jump" 9 8
```
