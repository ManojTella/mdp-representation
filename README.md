# MDP REPRESENTATION

## AIM:
The representation of real world scenario using Markov Decision Process by stating all the states,actions and environment with respective rewards.

## PROBLEM STATEMENT:
To develop a game which will promote to other level,when the agent complete its task correctly.

### Problem Description
If the agent unable to complete the given task,then there is no promotion to other level,when it reaches the final level,it will recieve a reward.

### State Space
{L1,L2,L3}--->{0,1,2}

### Sample State
L1--->{0}

### Action Space
Moving right(1)

Stay in the same level(0)

### Sample Action
Stay in the same level(0)

### Reward Function
+1(When it reaches the goal state or final level)

### Graphical Representation
![gr](https://github.com/ManojTella/mdp-representation/assets/94883876/998eaaa2-24c3-443a-a52a-f69e2ae64133)


## PYTHON REPRESENTATION:
```
Developed By: Manoj Guna Sundar Tella.
Reg No: 212221240026.

P = {
    0:{
        0: [(0.66,0,0,True),(0.33,1,0,False)],
        1: [(0.33,1,0,False),(0.66,0,0,True)]
    },
    1:{
        0: [(0.66,1,0,False),(0.33,2,1,True)],
        1: [(0.33,2,1,True),(0.66,1,0,False)]
    },
    2:{
        0: [(0.66,2,1,True),(0.33,1,1,False)],
        1: [(0.33,1,1,False),(0.66,2,1,True)]
    }
}

```
## OUTPUT:
![image](https://github.com/ManojTella/mdp-representation/assets/94883876/495537ee-0df9-4988-b4d8-805eec45a2a5)


## RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.

