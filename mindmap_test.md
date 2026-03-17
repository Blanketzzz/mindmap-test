```mermaid
mindmap
  root((Convex Optimization Theory))
    Optimization Problem
      Objective function
      Decision variables
      Constraints
      Standard form
        "minimize f(x)"
        "subject to g_i(x) <= 0"
        "h_i(x) = 0"
    Convexity
      Convex set
        "Line segment between any two points stays in the set"
      Convex function
        "f(tx+(1-t)y) <= t f(x) + (1-t) f(y)"
      Properties
        "Local minimum = global minimum"
        "Efficient optimization possible"
    Classes of Problems
      Continuous Optimization
        Linear Optimization
          Linear programming
        Nonlinear Optimization
          Convex problems
            Least-squares problem
          Nonconvex problems
            Local optimization
            Global optimization
      Discrete Optimization
        Integer programming
        Combinatorial optimization
    Algorithms
      First-order Methods
        Gradient descent
        Stochastic gradient descent
        Subgradient method
      Second-order Methods
        Newton's method
        Interior-point methods
      Other Methods
        Coordinate descent
        Proximal methods
    Applications
      Communications
        Power control
        Frequency allocation
        Beamforming design
      Signal Processing
        Estimation
        Detection
        Filter design
        Denoising
      Machine Learning
        Classification
        Regression
        Fitting
      Robotics
        Trajectory planning
        Motion control
      Intelligent Transportation
        Traffic management
        Navigation
      Financial Engineering
        Portfolio optimization
        Index tracking