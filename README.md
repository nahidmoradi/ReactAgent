Here I used the React Agent pattern, which is called the agent reaction pattern. 
Reasoning + Action is actually a reaction pattern that imitates human thinking, so we have a number of defined concepts:
Think: In fact, if we look at a specific problem, we first think about the problem.
Action: Then we take action to solve that specific problem.
Action Input: Here, the LLM suggests a keyword returned from the LLM to take action to solve this problem.
Observation: At this stage, the agent performs the operation with the provided keyword. If it comes to a conclusion, it thinks again and a loop is created from Think Action Observation Thin Ashken Observation and ... until it reaches the final answer. In this specific example: We have asked the agent to calculate the time interval between the launch of the SpaceX rocket to today, so we need to introduce two tools to the agent, one to get today's system date and the other to search on Google.
