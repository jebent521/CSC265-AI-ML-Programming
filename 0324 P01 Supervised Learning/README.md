# P01 Supervised Learning

**Goal 1:** Discover and quantify what drives user engagement. Use an equation that can predict it.

- [x] Define what you mean by user engagement and how you will measure it.
- [x] Explore the data to find out what features of the NPCs and/or interactions drive user engagement.
- [x] Engineer new features to define user engagement and/or to help you find out what drives it.
- [x] Use one of the models discussed in class to find out what drives user engagement and to predict it.

**Goal 2:** Make a recommendation for how NPCs could be improved in the game for the coming patch.

- [x] Define what drives user engagement based on the ML model.
- [x] Explore differences between old and seasonal NPCs.
- [x] Recommend updates to old NPCs.

## Datasets

- `interactions` contains data we'll examine. One user interaction per row.
- `oldNPCs` contains stats for current NPCs.
- `seasonalNPCs` contains stats for experimental NPCs.

## Columns

| Column                      | Definition                                                                                                                                                                                                                                                                                                       |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NPC ID                      | Unique identifier for each non-player character (NPC).                                                                                                                                                                                                                                                           |
| NPC friendliness            | The friendlier NPCs will give the player access to quests and trade items immediately or with minimal conversation. The less friendly NPCs will give the player access to quests and trade items only after a conversation, where the player establishes trust and obtains knowledge about the lore of the game. |
| NPC item value              | Value of the items the NPC offers with respect to player level.                                                                                                                                                                                                                                                  |
| NPC quest value             | Value of the quests the NPC offers with respect to player level.                                                                                                                                                                                                                                                 |
| NPC gender                  | The gender assigned to the NPC in-game.                                                                                                                                                                                                                                                                          |
| NPC class                   | The NPC’s role or character type (game-world class).                                                                                                                                                                                                                                                             |
| NPC area level              | The difficulty level of the area where the NPC is located.                                                                                                                                                                                                                                                       |
| User ID                     | Unique identifier for each player.                                                                                                                                                                                                                                                                               |
| User level                  | The player character level in the game.                                                                                                                                                                                                                                                                          |
| User class                  | The player character type or class.                                                                                                                                                                                                                                                                              |
| Interaction length          | How long the player’s interaction with the NPC lasted in arbitrary time units.                                                                                                                                                                                                                                   |
| Interaction text exchanges  | The number of dialogue exchanges or conversational turns between the player and the NPC.                                                                                                                                                                                                                         |
| Interaction quests acquired | The number of quests the player obtained from that NPC during the interaction.                                                                                                                                                                                                                                   |
| Interaction transactions    | The number of item-buying, selling, or trading transactions completed during the interaction.                                                                                                                                                                                                                    |

## Supervised Learning Methods

- Linear regression
  - Simple
  - Multiple
- Polynomial
- Logistic
