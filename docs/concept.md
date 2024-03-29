# Concept Document

*One or two sentences at most that say what the game is and why it’s fun.*

**Genre:** Beat-em-up

**Target audience**: Fantasy and fighting fans age 13 and up (ESRB T)

## Unique Selling Points

This game brings arcade beat-em-up action to the fantasy realm, where you can fight using the superhuman powers of a dragon. Your tail whips and throws send enemies flying farther than any human hands.

## Player Experience and Game POV

*Who is the player? What is the setting? What is the fantasy the game grants the player? What emotions do you want the player to feel? What keeps the player engaged for the duration of their play?*

You play Rose, a coastal village girl in a 16th-17th-century fantasy land. After her first taste of dragon blood, she has begun to transform into a dragon. As Rose, enjoy growing your dragon powers and using them in exciting heroic battles against mobs of villains. Each drink of dragon blood advances Rose's transformation, unlocking new draconic moves.

## Visual and Audio Style

*What is the “look and feel” of the game? How does this support the desired player’s experience? What concept art or reference art can you show to give the feel of the game?*

The aesthetic is colorful pixel fantasy with minor anime and manga influence. The gameplay and interface feel smooth, fast, and impactful.

## Game World Fiction

*Briefly describe the game world and any narrative in player-relevant terms (as presented to the player).*

The game is set on a dragon-shaped chain of islands called the Dragon Isles. At the southern tail end is Rose's village of Dragontail. The King rules from his castle in the city of Dragonheart.

The Dragon Child is the legendary heroine of the Dragon Isles. The legend says a young woman transformed into the Isles' avatar to protect them from an unspecified catastrophe.

## Monetization

*How will the game make money? Premium purchase? F2P? How do you justify this within the design?*

The game will be sold premium on digital stores.

## Platform(s), Technology, and Scope (brief)

*PC or mobile? Table or phone? 2D or 3D? Unity or Javascript? How long to make, and how big a team? How long to first-playable? How long to complete the game? Major risks?*

The game will target PCs first. The graphics will be 2D in order to get a head start with store-bought and Creative Commons assets. The tools are LOVE app framework, Tiled map editor, LibreOffice Calc for data editing, and Github/Gitlab for code repository and build automation.

The team is a single developer as programmer, designer, and producer. Art, music and sound assets will be free, bought, or hired.

## Core Loops

*How do game objects and the player’s actions form loops? Why is this engaging? How does this support player goals? What emergent results do you expect/hope to see? If F2P, where are the monetization points?*

## Objectives and Progression

*How does the player move through the game, literally and figuratively, from tutorial to end? What are their short-term and long-term goals (explicit or implicit)? How do these support the game concept, style, and player-fantasy?*

The object of the game is to have Rose drink from all the dragon blood fountains in the dragon isles and complete her transformation into the dragon child. She is guided by visions of the remaining fountains and an unquenchable thirst for the blood therein. If Rose does not complete the transformation in time, she will die of thirst.

## Game Systems

*What systems are needed to make this game? Which ones are internal (simulation, etc.) and which does the player interact with?*

Player-facing systems

- Fighting physics - striking, grabbing, throwing, slamming into walls or hazards, bouncing between walls after powerful throws
- Fighter condition - health, ability to attack and move
- Player growth - what powers and health upgrades have been gained

Internal systems

- Enemy dispatch - add enemies when player advances to certain points in the level or fulfills some other conditions
- Enemy behavior - decide move and attack based on situation and skill level

## Interactivity

*How are different kinds of interactivity used? (Action/Feedback, ST Cog, LT Cog, Emotional, Social, Cultural) What is the player doing moment-by-moment? How does the player move through the world? How does physics/combat/etc. work? A clear, professional-looking sketch of the primary game UX is helpful.*

Rose of Dragontail is playable with a controller, arcade stick, or keyboard.

Move Rose through the world with direction input. Enemies approach to fight Rose at set locations. Use action buttons to attack the enemies and direction input for grappling and defensive techniques. Bodies can be thrown into breakable objects and hazards to deal additional damage and leave marks on the environment.
