# Space 🚀 Invaders 

In my version of Space Invaders, which I developed using GDevelop, you control a spaceship at the bottom of the screen, by using "A" and "D" keys you're able to move left and right to avoid being hit by aliens. 
Spacebar will allow you to shoot back and destroy each alien one by one, when all aliens are destroyed you'll progress to the next level. 
Level 2 has a slightly upped difficulty with aliens now shooting twice the amount. 
Level 3 has a boss, with a health bar you'll need to use both "A" and "D" to avoid being hit by the ball of fire. After defeating the boss you've taken back to the main menu to play gain.  

Link to play: 🔗

https://gd.games/instant-builds/cf18b1ab-0e2a-447b-928a-0f216cf894fb

# Logic and Functionality ⚙️🔨

Player Movement:

Condition: A Left key is pressed ⬅️
Action: Move the spaceship left 
Condition: A Right key is pressed ➡️
Action: Move the spaceship right  

Bullet:

Condition: A Space key is pressed ⏺️
Trigger once: Fires the bullet once when the Space key is pressed ⚡
Action:
Create object: A bullet is created at the spaceship's position (X, Y) 🔫
Play sound: "laser 01.wav" at 25% volume (Pew Pew! 🔊)
Action:
Instant force (Bullet movement): Bullet is given an instant force at -90 degrees with a length of 500 pixels, firing upwards 💨

# Screenshots:

![image](https://github.com/user-attachments/assets/bec5e2b0-097f-408e-8e7b-04b46a168d29)
![image](https://github.com/user-attachments/assets/399a5703-597b-4411-ace3-6f40af8cf532)
![image](https://github.com/user-attachments/assets/21ba591e-471e-4774-ba0c-2c7a44992620)
![image](https://github.com/user-attachments/assets/0f9b5fd5-377f-4a18-886c-98c7003c753c)
![image](https://github.com/user-attachments/assets/165c6ada-47fd-46af-8dd1-b9d82a0b76f2)


