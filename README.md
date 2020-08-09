# Hyper Sonic for Sonic Battle

Hyper Sonic is a work-in-progress demo patch for Sonic Battle (US) demonstrating SBP files and their capabilities. It also uses SBHS.

It replaces Sonic with Hyper Sonic who has various increased stats and similar.

It's made with sprites that are made by shadow_91 and Joe TE with ripped sprites by Nate The Hedgehog.

Due to current circumstances (ie I haven't asked them whether I'm able to distribute the sprites yet) the sheet is not included in the repository. However, you can see the frames below and that can be used to recreate the sheet.

Without sprites, you'll encounter *a lot* of empty frames (As seen under original sprite, those gaps *are not mistakes, they are sprites not present in the original game.*).

## Special thanks

I'd like to thank the following for making this possible:

- Spritework

    - Hyper Sonic spritesheet

        - shadow_91 (Hyper Sonic sprites)

        - Joe TE (Super Sonic sprites)

        - Nate The Hedgehog (Original Sonic sprites, unused)

- Hacking scene

    - Phase - Started the hacking project 3+ years ago now! Created SBHS and SBRX!

    - Glimmer - Found metric tons (Almost all of it) of the data needed to make this happen!

    - Battle Highway - Motivating and supporting the animation data reverse engineering project!

        - Lsarereal

        - Nitespeed

        - Jase3300

        - Lofi Girl

- And you!

## Animations

- [x] - Idle

- [x] - Run startup

- [x] - Run

- [x] - Run stop

- [ ] - Dash

- [x] - Run turn around

- [x] - Stand turn around

- [ ] - Falling

- [ ] - Jumping

- [ ] - Landing

- [ ] - Air dash

- [ ] - Standard combo 1

- [ ] - Standard combo 2

- [ ] - Standard combo 3

- [ ] - Heavy attack

- [ ] - Upper attack

- [ ] - Dash attack

- [ ] - Pursuit animation

- [ ] - Pursuit attack

- [ ] - Unknown Pursuit attack variant

- [ ] - Air attack

- [ ] - Shot left/right

- [ ] - Unknown cut to a fall 1

- [ ] - Unknown cut to a fall 2

- [ ] - More left/right shot (Guess is ending of it due to the many many looped ball animations?)

- [ ] - ?? (53B20)

- [ ] - ?? (53B2C) - These are probably proxies or something for moves that end on the same thing so they can change it easier?

- [ ] - Power attack throw

- [ ] - Shot down

- [ ] - Idle redirect? (53C98)

- [ ] - Air trap

- [ ] - Possibly to do with the down shot?

- [ ] - Possibly to do with the up shot?

- [ ] - Ground trap

- [ ] - ?? (53EA0)

- [ ] - ?? (53EB4)

- [ ] - This seems to be the actual air trap?

- [ ] - ?? (53F34)

- [ ] - Idle? (53F48)

- [ ] - Getting hit

- [ ] - Flung back

- [ ] - Knocked into the air

- [ ] - Same again

- [ ] - Related to getting hit apparently?

- [ ] - Again?

- [ ] - Getting back up

- [ ] - Again?

- [ ] - Fall on the ground from air

- [ ] - Back up from falling from the air

- [ ] - Getting knocked into the air??

- [ ] - Getting flung back?

- [ ] - ?? (54590)

- [ ] - Knocked into the air then falling?

- [ ] - Getting hit normally then getting back?

- [ ] - Knocked into the air (AGAIN???)

- [ ] - Getting back up (AGAIN?)

- [ ] - Jump back then go idle

- [ ] - Actually go back on feet

- [ ] - First two frames of getting back

- [ ] - GET BACK AGAIN?

- [ ] - Shield stun

- [ ] - Healing startup

- [ ] - Healing loop

- [ ] - Healing end

- [ ] - Wall jump

- [ ] - First two frames of being knocked into the air, a ton of times

- [ ] - Landing and dying

- [ ] - ?? (549F8)

- [ ] - Respawn icon

## Frames

| ID |Comment|SBHS/SBRX Column (X)|SBHS/SBRX Row (Y)|Original sprite|
|:--:|:------|:------------------:|:---------------:|:--------------|
|``00``| Stand 1 | 1 | 1 | Stand 1
|``01``| Stand 2 | 1 | 2 | Stand 2
|``02``| Stand 3 | 1 | 3 | Stand 3
|``03``| Stand 4 | 1 | 4 | Stand 4
|``04``| Stand 5 | 1 | 5 | Stand 5
|``05``| Stand 6 | 1 | 6 | Stand 6
|``06``| Run Transition 1 | 1 | 7 | 
|``07``| Run Transition 2 | 1 | 8 |
|``08``| Run 1 | 2 | 1 | Run start up
|``09``| Run 2 | 2 | 2 |
|``0A``| Run 3 | 2 | 3 |
|``0B``| Run 4 | 2 | 4 |
|``0C``| Run 5 | 3 | 1 | Run 1
|``0D``| Run 6 | 3 | 2 | Run 2
|``0E``| Run 7 | 3 | 3 | Run 3
|``0F``| Run 8 | 3 | 4 | Run 4
|``10``| Dash 1 | 3 | 5 | Run 5
|``11``| Dash 2 | 3 | 6 | Run 6
|``12``| Dash 3 | 3 | 7 | Run 7
|``13``| Dash 4 | 3 | 8 | Run 8
|``14``| Dash 5 (Empty)| 4 | 1 | Stop (Run) 1
|``15``| Dash 6 | 4 | 2 | Stop (Run) 2
|``16``| Dash 7 | 4 | 3 | Stop (Run) 3
|``17``| Dash 8 | 4 | 4 | Stop (Run) 4
|``18``| Jump 1 | 5 | 1 | Dash 1
|``19``| Jump 2 | 5 | 2 | Dash 2
|``1A``| Jump 3 | 5 | 3 | Dash 3
|``1B``| Stall | 5 | 4 | Dash 4
|``1C``| Fall 1 | 5 | 5 | Dash 5
|``1D``| Fall 2 | 5 | 6 | Dash 6
|``1E``| Fall 3 | 5 | 7 | Dash 7
|``1F``| Air attack 1 | 5 | 8 |
|``20``| Air attack 2 | 6 | 1 | Turn (Stand) 1
|``21``| Air attack 3 | 6 | 2 | Turn (Stand) 2
|``22``| Air attack 4 | 6 | 3 | Turn (Stand) 3
|``23``| Air attack 5 | 6 | 4 | 
|``24``| Air attack 6 | 7 | 1 | Turn (Run) 1
|``25``| Air attack 7 | 7 | 2 | Turn (Run) 2
|``26``| Air attack 8 | 7 | 3 | Turn (Run) 3
|``27``| Air attack 9 | 7 | 4 | Turn (Run) 4
|``28``| Combo 1 - 1 |
|``29``| Combo 1 - 2 |
|``2A``| Combo 1 - 3 |
|``2B``| Combo 1 - 4 |
|``2C``| Combo 1 - 5 |
|``2D``| Combo 2 - 1 |
|``2E``| Combo 2 - 2 |
|``2F``| Combo 2 - 3 |
|``30``| Combo 2 - 4 |
|``31``| Combo 2 - 5 |
|``32``| Combo 2 - 6 |
|``33``| Combo 3 - 1 |
|``34``| Combo 3 - 2 |
|``35``| Combo 3 - 3 |
|``36``| Combo 3 - 4 |
|``37``| Combo 3 - 5 |
|``38``| Combo 3 - 6 |
|``39``| Combo 3 - 7 |
|``3A``| Combo 3 - 8 |