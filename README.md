# RL_Recruiter+

A participant selection algorithm using reinforcement learning.

## Abstract

Participant selection is a fundamental research issue in Mobile Crowdsensing (MCS). Previous approaches commonly assume that adequately long periods of candidate participants' historical mobility trajectories are available to model their patterns before the selection process, which is not realistic for some new MCS applications or platforms. The sparsity or even absence of mobility traces will incur inaccurate location prediction, thus undermining the deployment of new MCS applications. To this end, this paper investigates a novel problem called “From-Scratch MCS” (FS-MCS for short), in which we study how to intelligently select participants to minimize such “cold-start” effect. Specifically, we propose a novel framework based on reinforcement learning, named RL-Recruiter+. With the gradual accumulation of mobility trajectories over time, RL-Recruiter+ is able to make a good sequence of participant selection decisions for each sensing slot. Compared to its previous version RL-Recruiter, Re-Recruiter+ jointly considers both the previous coverage and current mobility predictability when training the participant selection decision model. We evaluate our approach experimentally based on two real-world mobility datasets, and the results demonstrate that RL-Recruiter+ outperforms the baseline approaches, including RL-Recruiter under various settings.