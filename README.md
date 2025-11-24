### DDD-2025-Group 08
Ruben Bähler; Riccardo Assirelli; Lynn Germiquet
# Silent Messengers: Amino acid concentration on samples from asteroids Orgueil, Murchison, Ryugu and Bennu

### Visualisation
![Data viz](Screenshot-Dataviz.png)

Link to visualisation: https://vimeo.com/1140051617?fl=pl&fe=sh


### Abstract
The visualisation is based on nmol/g data extracted from sample analysis simplified 
to arbitrary numbers to aid with the data visualisation. The data is converted from raw numerical data to a visual pattern that represents the density of carbolxylic and amino acids as well as amines on each of the 4 asteroids represented.

Data from NASA’s OSIRIS-REx mission (Bennu) reveal hydrated minerals, organic molecules, and energy gradients — all the ingredients of pre-biotic organization 
and the start point of life forms.


### Protocol Diagram
```mermaid
    flowchart TD

%% ============================
%% PRELIMINARY RESEARCH
%% ============================

A["Silent Messengers: Aminoacid concentration on samples from asteroids Orgueil, Murchison, Ryugu and Bennu"]

A --> B1["Asteroids"]
A --> B2["Organic vs unorganic"]

B1 --> C1["Amino acids are related to the origin of life"]
B2 --> C2["Which asteroids contain the most amount of amino acids?"]

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

I1 --> J1["What information is relevant to us?"]
I2 --> J2["Manually downloading images"]
I3 --> J3["Manually review and categorize\important dataset contents"]

J1 --> K((Google spreadsheets & Figma))
J2 --> K
J3 --> K

%% ============================
%% DATASET BUILDING
%% ============================

K --> L["Data Framing"]

L --> M1["Images"]
L --> M2["Amount & types of Amino acids"]
L --> M3["Asteroids"]

M1 --> N((Google spreadsheets, Figma, Python & Adobe PremierePro))
M2 --> N
M3 --> N

N --> O1["Selecting images of collection"]
N --> O2["Amino acids categorization"]
N --> O3["Collect information about historical & scientific impact of asteroids"]

%% ============================
%% DATA VISUALIZATION
%% ============================

O1 --> P((Figma))
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
