```mermaid
%%{init: {'theme':'base'}}%%
mindmap
  root((Convex Optimization Theory))

    Optimization Problem:::blue
      Objective function
      Decision variables
      Constraints
      Standard form
        minimize f(x)
        subject to inequality constraints
        equality constraints

    Convexity:::purple
      Convex set
        line segment between any two points stays in the set
      Convex function
        convex combination property
      Properties
        local minimum equals global minimum
        efficient optimization possible

    Classes of Problems:::gray
      Continuous optimization
        Linear programming
        Nonlinear optimization
      Discrete optimization
        Integer programming
        Combinatorial optimization

    Algorithms:::orange
      Gradient descent
      Newton method
      Interior point methods
      Subgradient methods

    Applications:::red
      Machine learning
      Signal processing
      Control systems
      Finance


classDef blue fill:#4A90E2,color:white
classDef purple fill:#9B59B6,color:white
classDef gray fill:#7F8C8D,color:white
classDef orange fill:#F39C12,color:white
classDef red fill:#E74C3C,color:white
```