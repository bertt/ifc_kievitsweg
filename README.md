# ifc_kievitsweg

3D Tiles from model https://github.com/Geonovum/GeoBIM_Georefereren/blob/main/data/Kievitsweg_R25_ILS%20Spaces%2020250815_LoGeoRef.ifc

1] Ion

https://bertt.github.io/ifc_kievitsweg/ion

Indeling:

```mermaid
graph TD
ROOT[tiles/0/0/0/0.glb]


%% Level 1
ROOT --> A[tiles/1/0/0/0.glb]
ROOT --> B[tiles/1/1/0/0.glb]
ROOT --> C[tiles/1/0/1/0.glb]
ROOT --> D[tiles/1/1/1/0.glb]


%% Level 2 - A
A --> A1[tiles/2/1/0/0.glb]
A --> A2[tiles/2/0/1/0.glb]
A --> A3[tiles/2/1/1/0.glb]


%% Level 2 - B
B --> B1[tiles/2/2/0/0.glb]
B --> B2[tiles/2/2/1/0.glb]


%% Level 2 - C
C --> C1[tiles/2/0/2/0.glb]
C --> C2[tiles/2/1/2/0.glb]
C --> C3[tiles/2/1/3/0.glb]


%% Level 2 - D
D --> D1[tiles/2/2/2/0.glb]
D --> D2[tiles/2/2/3/0.glb]
```

2] Py3dtiles

command:

```bash
py3dtiles convert kievitsweg.ifc
```

Issue: something with crs

Demo: https://bertt.github.io/ifc_kievitsweg/py3dtiles/


