## Language Conditioned Imitation Learning over Unstructured Data

### 1. Learning to follow natural language instructions from play
![Scaling up free-form natural language instruction following with unstructured data](assets/image-1.png)
1) First, relabel teleoperated play into many image goal examples. Next, pair a small amount of play with hindsight instructions, yielding language goal examples.

2) Multicontext imitation: train a single policy on both image and language goals.

3) Test time: A single agent performs many skills in a row, directly from images, specified only in natural language.

### 2. Multicontext Imitation Learning
![Multicontext Imitation Learning](assets/image-2.png)

### 3. Comparing original goal image conditioned LfP (left) to goal image or natural language conditioned LangLfP (right)

![LfP&LangLfp](assets/image-3.png) 

### 4. Following novel instructions at test time in zero shot using transfer learning
![test](assets/image-4.png)


## CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks

### Four key components of CALVIN
![Composing Actions from Language and Vision](assets/image-5.png)

### Observation and action spaces for the CALVIN benchmark
![alt text](assets/image-6.png)

###  Sensor and actuator suite for the CALVIN benchmark
![alt text](assets/image-7.png)

