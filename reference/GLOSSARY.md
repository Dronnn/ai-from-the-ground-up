# AI Foundations Glossary

Key terms used in this course, with the loose synonyms worth avoiding.

## Terms

**Neuron (artificial)**:
A unit that holds one number (its activation), computed from its inputs as a weighted sum plus a bias, passed through an activation function.
_Avoid_: node (use only when discussing graphs), perceptron (that's a specific older variant)

**Activation**:
The single number a neuron outputs — "how lit up" it is. With a sigmoid, it sits between 0 and 1.
_Avoid_: output value, firing rate

**Weight**:
A number on a connection representing the strength of that input — how much that input pushes the neuron up or down.
_Avoid_: strength score, importance

**Bias**:
A per-neuron number added to the weighted sum that shifts how eager the neuron is to fire, independent of any input.
_Avoid_: offset, threshold

**Weighted sum (z)**:
The value `w₁·x₁ + … + wₙ·xₙ + b` — every input times its weight, totalled, plus the bias. Fed into the activation function.
_Avoid_: pre-activation (correct but jargon)

**Activation function (σ)**:
A function that squashes the weighted sum into a bounded range. The sigmoid squashes to (0, 1); σ(0) = 0.5.
_Avoid_: transfer function, squashing function (descriptive, not the name)
