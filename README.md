# Intelligent Roundabout Insertion using Deep Reinforcement Learning
An important topic in the autonomous driving research is the development of maneuver planning systems. Vehicles have to interact and negotiate with each other so that optimal choices, in terms of time and safety, are taken. For this purpose, we present a maneuver planning module able to negotiate the entering in busy roundabouts. The proposed module is based on a neural network trained to predict when and how entering the roundabout throughout the whole duration of the maneuver. Our model is trained with a novel implementation of A3C, which we will call Delayed A3C (D-A3C), in a synthetic environment where vehicles move in a realistic manner with interaction capabilities. In addition, the system is trained such that agents feature a unique tunable behavior, emulating real world scenarios where drivers have their own driving styles. Similarly, the maneuver can be performed using different aggressiveness levels, which is particularly useful to manage busy scenarios where conservative rule-based policies would result in undefined waits. 

The following link (https://youtu.be/qVwRCad5K9c) shows how the vehicle performs the entering in the roundabout.

Further details about this work are available at the following link: https://arxiv.org/abs/2001.00786

CONFERENCE: International Conference on Agents and Artificial Intelligence 2020 (ICAART 2020)
