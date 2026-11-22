# Project Proposal: CAMPUS MYSTERY – The Last Exam
**Student Name:** Sakib Hasan  
**Student ID:** 11230321522
## 1. Introduction
CAMPUS MYSTERY: The Last Exam is a 2D top-down adventure and puzzle-solving game developed using Python and Pygame.
The game is set in a mysterious university campus where the final examination question paper has disappeared. The player controls a student character who explores different campus locations, collects hidden clues and keys, avoids security robots, and solves educational puzzles to recover the missing examination paper.
## 2. Objectives
- Develop an interactive 2D graphical game.
- Demonstrate player movement and keyboard interaction.
- Implement moving enemies and collision detection.
- Develop a scoring and health system.
- Design multiple levels with different environments.
- Introduce educational puzzles and interactive objects.
- Apply fundamental computer graphics and game programming concepts.
- Create an enjoyable and challenging adventure experience.
## 3. About the Game
CAMPUS MYSTERY: The Last Exam is an adventure game in which the player takes the role of a student detective.
The university's final examination question paper has mysteriously disappeared. The player must investigate different locations around the campus to discover what happened.
During the adventure, the player explores classrooms, the university library, the computer laboratory, and an underground secret laboratory. The player must collect hidden clues, find keys, solve educational puzzles, unlock restricted areas, and avoid security robots.
The main objective is to discover the missing examination paper and successfully complete the final mission.

## 4. Game Story and Gameplay

The game begins with a mysterious incident at the university: the final examination question paper has disappeared.

The player starts the investigation at the university campus and gradually discovers clues that lead to different locations.

The adventure includes the following activities:

- Explore different university environments.
- Collect hidden books, keys, and important documents.
- Avoid security robots patrolling the campus.
- Solve programming and general knowledge questions.
- Unlock restricted doors and secret areas.
- Complete missions to progress through the game.
- Recover the missing examination paper in the final level.

The player must manage health and mission time carefully to complete the adventure.

## 5. Planned Game Features

### A. Player and Movement System

1. **Player Character:** A student character controlled by the player throughout the game.
2. **Four-Directional Movement:** Move up, down, left, and right using the WASD keys.
3. **Character Animation:** Walking animations in different directions.
4. **Wall Collision:** Prevent the player from walking through walls and restricted areas.
5. **Player Health:** A health system that decreases when the player collides with enemies.

### B. Enemy and Obstacle System

6. **Security Robot Enemies:** Robots that patrol different areas of the university.
7. **Enemy Movement:** Security robots move automatically around the game environment.
8. **Enemy Collision:** Detect collisions between the student and security robots.
9. **Enemy Difficulty:** Increase enemy movement speed and difficulty in later levels.
10. **Obstacle System:** Add objects such as tables, chairs, bookshelves, and laboratory equipment that block player movement.

### C. Collectible and Interaction System

11. **Collectible Keys:** Find keys hidden in different locations to unlock doors.
12. **Hidden Clues:** Collect documents and clues to discover the missing examination paper's location.
13. **Book Collection:** Collect books and other knowledge-related objects to earn points.
14. **Interactive Objects:** Interact with computers, doors, bookshelves, and other objects.
15. **Locked Doors:** Require specific keys or completed puzzles to enter restricted areas.

### D. Educational Puzzle System

16. **Programming Questions:** Answer basic programming-related questions to unlock computers and doors.
17. **General Knowledge Questions:** Solve educational questions during the adventure.
18. **Multiple-Choice Answers:** Select the correct answer from several available options.
19. **Puzzle Rewards:** Earn points and unlock new areas after solving puzzles.
20. **Puzzle Feedback:** Display correct or incorrect messages after submitting answers.

### E. Level and Mission System

21. **Multiple Game Levels:** Include three different environments with separate missions.
22. **University Campus:** Explore the campus and collect the first clues.
23. **Mystery Library:** Search bookshelves and discover hidden keys and documents.
24. **Computer Laboratory:** Solve programming puzzles and unlock secret information.
25. **Underground Laboratory:** Explore the final secret area and recover the missing examination paper.
26. **Level Progression:** Unlock the next level after completing the current mission.

### F. Score and Game Management System

27. **Score Tracking:** Display the player's current score on the screen.
28. **Health and Lives Display:** Show the remaining health or lives during gameplay.
29. **Countdown Timer:** Display the remaining mission time.
30. **High Score System:** Save the highest achieved score in a local file.
31. **Increasing Difficulty:** Make later missions more challenging through faster enemies and additional obstacles.

### G. Game Interface and User Experience

32. **Start Menu:** Display the game title and start option.
33. **Instruction Screen:** Show the game controls and gameplay instructions.
34. **Pause and Resume:** Allow the player to pause and continue the game.
35. **Game-Over Screen:** Display a game-over message and the player's final score when all health is lost.
36. **Victory Screen:** Display a mission-completed message after recovering the missing examination paper.
37. **Restart Option:** Allow the player to start a new game.
38. **Quit Option:** Allow the player to exit the game.
39. **Sound Effects:** Add sound effects for collecting items, solving puzzles, and collisions.
40. **Background Music:** Play background music during gameplay.

## 6. How to Play

1. Start the game from the main menu.
2. Use the WASD keys to move the student character around the campus.
3. Explore the environment and search for hidden clues, keys, and books.
4. Press E to interact with objects, collect items, or use keys.
5. Avoid security robots and obstacles to protect your health.
6. Solve educational multiple-choice questions to unlock computers and restricted doors.
7. Collect points by finding items and completing puzzles.
8. Complete the objectives of each level to unlock the next location.
9. Reach the underground laboratory and recover the missing examination paper.
10. Complete the final mission to win the game.

## 7. Game Controls

| Keyboard | Action |
|---|---|
| W | Move Up |
| S | Move Down |
| A | Move Left |
| D | Move Right |
| E | Interact / Collect Items |
| SPACE | Confirm Puzzle Answer |
| P | Pause / Resume |
| R | Restart |
| ESC | Quit |

## 8. Planned Levels

### Level 1: University Campus

- Explore the university campus.
- Learn the player movement and interaction controls.
- Collect the first clues and books.
- Avoid security robots.
- Discover the location of the library.

### Level 2: Mystery Library

- Explore the university library.
- Search bookshelves for hidden objects.
- Find keys and important documents.
- Solve a knowledge puzzle.
- Unlock the computer laboratory.

### Level 3: Computer Laboratory and Underground Laboratory

- Explore the computer laboratory.
- Solve programming-related puzzles.
- Discover the entrance to the underground laboratory.
- Avoid security robots.
- Solve the final puzzle.
- Recover the missing examination paper.

## 9. Technologies

- **Programming Language:** Python
- **Game Development Library:** Pygame
- **Code Editor:** Visual Studio Code
- **Version Control:** Git
- **Project Repository:** GitHub
## 10. Step-by-Step Development Plan

The game will be developed in seven weeks. Each stage will be implemented, tested, and improved before moving to the next stage.

### Week 1: Project Setup and Basic Game Environment

**Development Tasks:**

1. Install Python and Pygame.
2. Set up the project in Visual Studio Code.
3. Create the project folder and organize the source code.
4. Create the main Pygame window.
5. Set the screen resolution, frame rate, and game title.
6. Create the basic university campus background.
7. Implement the main game loop.
8. Add basic game window exit functionality.

**Expected Result:** A working Pygame window displaying the initial university campus environment.

### Week 2: Player Character and Movement System

**Development Tasks:**

1. Create the student player character.
2. Display the character on the campus map.
3. Implement WASD keyboard controls.
4. Add four-directional player movement.
5. Control player movement speed.
6. Prevent the player from moving outside the game window.
7. Add basic walking animations.
8. Implement wall and obstacle collision.

**Expected Result:** A playable student character that can move around the campus without passing through walls or obstacles.

### Week 3: Enemy and Collision Detection System

**Development Tasks:**

1. Create security robot enemy characters.
2. Display enemies in the campus environment.
3. Implement automatic enemy movement.
4. Add enemy patrol movement.
5. Detect collisions between the player and enemies.
6. Implement the player health and lives system.
7. Add obstacles such as tables, chairs, and bookshelves.
8. Test player, enemy, wall, and obstacle collisions.

**Expected Result:** Moving security robots, working collision detection, and a functional health system.

### Week 4: Collectibles, Score, and Basic Game Completion

**Development Tasks:**

1. Add collectible books, keys, and hidden clues.
2. Implement item collection using the E key.
3. Add interactive objects.
4. Implement the on-screen score system.
5. Display player health and remaining lives.
6. Implement the game-over condition.
7. Create the game-over screen displaying the final score.
8. Implement restart and quit functionality.

**Expected Result:** A complete basic playable game with player movement, moving enemies, collision detection, scoring, health, game over, and restart functionality.

### Week 5: Doors, Puzzles, and Multiple Levels

**Development Tasks:**

1. Implement locked doors and key-based unlocking.
2. Add computer and bookshelf interactions.
3. Create educational multiple-choice questions.
4. Add programming and general knowledge puzzles.
5. Display correct and incorrect answer feedback.
6. Implement puzzle rewards and score updates.
7. Design the Mystery Library environment.
8. Design the Computer Laboratory environment.
9. Implement progression between the three planned levels.

**Expected Result:** Players can explore multiple environments, collect keys, solve educational puzzles, and unlock new areas.

### Week 6: Advanced Gameplay and User Interface

**Development Tasks:**

1. Create the main start menu.
2. Add the game instruction screen.
3. Implement pause and resume functionality.
4. Add increasing enemy speed and difficulty.
5. Implement the countdown timer.
6. Add a high-score system using local file storage.
7. Create the final underground laboratory environment.
8. Implement the final mission and victory screen.
9. Add background music and sound effects.
10. Improve the game interface and visual effects.

**Expected Result:** A feature-rich adventure game with multiple levels, menus, puzzles, sound, timer, high score, and victory functionality.

### Week 7: Testing, Debugging, Documentation, and GitHub Submission

**Development Tasks:**

1. Test all game features.
2. Identify and fix programming errors.
3. Test player movement and collision detection.
4. Verify enemy movement and difficulty.
5. Test collectible items, keys, and puzzles.
6. Verify scoring, health, timer, and high-score saving.
7. Test game-over, victory, pause, and restart screens.
8. Capture screenshots of different gameplay stages.
9. Prepare the project README.md file.
10. Upload the complete source code and screenshots to a public GitHub repository.
11. Verify the GitHub repository and documentation.

**Expected Result:** A completed, tested, and documented game ready for teacher demonstration and GitHub submission.

## 12. Expected Outcome

The expected outcome is a complete and playable 2D top-down adventure game featuring multiple university environments, a controllable student character, moving security robots, collectible objects, educational puzzles, scoring, health management, and different game states.

The game will demonstrate fundamental computer graphics and game programming concepts through interactive gameplay.

The completed source code, README.md file, and gameplay screenshots will be uploaded to a public GitHub repository.

## 13. Conclusion

CAMPUS MYSTERY: The Last Exam will combine university-themed storytelling, exploration, puzzle-solving, and interactive gameplay. The project will demonstrate practical applications of computer graphics through a 2D adventure game.

The game will be developed individually using Python and Pygame. Each feature will be implemented and tested step by step, and the student will understand the source code and be able to explain the development process.


##14.Screenshots
