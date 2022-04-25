# Avoid the bullets

- **Use the mouse to avoid flying bullets**
  
## General
---

![](./DemoImg.png)
This is the sample image. [**Click here**](##Demo-scene-using-Scratch) to get more images.


- Mouse cursor is the player. Main character image follows the cursor(bird).
- The player should avoid the bullets(jars).
- The player should reach the coin(described as strawberry). If you earn it, get score.
- The score is placed at the top left.
- When one game is end, the highscore and a button to restart appears.


## Details


|Content|Function|Related Event|
|------|------|------|
|Player|Controlled by mouse|mousemove|
|Bullet|Randomly, heading the player's location|Periodically|
|Coin|Randomly appears, touch it to earn score|Previous coin disappears|
|Score|Visualize the score|Coin earning|
|Highscore|Visualize the highest score|Player touched the bullet|


## Challenges


The bullet shape may not be an square, so calculating the player & bullet touch will be a challenge.

The bullet and the coin will be treated as object class (because we have to manage their location and touch). I will use the subscribing method to check the score change events.

The canvas will be drawn by the p5.js.


## Demo scene using Scratch

![https://scratch.mit.edu/projects/680274598/](DemoImg.png)
![https://scratch.mit.edu/projects/680274598/](Highscore.png)
Click the above images to get to the scratch demo.

