# Source Code for the book "Reinforcement Learning for Sequential Decision and Optimal Control"

Copyright © 2023 Intelligent Driving Laboratory (iDLab). All rights reserved.

Access the book *Reinforcement Learning for Sequential Decision and Optimal Control* at https://link.springer.com/book/10.1007/978-981-19-7784-8.

> Provide a comprehensive and thorough introduction to reinforcement learning, ranging from theory to algorithm
> 
> Introduce reinforcement learning from both artificial intelligence and optimal control perspectives
> 
> Written by a respected expert in the interdisciplinary field of industrial control and artificial intelligence

Make sure to also check out [GOPS](https://github.com/Intelligent-Driving-Laboratory/GOPS) (General Optimal control Problem Solver), a comprehensive Reinforcement Learning toolchain to cover main links in the whole industrial control process, including control problem modeling, policy network training, offline simulation verification, and controller code deployment.

## Run codes of this book
Setup conda first, and install dependencies.
```bash
conda env create -n rlbook -f environment.yml
conda activate rlbook
```
Then open each folder and run `main` or `plot` Python script.
## Source Layout
1. `Chap_3_4_CleanRobot`: Code for robot cleaning example in Chapter 3 and 4.
2. `Chap_5_AutoCar_GridRoad`: Code for autonomous car example in Chapter 5.
3. `Chap_6_Actor_Critic_Algorithm`: Code for actor-critic algorithm in Chapter 6.
4. `Chap_7_AC_wtih_Baseline`: Code for AC algorithm with baseline comparison in Chapter 7.
5. `Chap_8_Veh_Track_Ctrl`: Code for vehicle tracking control example in Chapter 8.
6. `Chap_9_Car_Brake_Control`: Code for emergency braking control example in Chapter 9.

## Citation
If you find this code useful in your research, please consider citing:
> S Eben Li. Reinforcement Learning for Sequential Decision and Optimal Control. Springer Verlag, Singapore, 2023.

Or in BibTeX style:
```bibtex
@book{li2023reinforcement,
    title={Reinforcement Learning for Sequential Decision and Optimal Control},
    author={Li, Shengbo Eben},
    year={2023},
    publisher={Springer Verlag, Singapore}
}
```
