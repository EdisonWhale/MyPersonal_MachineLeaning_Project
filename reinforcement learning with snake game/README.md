# Reinforcement Learning With PyTorch and Pygame

This project demonstrates the application of reinforcement learning to train a snake agent in a classic Snake game using PyTorch and Pygame.

![Snake Game](https://user-images.githubusercontent.com/103423072/236655594-cb8453bb-2419-448a-ad54-3a3a9e714ace.gif)

## Dependencies

To run this project, you'll need to install the following packages:

- PyTorch
- numpy
- matplotlib

You can install them using pip:

```bash
pip install torch numpy matplotlib

```



The `game.py` script contains the main game logic. You can adjust the game speed within the `game.py` file by changing the `SPEED` variable. The default speed is set to 40.

![Game Settings](https://user-images.githubusercontent.com/103423072/236655605-c2a7bca7-d916-4836-b77b-25a1c6e6c449.png)

After multiple training sessions, it has been found that the best performance is achieved with a speed value between 35 and 40. The snake agent tends to perform better after around 80 game iterations (game times).

Feel free to experiment with the parameters and explore the potential of reinforcement learning in the Snake game!

![Training Results](https://user-images.githubusercontent.com/103423072/236655606-974f0069-32bf-43ca-ba23-60d4b74b47de.png)


