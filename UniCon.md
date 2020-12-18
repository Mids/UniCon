# UniCon: Universal Neural Controller For Physics-based Character Motion

![image-20201218111557528](Abstract.png)

Motion Scheduler + Motion Executor(RL)

Objective function & training techniques...

Train once.

Keyboard driven controller

physics-based virtual avatar

SOTA over the DeepMimic

1. ## Intro

Training Efficiency, Robustness, Motion Capacity, and generalizability.

- a low-level motion executor  <- Key innovation
- a high-level motion schedular (get inputs from keyboard or sth)

Utilize a constrained multi-objective reward optimization,  a motion balancer and a policy variance controller.

Executor done, Utilize motions schedulers for applications.

Keyboard-driven control, compose user-specified motion sequences, and supports teleporting a person video to avatar.



Key improvements over previous work

- ### Generalization

  Imitate unseen motions 

  Natural transition  between motions without recording samples.

- ### Robustness

  Zero-shot

  Characters with widely varying mass, slower or faster motion than trained motions

  

- ### Interactive Applications

  Ranging from keyboard commands, pose from video, suer-specified motions without retrain or fine-tune

- ### Learning Efficiency

  Our algorithm is better

2. ## Related works

   2.1. Keyframe Based Animation

   2.2. Non-interactive Physics-based Methods

   2.3. Interactive Physics-based Methods

3. ## Overview

![image-20201218111620058](C:\Users\jin\AppData\Roaming\Typora\typora-user-images\image-20201218111620058.png)

