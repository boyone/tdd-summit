# Tennis Legacy

You task is to implement a tennis scoring program.
Summary of tennis scoring:

1. A game is won by the first player to have won at least four points in total and at least two points more than the opponent.

2. The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "love", "fifteen", "thirty", and "forty" respectively.

3. If at least three points have been scored by each player, and the scores are equal, the score is "deuce".

4. If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "advantage" for the player in the lead.

[source http://en.wikipedia.org/wiki/Tennis#Scoring]

---

## Specification by Example

| Player1 Score | Player2 Score | Game Score      |
| ------------: | ------------: | --------------- |
|             0 |             0 | Love-Love       |
|             1 |             0 | Fifteen-Love    |
|             2 |             0 | Thirty-Love     |
|             3 |             0 | Forty-Love      |
|             4 |             0 | Win-for-Player1 |

| Player1 Score | Player2 Score | Game Score            |
| ------------: | ------------: | --------------------- |
|             0 |             0 | Love-Love             |
|             1 |             0 | Fifteen-Love          |
|             1 |             1 | Thirty-Fifteen        |
|             2 |             1 | Thirty-Fifteen        |
|             2 |             2 | Thirty-Thirty         |
|             2 |             3 | Thirty-Forty          |
|             3 |             3 | Deuce                 |
|             3 |             4 | Advantage-for-Player2 |
|             4 |             4 | Deuce                 |
|             4 |             5 | Advantage-for-Player2 |
|             4 |             6 | Win-for-Player2       |

---

## Rule

1. Clone project from [https://github.com/boyone/tennis](https://github.com/boyone/tennis)

   ```sh
   cd path/to/workspace
   git clone git@github.com:boyone/tennis.git
   ```

2. Implement case by case

3. Stage your changes

   ```sh
   git add <changed files>
   ```

4. Commit the files that you've staged in your local repository.

   ```sh
   git commit -m "Your commit message"
   ```

5. Push the changes in your local repository to GitHub.

   ```sh
   git push
   ```
