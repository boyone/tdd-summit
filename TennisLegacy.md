# Tennis

You task is to implement a tennis scoring program.
Summary of tennis scoring:

1. A game is won by the first player to have won at least four points in total and at least two points more than the opponent.

2. The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "love", "fifteen", "thirty", and "forty" respectively.

3. If at least three points have been scored by each player, and the scores are equal, the score is "deuce".

4. If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "advantage" for the player in the lead.

[source http://en.wikipedia.org/wiki/Tennis#Scoring]

---

## Rule

| ชื่อ    | username   | repository      | ssh                                           |
| ------- | ---------- | --------------- | --------------------------------------------- |
| นัท     | <username> | tennis-legacy01 | git@github.com:<username>/tennis-legacy01.git |
| ต๋า     | <username> | tennis-legacy02 | git@github.com:<username>/tennis-legacy02.git |
| ต้น     | <username> | tennis-legacy03 | git@github.com:<username>/tennis-legacy03.git |
| ต้าร์   | <username> | tennis-legacy04 | git@github.com:<username>/tennis-legacy04.git |
| ตัวเล็ก | <username> | tennis-legacy05 | git@github.com:<username>/tennis-legacy05.git |
| อาร์ท   | <username> | tennis-legacy06 | git@github.com:<username>/tennis-legacy06.git |
| เอ      | <username> | tennis-legacy07 | git@github.com:<username>/tennis-legacy07.git |
| วิตร    | <username> | tennis-legacy08 | git@github.com:<username>/tennis-legacy08.git |
| ตั้ม    | <username> | tennis-legacy09 | git@github.com:<username>/tennis-legacy09.git |
| อาร์ม   | <username> | tennis-legacy10 | git@github.com:<username>/tennis-legacy10.git |
| บูม     | <username> | tennis-legacy11 | git@github.com:<username>/tennis-legacy11.git |
| ไผ่     | <username> | tennis-legacy12 | git@github.com:<username>/tennis-legacy12.git |
| ฟลุ๊ค   | <username> | tennis-legacy13 | git@github.com:<username>/tennis-legacy13.git |
| โอม     | <username> | tennis-legacy14 | git@github.com:<username>/tennis-legacy14.git |
| เอ      | <username> | tennis-legacy15 | git@github.com:<username>/tennis-legacy15.git |

1. [Create a Repo](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) call tennis-legacy[xx]

2. Create project on local machine

   create directory call **_workspace_**

   > ![maven-project00](./images/maven-project00.png)  
   > ![maven-project01](./images/maven-project01.png)  
   > ![maven-project02](./images/maven-project02.png)  
   > ![maven-project03](./images/maven-project03.png)  
   > ![maven-project04](./images/maven-project04.png)  
   > ![maven-project05](./images/maven-project05.png)

3. Go To project

   ```sh
   cd path/to/tennis-legacy19
   ```

4. Initialize the local directory as a Git repository.

   ```sh
   git init -b main
   ```

5. Add the files in your new local repository.

   ```sh
   git add .
   ```

6. Commit the files that you've staged in your local repository.

   ```sh
   git commit -m "Init project"
   ```

7. Add remote repository.

   ```sh
   git remote add origin git@github.com:<username>/tennis-legacy[xx].git
   ```

8. Verifies the new remote URL

   ```sh
   git remote -v
   ```

9. Push the changes in your local repository to GitHub.

   ```sh
   git push origin main
   ```

   or

   > use this command for the first time

   ```sh
   git push -u origin main
   ```

   > then the next time when you push can use only

   ```sh
   git push
   ```

10. Implement 15 minutes.

11. Turn around

    นัท clone ต๋า's repository
    ต้น clone ต้น's repository
    ...
    โอม clone เอ's repository
    เอ clone นัท's repository

    e.g. โอม clone เอ's repository

    ```sh
    cd path/to/workspace
    git clone git@github.com:<username>/tennis-legacy15.git
    ```

12. Open project with your IDE, then continuous implement.

13. Commit the files that you've staged in your local repository.

    ```sh
    git commit -m "Your commit message"
    ```

14. Push the changes in your local repository to GitHub.

    ```sh
    git push
    ```

15. Go back to your original project

    e.g. โอม

    ```sh
    cd ../tennis-legacy14
    git pull
    ```
