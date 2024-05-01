DQN uses two networks, a policy network and a target network.

![image](https://github.com/AkshayKulkarni3467/DeepQ-Networks/assets/129979542/806b678a-e1eb-428f-aa1a-6e8ff8fa1250)

DQN stores the experiences in a replay memory, and trains the policy network on it.
After a few batches, the parameters of the target network are replaced by the parameters of policy network.

Training the cart pole problem for 10,000 steps-

![image](https://github.com/AkshayKulkarni3467/DeepQ-Networks/assets/129979542/5633d1a2-d04e-4bc8-ae17-82b604f588b3)

Visualization of the training:


https://github.com/AkshayKulkarni3467/DeepQ-Networks/assets/129979542/50e2680c-d515-46af-83cc-285ded218959

