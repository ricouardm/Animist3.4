# Animist3.4

#Description : Mojoware, Daoc Animist Macro Team ( 5 Animist's, 1 Warden, 1 Bard, 1 Druid)- Galladoria

#Team Composition:

- DRIVER: Bafia --> Animist Verdant --> 43 Verdant, 32 Creeping  --> Window name: DRIVER
- HEALER1: Bamenyam --> Bard --> Nuture 50, Regrowth 43 --> Window name:  HEALER1
- HEALER2: Bandjoum --> Druid --> Nurture 42, Regen 33 --> Window name: HEALER2 
- BLOCKBOT: Bamun --> Warden --> Shield 42, Regrowth 33, Nurture 49 --> Window name: BLOCKBOT
- DPS1: Bajwe --> Animist Verdant --> 43 Verdant, 32 Creeping --> Window name: DPS1
- DPS2: Balbamu --> Animist Verdant --> 43 Verdant, 32 Creeping --> Window name: DPS2
- DPS3: Balefali --> Animist Verdant --> 43 Verdant, 32 Creeping --> Window name: DPS3
- DPS4: Bamendjing --> Animist Verdant --> 43 Verdant, 32 Creeping --> Window name: DPS4

## ==REV: 00.12 Date 11.02.2019 11:07==

### File name: ANIMIST 3.4.txt

####Team Composition:
- Fixed some typo's regarding Druid description (aka HEALER2)

####F1:
- Adding Heal Mushroom to the default planting sequence (  2 x DPS, 1 x Heal) of all Animist's ( Driver, DPS1-4)

#### LShift F1:
- Adding a new Mushroom plantation sequence for all Animist's ( Driver, DPS 1-4), they will all plant only one (1) Heal Mushroom

#### LCtrl F1:
- Adding a new Mushroom plantation sequence for DPS 3-4 , each of them will plant 8 DPS Mushroom's ( 16 x DPS mushroom's)

#### F3
- As the Animist reach Level 50, they now have access to pet that can move. Adding the fact that all Animists ( Driver and DPS 1-4) will sent their main PET to the target before they start DPS

#### LShift F3:
-  Adding a new function, all Animists's ( Driver and DPS 1-4) will send their PET at the target and cast a debuff on the target

#### F8:
- Removed Mana, Heal and Endurance song from the default cast sequence
- Healer 2 (DROUD) will cast CON & FOR buff on all team members, As Bard have a self buff he will be excluded 
- Bard to cast Resitance on himself (FIX)
- BLOCKBOT bubble sequence remove  the Wait of 300 ms as not necessary (FIX)
00.12 Date 11.02.2019 11:07
### Oem1:
- Bard cast Endurance, Mana and Heal songs 

#### RShift Oem1:
- Bard cast speed song

#### Oem3:
- This Macro  will invite all chars to the group and accept the invite
- Adding a delay of 200 ms  beetween two invites

#### LShift Oem3:
- This Macro will send an Accept to an invite to a BG, Group. Toons that will accept the invite are : DPS1-4 , HEALER 1-2 & Blockbot

#### RShift Oem3:
- Adding all toons to a BG. To accept  you will need to use LShift Oem3

#### V:
- All toons of the GRoup will RUN








## ==REV: 00.11 Date 21.01.2019 09:24==

### File name: ANIMIST 3.4.txt

####F8 hotkey:
- Removed : Heal , Endurance, Mana songs from Healer1

####F2 hotkey:
- Removed : Heal er's will not start casting Goup heal 1.5 sec after DPS's cast AOE

#### RShift Oem1 hotkey NEW !!:
-the Bard will now cast Endu, Mana and heal song 

## ==REV: 00.10 Date 18.01.2019 17:54==

### Fine name: ANIMIST 3.4.txt

####Oem4 hotkey:
- BUG: Error while loading the file at line 861 : Missing Commande "Package" , added it and works properly



## ==REV: 00.09 Date 17.01.2019 11:36==

### File name: ANIMIST 3.4.txt

####F1 hotkey:
- Correct some typo's to reflect recent changes ( removed different level's of shroom's)

####F2 hotkey:
- Correct some typo's

####F3 hotkey:
- Changed the duration of Wisp 2800 changed to 3100 ms

####F5 hotkey:
- Correct some typo's

####F8 hotkey:
- DPS 1 will cast Add damages on BLOCKBOT
- DPS 2 will cast Add damages on HEALER1
- DPS 3 will cast Add damages on HEALER2

####Minus hotkey:
- DPS 1 will cast Add damages on BLOCKBOT
- DPS 2 will cast Add damages on HEALER1
- DPS 3 will cast Add damages on HEALER2
- Correct some typo's

####Oem7:
- Simplify the  Kill All Turrets, the same command will be send to all DPS's and the Driver instead of 5 entries


## ==REV: 00.08 Date 16.01.2019 16:42==

### File name: ANIMIST 3.4.txt

####Team description:
  - Removed the dual entry for the Driver
  - Correct some typo's

####F3 hotkey:
- Animist will now only cast one wisp and after drain 
- Animist will not send PET to target as this is not possible at low level. This will be updated at later stage
- Update the timer of life drain to reflect the exact timer ( 3100 ms to 2800 ms)
- Correct some typo's

####F8 hotkey:
- Correct some typos
- Removed the self bubble from DPS1-4 and DRIVER

####Minus hotkey:
- Correct some typos
- Removed the self bubble from DPS1-4 and DRIVER

####Oem4 hotkey:
- Break down the PET sequence cast to be able to have PET bubbles not stacked (added a buffer of 200ms between casts)

### File name: ANIMIST KEYBOARD.json
- Removed Key 3 & 5 to free up space and barely used

### File name: ANIMIST KEYBOARD.jpg
- Removed Key 3 & 5 to free up space and barely used
