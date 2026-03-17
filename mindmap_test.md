```mermaid
mindmap
  root((Convex Optimization Theory))

    Optimization Problem
      Objective function
      Decision variables
      Constraints
      Standard form
        minimize f(x)
        subject to g_i(x) <= 0
        h_i(x) = 0

    Convexity
      Convex set
        Line segment between any two points stays in the set
      Convex function
        f(tx + (1-t)y) <= t f(x) + (1-t) f(y)
      Properties
        Local minimum = global minimum
        Efficient optimization possible

    Classes of Problems
      Continuous optimization
        Linear programming
        Nonlinear optimization
          Convex problems
            Least-squares problem
          Nonconvex problems
            Local optimization
            Global optimization
      Discrete optimization
        Integer programming
        Combinatorial optimization

    Algorithms
      Gradient descent
      Newton method
      Interior-point methods
      Subgradient methods

    Applications
      Machine learning
      Signal processing
      Control systems
      Finance
```