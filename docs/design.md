## Concept Statement
In one or two sentences (“your game in a tweet,” or “a few words that create a question”) describe the most important aspects of your game. What is its theme and setting? What makes the game fun? How many players are there? Is it a quick pick-up game or a huge epic? Why would someone want to play the game?

Don’t try to cram too much information into a quick statement, but don’t leave out vital aspects of your game either. This can be a tough balancing act. Expect to spend some time iterating and
polishing this.

## Genre

While genre statements about the gameplay (“this is a bullet-hell platformer”) are helpful to calibrate what the game is and isn’t, avoid vague statements that don’t actually inform the reader (“this is a Castlevania-like game”) and that may hide lazy thinking about the details of the game’s design (if it’s “a Castlevania-like game” what exactly does that mean for your game?).

Note that single-genre games are often less interesting as the space has likely been well-explored. Genre hybrids or combinations can create interesting new angles on existing gameplay, but beware of a “something for everyone” design that contains multiple genres, as these often end up being a mishmash that’s fun for no one.

## Target Audience

Who is the target player for this game? What other games might they have played? What is their age range or other relevant interests or attributes? What is the desired ESRB rating?

## Concept Paragraph and Unique Selling Points

Expanding on the Concept Statement, provide the reader with an overview of the gameplay. Briefly cover the game’s core loops, player progression, setting, look and feel, and any other aspects that are necessary to understand the core appeal of the game.

In particular, highlight your game’s unique selling points (USPs): what are the things that makes your game fresh, intriguing, new, and worth someone’s time? Your game’s USPs must be clearly understood by you and anyone who reads the design docs. If for some reason you can’t state these clearly, or if they don’t feel compelling, this is a sign that you need to rethink or refocus your design. By reading your game’s USPs, a player (who isn’t you!) can see why they would want to play your game instead of all the others like it that already exist.

A link to a current prototype, or even a video of a prototype, goes here once one exists.

## Player Experience

Who is the player in the game? What is the setting? How long does the game last? What is the fantasy or aspiration the game grants the player? What emotions does the player feel by playing the game? What are the major phases of the player’s experience in the game? (This section can link to “Player Objectives and Progression” and leave most of the detail to that part of the design.)

## Key Moments

As part of the player experience, and to help others understand the design, briefly discuss a few “key moments” in the game. Typical examples include an initial positive experience in the first 1-5 minutes of the game; key struggles that must be overcome; and major victory, achievement, or resolution points the player experiences as part of their arc through the game.

## Art, sound and music

This section contains high-level information and examples about the visual and auditory style for the game, as well as links to more specific information.

The high-level information here includes reference and concept art (and where possible, music) to give the reader an idea of the visual style and tone for the game. Reference art may be taken from movies, books, other games, etc., so long as it is not used in the game in any way. Concept art (if any) must be original to the game. This art gives the reader a clear idea of the environments, characters, opponents, objects, major locations, key events, user interface, etc. in the game.

A separated (linked) doc, usually in the form of a spreadsheet, delineates all known art and sound assets that are needed for the game. This includes all user interface assets, animations,
environments, characters, etc, in complete detail.

## Current Target Platform (and any system requirements)

What is the first or current platform for the game – PC, web, tablet, phone, or something else?
Keep this to the current target platform; leave off any “future” desired platforms.

## Competition

What games are similar from the player’s point of view, or would compete directly with your game? Show their name, release date, any revenue and budget information you can find, and a brief description of each. Also include a brief description of what sets your game apart.

Fight'n'Rage (9/9/2017)

TMNT: Shredder's Revenge (6/16/2022)

River City Girls (9/5/2019) 

River City Girls 2 (12/14/2022)

Fallen City Brawl (upcoming)

## Monetization

If the game is “free to play” or has in-game purchases, these need to be wholly integrated with the rest of the design. This section provides an overview of the monetization philosophy and the major systems. It is heavily linked with the systems and features section.

## Links to Detailed Sections

From the main page, the reader must be able to easily find the detailed information they want by following links to the following detailed sections. These appear separately, as on their own web pages or in their own chapters.

## Player objectives and progression

-   Who is the player in the game?
-   Synopsis of what the player knows when the game starts, and any following in-game narrative
-   Player’s primary goals and how they progress to them, including which parts are linear
or based on player choices
-   Moment-by-moment gameplay (with links to UI section)
-   core loops and outer loops
-   reference back to Key Moments

## Game world
-   Backstory overview – important elements of the world fiction that set the stage for the
game, but do not directly affect the gameplay; include Link to full world fiction
-   World organization: MVP levels, locations, zones, chapters – including introductory or tutorial areas
-   Game world physics: running, flying, falling, etc., anything of note for the design
-   How does the player move through the game in terms of locations, chapters, etc.
-   Easter Eggs planned, if any

## User Interface
-   Specifics of all needed control schemes (selection, activation, radial or context menu use, tapping, dragging, etc.), ensuring that these are consistent across the game
-   Screen flow mockups: each screen/menu in full functional detail (wireframe, no art), showing the player’s flow through all aspects of the game.
-   Mockups for on-screen controls (with links to individual features and systems)
-   Help system details
-   Game options: audio, visual, game save, etc.

## MVP Systems and Features

-   All major features such as character creation, crafting, combat, dialog, etc., including areas for monetization (if any), and specific puzzles or similar
    -   Intent, the “why” behind the feature
    -   The moment-by-moment gameplay for each feature or system
    -   The monetization aspects of each system or feature (if applicable)
    -   Lots of pictures and diagrams – give the reader the feel for the feature or system
    -   Links to technical docs for programmer consumption
        -   Math, data structures, format of external data docs
        -   Naming schemes for external directories and files
    -   Break down into Epics and User Stories for implementation
-   Include a description of the UI for each (with links back to the main UI section)

## Game Objects
-   Listing of all NPCs and monsters, including

    -   NPC backstory, narrative, dialog (links to specific dialog data files)
    -   Attributes, attacks, special powers
-   Game objects
    -   Attributes and their values/ranges
    -   Behaviors
-   Link to external spreadsheet containing each object’s data and attribute information

## Localization
-   Description of the initial localization plan: English-only, EFIGS, or other.
-   Technical description of localization syntax for strings
-   Technical description for localization string name conventions
-   Link to external localization string files

## Tools

A description of tools needed for designers, programmers, and others to create the game. This does not include standard word-processing or program editors, but focuses on tools such as:
-   World creation and layout
-   Object definition
-   Missions/quests
-   Others as needed to implement the game

## Technical documentation
-   Major technical areas and risks
-   Target hardware and specific requirements/assumptions
-   Infrastructure
    -   directory structure and file naming conventions
    -   data file format
-   Server, client, and network architecture (as needed)
-   Artificial intelligence and other autonomous/procedural systems
    -   Procedural world creation
    -   Pathfinding
    -   Economy
-   Technical (programming doc for each major feature or system, linked to the design doc for each above. These docs are for programmers, and focus on implementation details rather than the design itself or its rationale.
-   Game cheats for testing

## Ideas and Expansions
Non-MVP feature ideas for future expansion are kept here.

## Unresolved Questions
As questions and concerns arise, they are listed here. When resolved, the question or concern is not deleted, but is moved to a “Resolved” section along with a link to the document that describes the design that answers the concern.

## Prototypes
Links to prototypes not already referenced, if any, are here.