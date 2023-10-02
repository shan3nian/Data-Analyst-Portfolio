# Mobile Games A/B Testing - Cookie Cats
- **Project Goal:**
  - Trying to use A/B test results of Cookie Cats to examine what happens when the first gate in the game was moved from level 30 to level 40. When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

- **Dataset**: *Kaggle*     https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats
  - **Variables**:
    - userid: A unique number that identifies each player.
    - version: Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).
    - sum_gamerounds: the number of game rounds played by the player during the first 14 days after install.
    - retention_1: Did the player come back and play 1 day after installing?
    - retention_7: Did the player come back and play 7 days after installing?
- **Tool**: Python

