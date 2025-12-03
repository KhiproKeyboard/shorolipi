# Shörolipi
Shorol + Shor + Lipi = Shorolipi
What is shorolipi?

### হাইলাইটস

### এক নজরে (ওভারভিউ)
সফটওয়্যারটা কী করে, কীভাবে কাজ করে, আর কারা বানিয়েছে। আলাদা আলাদা সেকশনে থাকবে।

### ইনস্টলেশন নির্দেশনা 
লাগবে না

### কীভাবে ব্যবহার করব?

### আপনার মতামত দিন কিংবা ডেভেলপমেন্টে অবদান রাখুন

### Flowchart Demo
```mermaid
flowchart TD
    %% Basic nodes
    A[Rectangle Node] --> B(Rounded Node)
    B --> C{Decision Node}
    C -->|Yes| D[Action for Yes]
    C -->|No| E[Action for No]

    %% Shapes demo
    F((Circle)) --> G[/Parallelogram/]
    G --> H>Asymmetric]

    %% Multiple edges from same node
    D --> I & J

    %% Loop
    J --> C
```

### Sequence Diagram Demo
```mermaid
sequenceDiagram
    autonumber
    participant User
    participant Server
    participant DB

    User->>Server: Send login request
    Server->>DB: Query credentials
    DB-->>Server: Return data
    Server-->>User: Login success

    Note over User,Server: Authentication sequence complete

    User->>Server: Fetch dashboard
    Server-->>User: Rendered page
```

### Class Diagram Demo (GitHub Compatible)
```mermaid
classDiagram
    class Animal {
        +String name
        +eat()
        +sleep()
    }

    class Dog {
        +breed : String
        +bark()
    }

    class Cat {
        +color : String
        +meow()
    }

    class Collar
    class Owner
    class Address

    Animal <|-- Dog
    Animal <|-- Cat
    Dog *-- Collar
    Cat o-- Owner
    Owner --> Address
```



### Mindmap Demo
```mermaid
mindmap
  root((Programming))
    Languages
      Compiled
        C++
        Rust
        Go
      Interpreted
        Python
        JavaScript
    Paradigms
      Functional
      OOP
      Procedural
```


### State Diagram Demo
```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Processing : start
    Processing --> Idle : stop
    Processing --> Error : fault
    Error --> Idle : reset
```


### Gantt Chart Demo
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title  Project Timeline

    section Phase 1
    Research     :a1, 2025-01-01, 5d
    Design       :after a1, 4d

    section Phase 2
    Development  :2025-01-10, 10d
    Testing      :after a1, 7d
```


### Subgraph Demo
```mermaid
flowchart LR
    subgraph Frontend
        A[React App] --> B[Tailwind Styles]
    end

    subgraph Backend
        C[Node Server] --> D[(Database)]
    end

    A --> C
    B --> D
```


### Styling Demo (GitHub Compatible)
```mermaid
flowchart TD
    %% Comments work
    A["Bold Text"] --> B["Italic Text"]
    B --> C["Line<br/>Break"]
    C -.-> D["Inline Code"]
    D --> E["Normal Node"]
    E -.-> F["Dashed Arrow"]
    F -->|Thick| G["Simulated Thick Arrow"]
```


