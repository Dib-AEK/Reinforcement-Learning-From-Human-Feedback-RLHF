# Reinforcement-Learning-From-Human-Feedback-RLHF
Use Reinforcement Learning From Human Feedback for fine tuning an LLM model. Based on Coursera project:

https://www.coursera.org/projects/reinforcement-learning-from-human-feedback-project

# Main
TuneLLM.ipynb

# RLHF Fine-Tuning Loop for LLMs

Our Large Language Model (LLM) is fine-tuned using a Reinforcement Learning from Human Feedback (RLHF) loop. The loop consists of the following steps:

1. **Preference Dataset**: A dataset of human preferences is collected, which serves as the foundation for the fine-tuning process.
2. **Reward Model**: The preference dataset is used to train a reward model. This reward model will be used to provide feedback to the LLM during the reinforcement learning loop.
3. **Reinforcement Learning Training Loop**: The base LLM is then trained using reinforcement learning, with the reward model providing feedback on its performance. The LLM is updated based on this feedback, and the process is repeated until convergence.
