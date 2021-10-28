+++
weight = 41
+++

<!-- Start vertical slides -->
{{% section %}}

# How you can help ?

Participating GitHub repositories:

- ➡️ [PyTorch-Ignite](https://github.com/pytorch/ignite) - Library to help with training and evaluating neural networks

- [PyTorch-Ignite Examples repository](https://github.com/pytorch-ignite/examples) - Examples, tutorials, and how-to guides

---

# Prerequisites

- Basic Python knowledge
- Basic PyTorch knowledge
- Basic Machine Learning knowledge

---

# Start contributing

## Codebase structure

<div style="font-size: 20px;">

- [ignite](ignite) - Core library files
  - [engine](ignite/engine) - Module containing core classes like Engine, Events, State.
  - [handlers](ignite/handlers) - Module containing out-of-the-box handlers
  - [metrics](ignite/metrics) - Module containing out-of-the-box metrics
  - [contrib](ignite/contrib) - Contrib module with other metrics, handlers classes that may require additional dependencies
  - [distributed](ignite/distributed) - Module with helpers for distributed computations
- [tests](tests) - Python unit tests
- [docs](docs) - Documentation files

</div>

https://github.com/pytorch/ignite/blob/master/CONTRIBUTING.md#developing-ignite

---

# Help-wanted issues:

https://github.com/pytorch/ignite/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22




<!-- End vertical slides -->
{{% /section %}}
