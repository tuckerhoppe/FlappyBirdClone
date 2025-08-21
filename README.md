# FlappyBirdClone
A simple flappy bird clone built using Unity.

![Gameplay GIF of Pixel Wings](https://via.placeholder.com/600x300.png?text=<-+PLACE+YOUR+GAMEPLAY+GIF+HERE)

*A classic and challenging arcade-style game built with the Unity Engine, inspired by Flappy Bird.*


---

## Key Features
* **Endless Procedural Generation:** Pipes are generated endlessly at random heights, ensuring every run is a unique challenge.
* **Collision Detection:** Precise collision detection using Unity's 2D physics system.
* **Simple & Responsive Controls:** Intuitive one-click "flap" mechanic that feels snappy and responsive.
* **Score Tracking:** A clean UI that tracks the player's score in real-time.
* **Game State Management:** A simple but effective system to manage gameplay and game-over states.

---

## 🛠️ Technologies Used
* **Game Engine:** Unity 6.1
* **Language:** C#
* **Version Control:** Git & GitHub


---

## Challenges & Solutions

### Challenge: Creating Performant, Endless Obstacles
* **The Problem:** Constantly creating and destroying pipe GameObjects would cause performance stutters due to memory allocation and garbage collection.
* **The Solution:** I implemented a system that deleted pipes once they reached a certain point past the screen.

### Challenge: Managing Game State
* **The Problem:** The game needed to cleanly transition between the main menu, the active gameplay, and the game over screen without bugs, like the player being able to score after dying.
* **The Solution:** I implemented logic in my logic manager and bird script that prevented the player from being able to score after dying.

---

## Future Improvements
* **High Score System:** Implement `PlayerPrefs` to save and display the local high score.
* **Character Skins:** Add a selection of different bird sprites for the player to choose from.
* **Sound Effects & Music:** Add background music and sound effects for flapping, scoring, and collisions to enhance the player experience.
* **Add Start Menu** Add a start menu that opens as soon as the app runs.

---

## 💻 How To Run
1.  Clone this repository:
2.  Open the project in the Unity Hub 
3.  Open the `MainScene` file from the `Assets/Scenes` folder.
4.  Press the Play button.

---

## ✉️ Contact
* **LinkedIn:** [[Link to your LinkedIn profile](https://www.linkedin.com/in/tucker-hoppe/)]
* **Email:** [tuckerhoppe22@gmail.com]
