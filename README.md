# Policy gradient Pong for year 2025

Minor adaptation of Andrej Karpathy's [Policy Gradient Pong example](https://gist.github.com/karpathy/a4166c7fe253700972fcbc77e4ea32c5) to more modern dev environment. Changes include:
1. make it work with Python3 (verified with Python 3.12)
2. use gymnasium instead of gym as gym is not updated anymore

Usage:
```
pip install numpy gymnasium ale-py
python pg-pong-2025.py
```

After running it overnight (25500 episodes), the trained agent can beat the computer roughly 1 out of 10 episodes.
