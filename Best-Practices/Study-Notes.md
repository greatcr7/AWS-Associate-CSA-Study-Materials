# [Brandon's Notes] AWS Best Practices


# Introduction
The best practices apply to both migration of existing applications and design of new applications for the cloud.


# The Cloud Computing Difference
## IT Assets Become Programmable Resources

## Global, Available and Unlimited Capacity

## Higher Level Managed Services

## Security Built In


# Design Principles
## Scalability
- Pros: economies of scale, scale in linear manner.
- Two ways to scale: *vertically* & *horizontally*.

### Scaling Vertically
- Scale by increasing the capacity and power of an individual instance. 
- Pros: easy to implement; sufficient for short term in some cases.
- Cons: will eventually hit a limit and is not always cost efficient.

### Scaling Horizontally
- Scale by increasing the number of resources.
- Better way to leverage the elasticity of cloud computing but not apply to all cases.
- Examine by scenarios: *stateless applications*, *stateless components*, *stateful components*, *distributed processing*.
