```mermaid
flowchart LR

A((Convex Optimization Theory))

A --- B
A --- C
A --- D
A --- E
A --- F

B[Optimization Problem]
C[Convexity]
D[Classes of Problems]
E[Algorithms]
F[Applications]

B --> B1[Objective function]
B --> B2[Decision variables]
B --> B3[Constraints]
B --> B4[Standard form]

B4 --> B41[Minimize objective]
B4 --> B42[Inequality constraints]
B4 --> B43[Equality constraints]

C --> C1[Convex set]
C --> C2[Convex function]
C --> C3[Properties]

C1 --> C11[Line segment property]
C2 --> C21[Convex combination property]
C3 --> C31[Local minimum equals global minimum]
C3 --> C32[Efficient optimization]

D --> D1[Continuous optimization]
D --> D2[Discrete optimization]

D1 --> D11[Linear programming]
D1 --> D12[Nonlinear optimization]

D12 --> D121[Convex problems]
D12 --> D122[Nonconvex problems]

D121 --> D1211[Least squares problem]
D122 --> D1221[Local optimization]
D122 --> D1222[Global optimization]

D2 --> D21[Integer programming]
D2 --> D22[Combinatorial optimization]

E --> E1[Gradient descent]
E --> E2[Newton method]
E --> E3[Interior point methods]
E --> E4[Subgradient methods]

F --> F1[Machine learning]
F --> F2[Signal processing]
F --> F3[Control systems]
F --> F4[Finance]

classDef root fill:#FFD166,stroke:#B45309,color:#111111;
classDef blue fill:#93C5FD,stroke:#1D4ED8,color:#111111;
classDef purple fill:#C4B5FD,stroke:#6D28D9,color:#111111;
classDef gray fill:#D1D5DB,stroke:#4B5563,color:#111111;
classDef orange fill:#FDBA74,stroke:#C2410C,color:#111111;
classDef red fill:#FCA5A5,stroke:#DC2626,color:#111111;

class A root;
class B,B1,B2,B3,B4,B41,B42,B43 blue;
class C,C1,C2,C3,C11,C21,C31,C32 purple;
class D,D1,D2,D11,D12,D121,D122,D1211,D1221,D1222,D21,D22 gray;
class E,E1,E2,E3,E4 orange;
class F,F1,F2,F3,F4 red;
```