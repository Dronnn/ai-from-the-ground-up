# AI Foundations Resources

## Knowledge

- [Video series: "Neural Networks" — 3Blue1Brown (Grant Sanderson)](https://www.3blue1brown.com/topics/neural-networks)
  The gold standard for visual intuition. Use for: what a neuron is, layers, forward pass, gradient descent, backpropagation. Watch in order.
- [Lesson 1: "But what is a Neural Network?" — 3Blue1Brown](https://www.3blue1brown.com/lessons/neural-networks)
  Single video introducing the neuron as "a thing that holds a number" and how weighted sums + bias + activation build a network. Use for: lesson 0001.
- [Book (free, online): "Neural Networks and Deep Learning" — Michael Nielsen](http://neuralnetworksanddeeplearning.com)
  Free, beginner-friendly, math shown but gently. Use for: deeper reading on neurons, gradient descent, backprop with code.
- [Course: "Practical Deep Learning for Coders" — fast.ai](https://course.fast.ai)
  Top-down, code-first, aimed at programmers. Use for: when you start training real models.
- [Wikipedia: Artificial neuron](https://en.wikipedia.org/wiki/Artificial_neuron)
  Confirms the canonical formula y = φ(Σ wⱼxⱼ) with bias as the x₀=1 term. Use for: the neuron definition.
- [Wikipedia: Sigmoid function](https://en.wikipedia.org/wiki/Sigmoid_function)
  Confirms logistic sigmoid σ(z)=1/(1+e⁻ᶻ), range (0,1), σ(0)=0.5. Use for: activation functions.
- [Wolfram Alpha](https://www.wolframalpha.com)
  Use for: verifying numeric results (e.g. σ(1.0)=0.7311).
- [Course notes: CS231n — Neural Networks parts 1–3 (Stanford)](https://cs231n.github.io/neural-networks-1/)
  Crisp reference on activations, layer counting, initialization, epochs. Use for: conventions and the ReLU story (lessons 4, 5, 9, 10).
- [Video: Karpathy — "The spelled-out intro to neural networks and backpropagation"](https://www.youtube.com/watch?v=VMj-3S1tku0)
  Builds the training loop from an empty Python file, narrating every line. Use for: after lesson 9, before/alongside lesson 10.
- [Tutorial: PyTorch — "Learn the Basics"](https://pytorch.org/tutorials/beginner/basics/intro.html)
  Official 7-part intro (tensors, autograd, optimization loop), each part runnable in Colab. Use for: lessons 11–12 and beyond.

## Wisdom (Communities)

- [r/learnmachinelearning](https://reddit.com/r/learnmachinelearning)
  Beginner-friendly, moderated. Use for: "is my mental model right?" questions, study-path critique.
- [r/MachineLearning](https://reddit.com/r/MachineLearning)
  Higher-level / research. Use for: later, once fundamentals are solid.
