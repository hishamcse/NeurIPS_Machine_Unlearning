## NeurIPS_Machine_Unlearning

### table of contents
   * [Overview](#overview)
   * [Project Introduction](#intro)
   * [Problem Definition](#def)
   * [Competition](#comp)
   * [Solutions](#soln)
   * [Presentation](#present)
   * [Contributors](#cont)

## Overview<a name="overview"></a>
   CSE 472 Machine Learning term project <b>NeurIPS: Machine Unlearning</b> By <b>Syed Jarullah Hisham (1805004)</b> & <b>Abdur Rafi (1805008)</b><br />
   It was a competition hosted on Kaggle organized by Google researchers.

## Project Introduction<a name="intro"></a>
   With rapid growth of AI, more and more rules and regulations are being introduced concerning user privacy and security. These rules and regulations grant users with the right to be forgotten, 
   leading to a new type of request - to delete information. Unfortunately, removing from the training dataset does not guarantee complete removal of the information of a user. Membership inference attack,
   model inversion attack can reveal information about specific contents of a training dataset from the trained model \cite{xu2023machine}. Consequently, removing the influence of some data from the trained 
   model, both completely and quickly has become a region of interest. The NeurIPS: Machine Unlearning competition, held in Kaggle, asks the competitors to perform this task. 

## Problem Definition<a name="def"></a>
   We are given a bi-partition of the training set, where one is called the retain set and other is called the forget set. We are also given a trained model. 
   We have to modify the trained model in such way that the model, ideally, becomes identical to one that was trained only on the retain set. An image from the organizers pictorially describe this problem
                               ![image](https://github.com/hishamcse/NeurIPS_Machine_Unlearning/assets/60782190/bbbb9a57-56cb-4d22-9d86-226a4aab9e71)

## Competition<a name="comp"></a>
   * [NeurIPS-Kaggle](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning)
   * [NeurIPS Challenge Website](https://unlearning-challenge.github.io/)
   * [NeurIPS Github Repo](https://github.com/unlearning-challenge/starting-kit)

## Solutions<a name="soln"></a>
   * [Competition Winner](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning/discussion/458721)
   * [Reproduced 1st Place](https://www.kaggle.com/code/syedjarullahhisham/neurips-machine-unlearning-improved-scl?scriptVersionId=158595208)
   * [Approach 1 : Improved 1st Place](https://www.kaggle.com/code/syedjarullahhisham/neurips-machine-unlearning-improved-scl?scriptVersionId=163792309)
   * [Approach 2 : Gradient Ascent:](https://www.kaggle.com/code/abdurrafi08236/neurips-machine-unlearning-gradient-ascent?scriptVersionId=164117975)

## Presentation<a name="present"></a>
   * [Project Proposal](https://github.com/hishamcse/NeurIPS_Machine_Unlearning/tree/main/Project%20Proposal)
   * [Final Presentation](https://github.com/hishamcse/NeurIPS_Machine_Unlearning/tree/main/Project%20Final%20Presentation)

## Contributors:<a name="cont"></a>
   * [Syed Jarullah Hisham (1805004)](https://hishamcse.github.io/)
   * [Abdur Rafi (1805008)](https://github.com/abdur-rafi)
   
   
