# GDIM32 In Class Activities
## W1 class activities

### Activity 1
- LA tech support
- start early
- playtest
- office hours
- table discussion
- lecture slides & course resources (including unity official website)
- itch link checkkkkkk

### Activity 2
1. 10
2. 2
3. prints "hello world" message every frame to the console
4. Monobehaviour
5. prints message "x = 10" to the console
6. parameter and argument
7. Transform is a class so cannot call for translation
8. should use _playerTransform

### Activity 3
[google doc](https://docs.google.com/document/d/11NYqSVvzWFbjYSesEhZULsuZtHzjsLqqcApzmbzIQNQ/edit?usp=sharing)




## W2 class activities


### Activity 1
![classactivity](https://github.com/user-attachments/assets/bca4f035-dcb2-4e7b-bac2-c97ca2d104d9)


### Activity 2
[MG2 repo link](https://github.com/UCI-GDIM32-W25/mg2-oop-review-minjoos5/commit/c767fd84fcad7a0ee93da43e7d80704bc77ab227)

I created game objects (penguin player, coin prefab, UI TMP texts, and scripts of them), and added components to them (rigidbody 2D, collider 2D, etc)




## W3 class activities

### Activity 0 - 2


Partner: Sonia Mangat


### Activity 3
![2023  6  27  - 250](https://github.com/user-attachments/assets/ac3ae340-1d1e-4ae2-9363-5808c57a8d8d)


## W4 class activities

### Activity 0


Partner: Sonia Mangat


### Activity 1

Q: Add multiple Locator objects to the Scene. What happens to the Locator objects when you run the game, and why?


A: When I added multiple Locator game objects in Unity (copy & paste), the last Locator I created worked in the scene, and the rest of the Locators were disabled in the game. Multiple locators didn't ruin my game, but only one locator worked in the game. Instance let the game refers to the same game object, although I created multiple locators in the game hierarchy.


### Activity 2
![KakaoTalk_20260127_183848724](https://github.com/user-attachments/assets/791b2899-efe8-491e-a5c2-73b536cdf153)


### Activity 3
[MG4 repo link](https://github.com/minjoos5/HW4)

I created Unity file and added some basic sprites for the game


## W5 class activities

### Activity 1

What do you think of the design of these interfaces and abstract classes? Would you keep it the same, or change it, if you were building a project with items like these?
- I think it's better to use abstract classes in games like these because the results for each item are different. In addition, it's difficult to create unique methods for each item, which is inefficient. Thus, I think it's better to use an abstract class in the game to manipulate methods more concisely. I want to keep it the same in managing the methods and expected outcomes in the game.


### Activity 2

In the second demo, what classes represent the Model, View, and Controller aspects of the MVC pattern used in the scene?

- They show the aspect of MVC through their connection between the classes. When the controller gets the input information from the player, it calculates it with model classes and shows it on the screen (UI screen).

### Activity 3

#### Senario 1
I think inheritance, finite state machine, and singleton should be in the game, like Project Diva.
- There are multiple different beats that share the same action from the player
- FSM to update the state of the player and beat throughout the game (also to change the animation of each beat)
- Singleton to calculate the score and show up in the UI --> Singleton makes it easier and more concise

#### Senario 2
- FSM to manipulate the animations of each weapon and playable characters
- MVC to calculate and show the reaction based on the weapon and attack made by the player
- Scriptable Objects to manipulate various variables simultaneously

#### Senario 3
- FSM to update the player's status (emotion, farming, etc)
- Inheritance & singleton to manipulate multiple items and foods (apple, banana, orange will share similar animation and behavior --> abstract class and overriding required)

### Activity 4
- Attendance: Minjoo Shin, Sonia Mangat, Milla Lucido
- [Final Project Proposal](https://docs.google.com/document/d/1t76iuo2Br_0iJsKgst12nwN4ChwI5BFe61iVY1-cFXg/edit?usp=sharing)

## W6 GDW alternative assignment

- [Alternative Assignment](https://docs.google.com/document/d/17i9UxM3GMZ1Zy1EU4e3AI8FzxnrcviEbiPTcdNS9ADY/edit?usp=sharing)
- Please check the second tab!!

## W7 class activities

### Activity 1

- Duck detects the player (chicken) by using a raycast (visualized by Gizmo in the scene)
- If the player hides behind the tree --> duck cannot detect the player, and it is shown by the dot in the scene
- The singleton is useful in managing duck's animation in this case (see player (run/red), not see player (mingle around))

### Activity 2
Attendance: Minjoo Shin, Milla Lucido, Sonia Mangat

### Activity 3
![image0](https://github.com/user-attachments/assets/5e6a70b4-178d-4c97-85da-aaa11c1eeeeb)


### Activity 4
- Sonia: Player and item script
- Minjoo: Setting up UI
- Milla: Building Scene and uploading assets
- [Project Tracker](https://docs.google.com/document/d/1OFqRcPZ5ifyW1PyqHkWC3omZ_qQ_pCy577yJh6sZSFs/edit?usp=sharing) 

### Activity 5
- [UI commit link](https://github.com/jedi-narwhal/GDIM32-Final/commit/228ef11b8ed65b63d9623ac844624c10949434f6)
- I worked on game over, game start, and timer on the gameplay screen (UI)


## W8 class activities

### Activity 1
- should check the rendering pipeline at the assets store to check its compatibility
- Edit > Project settings > Graphics to check the compatibility
- post-processing at the end of the game build --> should set a layer for post-processing
- drunk chicken

### Activity 2
Attendance: Minjoo Shin, Milla Lucido, Sonia Mangat

### Activity 3
- We reached our goal, and the game's movement works all ok
- The player's sensitivity is too high --> should be fixed
- The player's collider doesn't work naturally when it is hit by the furniture around the room (ex. couch) --> should use raycast to fix this problem?


- Change FOV for camera (reduce)
- Reduce mouse sensitivity
- Make players unable to walk on furniture
- Good movement
- Unity play has good mouse sensitivity, figure out how to make itch have good sensitivity
- Assign proper skybox

### Activity 4
My task: work on the inspector, timer, and UI

### Activity 5

