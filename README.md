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
    flowchart TD

%% ============================
%% PRELIMINARY RESEARCH
%% ============================

A["Silent Messengers: Aminoacid concentration on samples from asteroids Orgueil, Murchison, Ryugu and Bennu"]

A --> B1["asteroids"]
A --> B2["organic vs"]

B1 --> C1["amino acids are related to the origin of life"]
B2 --> C2["which asteroids contain the most amount of amino acids?"]

C1 --> D["How effectively can a grain chart, centered on asteroid images, visually compare the amount of amino acids in Orgueil, Murchison, Ryugu & Bennu to help understand their prebiotic chemical potential, with a focus on amino acids, for life beyond earth?"]
C2 --> D

D --> E["Searching for which asteroids contain the most amino acids"]

E --> F["Google"]

%% ============================
%% DATA COLLECTION
%% ============================

F --> G["sites"]

G --> H1((Google))
G --> H2((NASA))
G --> H3((Other))

H1 --> I1["Datasets about Bennu samples"]
H2 --> I2["Dataset about asteroids containing the most amino acids"]
H3 --> I3["Images from asteroids Orgueil, Murchison, Ryugu & Bennu"]

%% ============================
%% DATA ANALYSIS
%% ============================

I1 --> J1["what information is relevant to us?"]
I2 --> J2["manually downloading images"]
I3 --> J3["Manually review and categorize\important dataset contents"]

J1 --> K((Scope and\nRequirements Logic))
J2 --> K
J3 --> K

%% ============================
%% DATASET BUILDING
%% ============================

K --> L["Data Framing"]

L --> M1["Merge"]
L --> M2["Attribute Enrichment"]
L --> M3["Validate"]

M1 --> N((Identify gaps,\nconcerns,\nand targets))
M2 --> N
M3 --> N

N --> O1["Improve metadata standards"]
N --> O2["Service-level categorization"]
N --> O3["Theme-level dataset comparisons"]

%% ============================
%% DATA VISUALIZATION
%% ============================

O1 --> P((Figure))
O2 --> P
O3 --> P

P --> Q["Data Visualization"]

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
