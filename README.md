# Planning with Diffusion, on High-dimensional Space

Written by Simo Ryu, Hyunsik Oh, Moonkyu Jung, Taegyu Song
(류시모, 오현식, 정문규, 송태규)


> Technical Report based on the experiments inspired by the paper: [Planning with Diffusion for Flexible Behavior Synthesis](https://arxiv.org/abs/2205.09991), by Michael Janner, Yilun Du, Joshua B. Tenenbaum and Sergey Levine

###  It looks like video breaks on github. So run/view the notebook on [Google Colab](https://colab.research.google.com/drive/1MT-YhOAsdD-T3kAMCsViVZazk7HrZaat)



Planning with diffusion models has garnered significant attention in the field of continuous action-space planning. However, implementing diffusion models from scratch for environments with high-dimensional action-observation spaces can be exceptionally challenging. 
Moreover, the current landscape lacks easily understandable tutorials for diffusion planners. Our goal with this technical report is to provide a more accessible and practical approach to planning with diffusion models, specifically focusing on trajectory planning.

In this report, we will cover the following topics:

1. An overview of diffusion models and their relevance in reinforcement learning (RL) planning.
2. The challenges associated with planning using diffusion models and their implementation.
3. Proposed solutions to address these challenges and improve the effectiveness of diffusion planners.

## Acknowledgements

This work was submitted as final-homework for class AI611 of KAIST GSAI. We would like to thank Prof. [Kee-Eung Kim](http://ailab.kaist.ac.kr/users/kekim) for his guidance and support throughout the course. We would also like to thank the authors of the original paper for their insightful work.
