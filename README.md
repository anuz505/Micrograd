# My Experience with Micrograd

Micrograd has been one of the most impactful projects I've worked on in my journey to understand neural networks. Designed and explained by the brilliant Andrej Karpathy, Micrograd strips away all the abstractions and shows you what deep learning really is at its core. This project helped me learn neural networks better than ever before — not just how to use them, but how they work under the hood. From the forward pass to backpropagation, and everything in between, I got to see and build it all from scratch.

## Why Micrograd Clicked With Me

Before Micrograd, I had worked with high-level libraries like TensorFlow and PyTorch. While powerful, they often felt like magic. I didn’t fully understand what was happening behind `.backward()` or `.step()`. Micrograd demystified all of that. It made me realize that the essence of neural networks isn’t that complex — it's built on basic principles like gradients, the chain rule, and simple data structures.

The moment everything started to click was when I implemented the `Value` class and watched the computation graph come to life using Graphviz. Seeing how every operation was tracked and how gradients flowed backward gave me a newfound appreciation for autograd systems. I now understand what it really means when we say “the model learns.”

## What I Learned

* **Forward Pass**: I finally got to build a neural network from the ground up — feeding inputs, processing them through layers of neurons, and getting predictions.
* **Backpropagation**: Learning how gradients are calculated and passed backward gave me a solid grasp of how training works. Manually defining `.backward()` for each operation was both challenging and satisfying.
* **Gradient Descent**: Playing with learning rates and watching how overshooting affects training made the theory very real. It’s not just formulas anymore — it’s intuition.
* **Building MLP from Scratch**: Constructing neurons, layers, and eventually the full MLP using nothing but basic Python and math gave me an empowering “I can build this” mindset.

## My Advice for Anyone Learning from Micrograd

If you're planning to learn from this project, here’s what worked best for me:
1. **Watch First, Then Code**: I watched each segment of the video without distractions, trying to absorb the *why* behind each step.
2. **Write Your Own Explanations**: After each section, I paused and wrote out what just happened in my own words. This reinforced my understanding better than anything else.
3. **Rebuild from Memory**: I tried recreating Micrograd without copying code. This was tough, but it showed me where my understanding was still fuzzy — and that’s where the learning really happens.

## Final Thoughts

This wasn’t just another project for me — Micrograd changed how I think about neural networks. It’s one thing to use a tool, and another to understand how it’s built. Thanks to Andrej’s clear teaching and this elegantly simple codebase, I now feel more confident in both my theoretical understanding and practical skills.

If you’re serious about deep learning and want to get your hands dirty in the best way possible, Micrograd is the perfect place to start.

---

### References

* [Andrej Karpathy's Micrograd GitHub Repo](https://github.com/karpathy/micrograd)
* [Andrej Karpathy's YouTube Video on Micrograd](https://youtu.be/VMj-3S1tku0)
