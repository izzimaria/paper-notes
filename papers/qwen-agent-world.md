[Link](https://arxiv.org/abs/2606.24597)

Made me want to look more into what exactly makes something a "world" model - I was told that part of its objective is to predict future states of the environment, but don't all LLMs end up having internal representations of the user, and thus in some sense, the "world"?

I am curious about the tradeoffs between a model predicting the environment's response to an action, and allowing that to replace the actual execution of the action itself. How can we measure the error on a model that is building a world based on predictions that we can't see and haven't asked for? At the same time, if we are intentionally measuring how correct a model's world is, I wonder if that may lead to less bias than a model that has internal representations that aren't included in accuracy calculations.

Thinking about world models reminded me of Bengio et al's [Scientist AI](https://arxiv.org/abs/2502.15657) paper.