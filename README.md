# Dejarik OS
#### The Table Top Board Game OS of the not so future.

### Features
- App Store
- SDK for creating apps/games
- Native messaging system that can be incorporated into games
  - Team chat feature
  - Maybe a Discord integration?


### Questions
- Does it need to provide a game engine?
  - Do the games themselves provide their own game engine?

- What are the interactive components?

- What software does TTOS need?
  - Extension builder
  - Messing
  - Game Engine
  - App Store
  - 

- What system resources would a TTOS need?
  - The touch screen Instructable was done on a RaspberryPi

- What is the upper limit of touch points for a display?
  - Seems like 10?
  - Microsoft/3M prototype tables have 50-100, but that is likely years out.

- Can you get object recogintion on a single or two touch points?

- How else can you do object recoginition?
  - PlayTable uses RF, but have 70 antennas in their system. That is a no go for me

- What are the guiding principals of this system?
  - Accessible
    - Should be assembalable with inexpensive off-the-shelf parts.
      - Though also expandable with big graphics PC and big-screen display
  - DIY-able
    - A moderatly technically inclinded person or motivated non-techy should be able
      to get the system up and running
    - Should have minimum components
      - Display, mini-pc, video/power cords, table.
  - Object interaction
    - Playable piece limit?
      - What is Avg number of pieces played on a game board?
        - Cards, tiles, resources etc could be digitized to offset limit.
    - Don't want this to turn into a horizontal video game console (aka [PlayTable])
  - Not a hardware company
    - Off the shelf hardware
    - Software oriented solutions to hardware limitations

- What is MVP feature set?

- How do you make the OS work across many different hardware options?
  - RaspberryPi (do they have enough resources to run this?)
  - mini-PCs
  - Jump drive?






#### Tokens:
Would need to be able to mark pieces on a "type" basis, but also "player" basis

Generic pieces that can be used across many games ex. "Meeple"
initilizatioin of pieces/tokens
  - Game would step though all of it's piece types
    - player would put each type down upon request so it could be registered


#### Limitations

Most commercial capacitive touch screens have a limit of 10 points of contact
- if we use a tri-point system for object identificatioin as per [Instructibles]
  this means you can have no more than 3 pieces on a board. :(
- Would there be a software solution to this issue?
  - Can you "toggle/turn off" part of or all of a screen? Temporarly disable a/three
     touch points?

