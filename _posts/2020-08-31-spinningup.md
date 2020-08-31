# OpenAI's Spinning Up

## What is Spinning Up?

[OpenAI's Spinning Up](https://spinningup.openai.com/en/latest/index.html)

One difficulty of starting out in the field of deep reinforcement learning is trying to figure out where exactly to start. While there are numerous resources for deep learning, there are far fewer high quality resources for deep reinforcement learning. To help solve this problem, OpenAI has developed both a software package and a list of resources that will help you get started in deep RL. 

In addition to the software that is installed, including both Tensorflow and PyTorch, there are numerous resources that are required reading for anyone who wants to work in RL. There are a list of about one hundred papers that considered key papers within the field (Don't worry, you don't have to read them all at once!), along with links to numerous useful blog posts about the reality of conducting research within the field.

## How to use it?

Installing the software and reading through the guide is the most straightforward way to get a handle what the authors are trying to accomplish with Spinning Up. Creating artifacts from experiments and automating the experiment running process is one huge advantage to using Spinning Up, allowing a researcher to run a series of experiments and have numerous artifacts available once the experiments have concluded. 

One of the main advantages to using SU is the ability to very quickly design a series of experiments, and then iterate through them; SU has reference implementations of most of the popular algorithms used such as DQN, DDQN, PPO, A2C and A3C, among others. Since Gym comes installed along with both PyTorch and Tensorflow versions of those algorithms, you can design a series of experiments using different algorithms and compare them directly.

In addition to the software infrastructure that is provided, and the reading and theory that are linked to, there are also exercises that are provided with solutions. These are in part designed to get the user more comfortable with reading mathematical formulas and then implementing those formulas in code. Knowledge of your library of choice helps immensely with these, as knowing what methods to use will help immensely.

I personally haven't implemented any new algorithms in the environment that SU uses, but the process seems straightforward to implement. I also haven't experimented with adding new environments that built from Gym, but adding them isn't likely to be difficult.

## Will I be using it?

Yes! The amount of both infrastructure support and dense reading material means that I will be busy for probably the next calendar year as my skills allow me advantage of the resources at a higher level. I plan to start with small experiments and report on results on a (hopefully) weekly basis.