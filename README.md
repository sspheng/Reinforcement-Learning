A. WHAT IS REINFORCEMENT LEARNING ?

Reinforcement Learning is a feedback-based Machine learning technique in which an agent learns to behave in an environment by performing the actions and seeing the results of actions.For each good action, the agent gets positive feedback, and for each bad action, the agent gets negative feedback or penalty.
In Reinforcement Learning, the agent learns automatically using feedbacks without any labeled data, unlike supervised learning.Since there is no labeled data, so the agent is bound to learn by its experience only.Reinforcement Learning solves a specific type of problem where decision making is sequential, and the goal is long-term, such as game-playing, robotics, etc.

B. HOW IS REINFORCEMENT LEARNING DIFFERENT FROM SUPERVISED LEARNING ?

Reinforcement learning differs from supervised learning in a way that in supervised learning the training data has the answer key with it so the model is trained with the correct answer itself whereas in reinforcement learning, there is no answer but the reinforcement agent decides what to do to perform the given task.

![image](https://github.com/sspheng/Reinforcement-Learning/assets/78303183/1bc70c06-36f9-475e-af26-8e335c931951)

C. CHARACTER OF REINFORCEMENT LEARNING

No Supervision, only a real value or reward signal.

Decision making is Sequential.

Time Plays a major role in reinforcement Problems.

Feedback isn't Prompt but delayed.

The following data is receive is determined by the agent’s actions.

D. REINFORCEMENT LEARNING ALGORITHMS

* Value-Based: The main goal of this method is to maximize a value function. Here, an agent through a policy expects a long-term return of the current states.

* Policy-Based: In policy-based, you enable to come up with a strategy that helps to gain maximum rewards in the future through possible actions performed in each state. Two types of policy-based methods are deterministic and stochastic.

* Model-Based: In this method, we need to create a virtual model for the agent to help in learning to perform in each specific environment

E. TYPES OF REINFORCEMENT LEARNING

1. Positive Reinforcement Learning :-  Positive Reinforcement is defined as when an event, occurs due to specific behavior, increase the strength and frequency of the behavior. It has a positive impact on behavior.

* Advantages: Maximizes the performance of an action ; Sustain change for a longer period

* Disadvantage: Excess reinforcement can lead to an overload of states which would minimize the results.

2. Negative Reinforcement Learning :-  Negative Reinforcement is represented as the strengthening of a behavior. In other ways, when a negative condition is barred or avoided, it tries to stop this action in the future.

* Advantages: Maximized Behavior ; Provide a decent to minimum standard of performance.
* Disadvantage: It just limits itself enough to meet up a minimum Behavior.

F. MAJOR 5 FRAMEWORK FOR REINFORCEMENT LEARNING 

1. Keras-RL

2. Keras-RL2

3. OpenAI Baselines

4. Stable Baselines

5. ACME

G. WHAT ARE THE ELEMENTS OF REINFORCEMENT LEARNING ?

There are four main Elements of reinforcement Learning which are given below: 

1. Policy

2.Reward Signal

3. Value Function

5.Model of the Environment

H. WHAT IS THE MULTI-ARMED BANDIT PROBLEM ?

The term "multi-armed bandit" comes from a hypothetical experiment where a person must choose between multiple actions (i.e., slot machines, the "one-armed bandits"), each with an unknown payout.The goal is to determine the best or most profitable outcome through a series of choices.At the beginning of the experiment, when odds and payouts are unknown, the gambler must determine which machine to pull, in which order and how many times. This is the “multi-armed bandit problem.”

*** MULTI-ARMED BANDIT SOLUTIONS

There are many different solutions that computer scientists have developed to tackle the multi-armed bandit problem. Below is a list of some of the most commonly used multi-armed bandit solutions:

1. Epsilon-greedy

2. Upper confidence bound

3. Thompsons Sampling(Bayesian)

I. WHAT IS MARKOV DECISION PROCESS ?

Reinforcement Learning is a type of Machine Learning.

It allows machines and software agents to automatically determine the ideal behavior within a specific context, in order to maximize its performance. Simple reward feedback is required for the agent to learn its behavior; this is known as the reinforcement signal. There are many different algorithms that tackle this issue.
As a matter of fact, Reinforcement Learning is defined by a specific type of problem, and all its solutions are classed as Reinforcement Learning algorithms. In the problem, an agent is supposed to decide the best action to select based on his current state. When this step is repeated, the problem is known as a Markov Decision Process.

A Markov Decision process (MDP) model contains:

A Set of possible world states S.

A set of Models.

A set of possible actions A.

Areal value reward function R(s , a).

A Policy the Solution of Markov Decision process.

Reference:

https://my.careerera.com/admin/EditBatchAttachment.php?WorkshopID=WS103891&schedule_id=53013




  



