# Report

## Project 3 : Collaboration & Competition

## 1. ALGORITHMS

Multi agent DDPG for Tennis prject

## 2. NETWORKS

(1) Actor : Batch Normal -> Linear -> ReLU -> Batch Normal -> Linear  -> ReLU -> Batch Normal -> Linear
(2) Critic : Linear -> ReLU -> Batch Normal -> Linear -> RelU -> Linear

## 3. Parameters

n_episodes = 2000

BUFFER_SIZE = int(1e5)   
BATCH_SIZE = 128         
GAMMA = 0.99            
TAU = 1e-3              
LR_CRITIC = 1e-3         
LR_ACTOR = 1e-3          
WEIGHT_DECAY = 0 

## 4. Results
![32323](https://user-images.githubusercontent.com/75971822/135043235-a8199b4a-89e7-4df0-822e-b27205a30b46.png)

