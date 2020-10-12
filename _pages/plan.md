---
title: Plan
permalink: /plan/
toc: true
toc_sticky: true
---



# Brainstorm

### Idea List #1

| Question | Genre | Action |
| :------: | :---: | :----: |
|   ...    |  ...  |  ...   |

*10 - 20 entries.*



### Idea List #2

| Describe a memorable moment (5s) | What excites me? | How is it challenging? (Difficulty tuning) | Features to be implemented | Visual style | Does it fit the scope? |
| :------------------------------: | :--------------: | :----------------------------------------: | :------------------------: | :----------: | :--------------------: |
|               ...                |       ...        |                    ...                     |            ...             |     ...      |          ...           |

*less than 10 entries.*



### Idea List #3

| What does 30s of gameplay looks like? | What are the controls? | How are you going to code the game's rules? | What aspect ratio fits the game the best? | What's the win/failure condition? |
| :-----------------------------------: | :--------------------: | :-----------------------------------------: | :---------------------------------------: | :-------------------------------: |
|                  ...                  |          ...           |                     ...                     |                    ...                    |                ...                |



# Development

## First Playable

Your toy is your foundation, so think of what you can combine and experiment with it.


1. Inputs
2. Core Mechanic
3. Core Interactions
4. Win/Defeat Condition



## Gameplay

1. Mechanics
2. Interactions
3. Progression
4. Tweaking



> Is there anything about feature X which is **distracting** or **broken**?

- **Yes** - Prioritize it.

- **No** - Move on to the next feature.



## Visuals

1. UI
2. Art
   - **Form follows function**
3. Animations



## Bugs

- Game Breaking *//stops game from working*
  - Drop everything, fix immediately
- Annoying *//distracts the player*
  - Fix before moving on to the next feature
- Looks bad *//player will notice*
  - Fix if you get time



1. Reproduction steps
2. What is this step doing
3. Look for
   - Doing wrong thing
   - Doing additional things
   - Not doing anything
4. Fix the code
5. Test



## Content

- Analyze **every** action parameter and experiment with it

- Always have a **minimum** and **maximum** for each challenge

- Let **challenge** define the game's flow

  

## UX Improvement

- See your game as a big **OCR loop** with micro OCR loops inside
  - Objective - Challenge - **Reward**
- Reward **immediately** EVERY positive or intended behavior
- Failures must have a cost
- Feedback tables to help with interactions

|               | SIGN (FORM) | FEEDBACK DURING ACTION | FEEDBACK SUCCESSFUL | FEEDBACK UNSUCCESSFUL |
| :-----------: | :---------: | :--------------------: | :-----------------: | :-------------------: |
|    **UI**     |     ...     |          ...           |         ...         |          ...          |
|    **VFX**    |     ...     |          ...           |         ...         |          ...          |
|   **AUDIO**   |     ...     |          ...           |         ...         |          ...          |
| **ANIMATION** |     ...     |          ...           |         ...         |          ...          |
|  **CAMERA**   |     ...     |          ...           |         ...         |          ...          |



## Extra

- Store page
- Saving systems
- Scene transitions
- Scenery variation
- In-game Tutorial
