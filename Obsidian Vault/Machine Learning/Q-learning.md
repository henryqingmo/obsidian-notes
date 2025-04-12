### Idea
![[Screenshot 2024-11-05 at 5.31.41 pm.png]]
#### Bellman equation
$$
Q(S_1​,a)_{observed}​=R(S_2​)+\gamma \;max​\;Q(S_2​,a)
$$
Here $\gamma$ is the Discount factor, higher $\gamma$ represent we value more of future value rather than current value.
#### Example
![[CodeEmporium - Q-learning - Explained! [TiAXhVAZQl8 - 925x578 - 6m48s].png]]
#### Temporal difference error
$$
\text{TD\;Error} = Q(S_1, \text{a})_{observed}\; -Q(S_1,a)_{expected}
$$
#### Example
![[CodeEmporium - Q-learning - Explained! [TiAXhVAZQl8 - 925x578 - 7m23s].png]]
#### Update Rule
$$
Q(S_{1,}a) = Q(S_{1,}\text{a}) + \alpha \times \text{TD Error}
$$
Here $\alpha$ is the learning rate, defines how much in each timestamp to change the Q-Value
![[CodeEmporium - Q-learning - Explained! [TiAXhVAZQl8 - 925x578 - 8m03s].png]]
### [[Policy]]
Q-learning uses behaviour policy which chooses random action that doesn't base
on the Q-value. Hence it's off-policy.

Once the Q-Value is learnt, we give the agent target policy, so the agent follows the highest Q-value.






#coding #math #machine_learning #reinforcement_learning


