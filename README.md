### DDD-2025-Group 08
Ruben Bähler; Riccardo Assirelli; Lynn Germiquet
# Silent Messengers: Aminoacid concentration on samples from asteroids Orgueil, Murchison, Ryugu and Bennu

### Visualisation
[Delete this for final delivery] *Upload here your visualisation. You can use a screenshots, a video/gif (if you need to show the interaction)*

![ScreenRecording2025-11-19at16 59 27-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/417f8a88-694f-484c-9e0b-bd96dab792a2)



#### Link to the prototype or website (if available)
https://www.jasondavies.com/wordtree/?source=obama.inauguration.2013.txt&prefix=devastating 


### Abstract (300 charachters)
This project maps amino-acid concentrations in Orgueil, Murchison, Ryugu, and Bennu. Using images, chemical datasets, and added historical and scientific context, it visualizes and compares patterns that shed light on organic origins in the early solar system.

### Protocol Diagram
```mermaid
graph TD
    % Phase 1: Project Initiation (Styled as the initial black box)
    A[Project Initial Assessment]:::startNode
    
    A --> B1[Review Project Criteria]
    A --> B2[Gather External Information]
    
    % Phase 1: Data Identification and Gathering
    B1 --> C1[Identify Necessary Data]
    B2 --> C2[Analyze Available Data Points]
    
    % Phase 1: Input Standardization (Hexagon in the sketch)
    C1 --> D{Standardize Input Parameters}
    C2 --> D

    % Phase 2: Core Logic (Styled as the CORE black box)
    D --> E[CORE: Execute Initial Transformation & Mapping]:::coreProcess

    % Phase 2: Validation
    E --> F{Data Integrity Pass?}
    F -- "No" --> G((Error Handler))
    G --> A % Error loop back to Project Start
    F -- "Yes" --> H((Validation Complete))

    % Phase 3: Data Store Checks (Cylinder/Database shapes)
    H --> I1[(System A Data Store)]
    H --> I2[(System B Data Store)]
    H --> I3[(System C Data Store)]

    % Phase 3: Readiness Decisions
    I1 --> J1{A is Ready?}
    I2 --> J2{B is Ready?}
    I3 --> J3{C is Ready?}

    % Polling/Waiting for Readiness
    J1 -- "No" --> H
    J2 -- "No" --> H
    J3 -- "No" --> H
    
    % Convergence and Aggregation
    J1 -- "Yes" --> K
    J2 -- "Yes" --> K
    J3 -- "Yes" --> K
    K[Aggregate Results] --> L[Generate Interim Report]

    % Phase 4: Review Cycle (Parallel steps)
    L --> M1[Client Approval Needed]
    L --> M2[Internal Review]
    L --> M3[External Dependency]

    M1 --> N{Final Check Passed?}
    M2 --> N
    M3 --> N

    % Rework Loop
    N -- "No" --> O((Rework Required))
    O --> L 
    
    % Phase 5: Finalization
    N -- "Yes" --> P[Prepare Final Artifact]
    P --> Q((Deploy to Target System))
    Q --> R[[End Process]]:::endNode

    % Custom Styling to match the sketch's visual elements
    classDef startNode fill:#000, color:#fff, stroke:#000, stroke-width:4px;
    classDef coreProcess fill:#000, color:#fff, stroke:#000, stroke-width:4px;
    classDef endNode fill:#eee, stroke:#000, stroke-width:2px;
```

### What topic does the project address?
The project explores how amino acids are distributed in asteroid and meteorite samples to better understand the origins of organic matter in the solar system, and potentially the origins of life.

### What data have you considered?
We used two main types of data:
1. Images of asteroid and meteorite samples
* High-resolution images of the four samples:
* Orgueil
* Murchison
* Ryugu
* Bennu
These images served as the base layer for visualizing where amino acids were detected across each sample.

2. Datasets of amino-acid concentrations
We used quantitative datasets showing the concentration and spatial distribution of various amino acids within each sample.
These datasets allowed us to:
* Plot points directly on the sample images
* Color-code the points based on concentration level
* Compare amino-acid abundance between the different asteroids/meteorites

![Dataset](https://github.com/rubenroesti/DDD-2025-Group08/blob/main/Screenshot%20dataset.png?raw=true)

#### Link to the dataset
https://www.nature.com/articles/s41550-024-02472-9

### What does the visualisation show?
#### 1. Amino-acid concentration maps
Each asteroid image displays a grey silhouette of the sample with colored dots overlaid:
- Yellow, green, and red points indicate relative concentrations of different amino acids.
- The color bar at the bottom (green → yellow → red) represents low to high amino-acid abundance.
- This lets you visually compare how amino acids are distributed across each sample.

#### 2. Historical & scientific context
Below each asteroid, there is scrollable text describing:
- Name & type (e.g., CI1 chondrite, carbonaceous asteroid)
- Sample mass
- Collection date/location
- Historical impact – why each meteorite/asteroid sample is scientifically important
(e.g., Orgueil’s role in early organic-matter studies, Ryugu/Bennu being part of spacecraft sample-return missions).

#### 3. Purpose of the visualization
The graphic is meant to show:
- How organics vary across different primitive solar system bodies.
- How the distribution of amino acids differs between older meteorite falls (Orgueil, Murchison) and recent sample-return missions (Ryugu, Bennu).
- How these findings connect to the study of the origins of life and prebiotic chemistry.
