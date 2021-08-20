# Reinforcement-learning

This is a PyTorch implementation of Deep Q-Learning.

## Example (1)- A result from the Atari_Breakout.

Experience memory capacity: 80000 set  
Random action ratio: from 1.0 to 0.1 through 1000000 frames

### Best eposide:

https://user-images.githubusercontent.com/48608835/129293272-7ab38bf0-b2d6-41e2-aebf-c641cfc92ab3.mp4

### Learning scores:

<img src="https://user-images.githubusercontent.com/48608835/130166082-5cd812c8-ea23-4acf-82df-da0b5252bad2.png" width=680px>

Blue line: Score of training episode.  
Magenta line: Mean score of last 100 training episodes.  
Red star: Score of target agent.  

## Example (2)- A result from the Cartpole.

Experience memory capacity: 10000 set  
Random action ratio: from 0.9 to 0.05 through 200 episodes

### Best eposide:

https://user-images.githubusercontent.com/48608835/129293385-7a936a7c-f663-4813-b01c-0b17f77f777f.mp4

### Learning scores:

<img src="https://user-images.githubusercontent.com/48608835/130166878-b98c9198-8ac8-4ff1-91c7-1df3bf70ae51.png" width=680px>

Blue line: Score of training episode.  
Magenta line: Mean score of last 100 training episodes.  
