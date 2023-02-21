- ```mermaid
  graph TD
  
  A[logging strings] --> B[variables]
  
  B --> C[p/a + conditionals + simple string stuff]
  
  C --> D[c + more types + more operators]
  
  D --> E[while loops, I/O checks]
  
  D --> F[DOM IO library + syntax boilerplate]
  
  E --> G[for-of loops]
  
  F --> G
  
  D --> H[functions + unit tests]
  
  H --> I[import/export]
  
  G --> J[for loops]
  
  D --> K[numbers, casting, ...]
  
  K --> L[p/a/c numbers]
  
  E --> L
  
  D --> M[arrays, reference vs. value]
  
  G --> N[array iteration]
  
  M --> N
  
  J --> N
  
  M --> O[side-effects]
  
  H --> O
  
  H --> P[using functions]
  
  P --> Q[separating logic]
  
  I --> Q
  
  F --> S["persisting" data]
  
  S --> T["persisting" reference types]
  
  R --> T
  
  O --> U[separating array logic]
  
  Q --> U
  
  T --> U
  
  F --> V[multiple interactions per page]
  
  S --> W[data + many interactions]
  
  W --> X[users + data structures]
  
  T --> X
  
  X --> Y[pre-SOC projects]
  ```