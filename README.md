### DDD-2025-Group 08
Ruben Bähler; Riccardo Assirelli; Lynn Germiquet
# Silent Messengers: Aminoacid concentration on samples from asteroids Orgueil, Murchison, Ryugu and Bennu

### Visualisation
[Delete this for final delivery] *Upload here your visualisation. You can use a screenshots, a video/gif (if you need to show the interaction)*

![ScreenRecording2025-11-19at16 59 27-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/417f8a88-694f-484c-9e0b-bd96dab792a2)



#### Link to the prototype or website (if available)
https://www.jasondavies.com/wordtree/?source=obama.inauguration.2013.txt&prefix=devastating 


### Abstract (300 charachters)
This project visualizes amino-acid concentrations in samples from Orgueil, Murchison, Ryugu, and Bennu. Using images, chemical datasets, and added historical and scientific context, it maps and compares patterns that illuminate early solar-system organics.

### Protocol Diagram
```mermaid
flowchart TD
  A["Topic:<br/>Human–Alien Communication"] --> B["Research question"]
  B --> C{"Collect data"}

  C --> D["Online posts<br/>Reports<br/>Shared experiences"]
  C --> E["Public archives"]

  C --> DS[("Dataset:<br/>Space Signal Collection")]

  DS --> COL1["Column 1:<br/>Intercepted radiofrequencies"]
  DS --> COL2["Column 2:<br/>SETI audio tracks"]

  D --> F{"Organize & code"}
  E --> F
  COL1 --> F
  COL2 --> F

  F --> G["Grouped dataset"]

  G --> H{"Analysis"}

  H --> I["Recurring themes"]
  H --> J["Collective attention"]

  G --> K{"Transform"}
  K --> L["Timelines"]
  K --> M["Location-based views"]

  I --> N{"Interpretation"}
  J --> N
  L --> N
  M --> N

  N --> O["Insights:<br/>Shared narratives<br/>Signal waves<br/>Ideas about contact"]
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
