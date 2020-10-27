# Intelligent Agents
## Agents and Environments
### Agent
- An **agent** is anything that can be viewed as perceiving its **environment** through **sensors** and acting upon that environment through **actuators**.
- Example:  A human agent has eyes, ears, and other organs for sensors and hands, legs, vocal tract, and so on for actuators.

## Good Behavior: The Concept of Rationality
- A **rational agent** is one that does the right thing.

### Performance measures
- Moral philosophy has developed several different notions of the "right thing", but AI has generally stuck to one notion called **consequentialism**: we evaluate an agent's behavior by its consequences. When an agent is plunked down in an environment, it generates a sequence of actions according to the percepts it receives. This sequence of actions causes the environemnt to go through a sequence of states. If the sequence is desirable, then the agent has performed well. This notion of desirability is captured by a **performance measure** that evaluates any given sequence of environment states. 
### Rationality
- What is rational at any give time depends on four things:
	- The performance measure that defines the criterion of success.
	- The agent's prior knowledge of the enviroment
	- The actions that the agent can perform
	- The agent's percept sequence to date.
- For each possible percept sequence, a rational agent should select an action that is expected to maximize its performance measure, given the evidence provided by the percept sequennce and whatever built-in knowledge the agent has.
### Omniscience, learning, and autonomy
- An omniscient agent knows the *atual* outcome of its actions and can act accordingly; but omniscience is impossible in reality.
## The Nature of Environments
### Specifying the task environment
- **Fully Observable vs Partially Observable**:
	- If an gent's sensors give it access to the complete state of the environment at each point in time, then we say that the task environment is fully observable. A task environment is effectively fully observable if the sensors detect al aspects that are *relevant* to the choice of action; relevance, in turn, depends on the performance measure.
- **Single-agent vs Multiagent**
- **Deterministic vs nondeterministic**: If the next state of the environment is completely determined by the current state and the action executed by the agent, then we say the environment is deterministic; otherwise, it is nondeterministic environment.
- **Episodic vs Sequential**: In an episodic task environment, the agent's experience is divided into atomic episodes.In each episode the agent receives a percept and then performs a single action.
- **Static vs Dynamic**: If the environment can change while an agent is deliberating, then we say the environment is dynamic for that agent
- **Discrete vs Continuous**: The discrete/cntinuous distinction applies to the state of the environment, to the way time is handled, and to the percepts and actions of the agent.
