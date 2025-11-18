# rPPG

Data should be organized in the following format:

---
## UBFC-rPPG  
Dataset link:  
**https://sites.google.com/view/ybenezeth/ubfcrppg**

data/
└── UBFC-rPPG/
    ├── subject1/
    │   ├── vid.avi
    │   └── ground_truth.txt
    ├── subject2/
    │   ├── vid.avi
    │   └── ground_truth.txt
    ├── subject3/
    │   ├── vid.avi
    │   └── ground_truth.txt
    └── subjectN/
        ├── vid.avi
        └── ground_truth.txt
---
## UBFC-Phys  
Dataset link:  
**https://sites.google.com/view/ybenezeth/ubfc-phys**

data/
└── UBFC-Phys/
    ├── T1/
    │   ├── s1/
    │   │   ├── video.avi
    │   │   └── bvp.csv
    │   ├── s2/
    │   │   ├── video.avi
    │   │   └── bvp.csv
    │   └── sN/
    │       ├── video.avi
    │       └── bvp.csv
    ├── T2/
    │   └── s1/
    │       ├── video.avi
    │       └── bvp.csv
    └── T3/
        └── s1/
            ├── video.avi
            └── bvp.csv
---

## iBVP-Dataset  
Dataset link:  
**https://github.com/PhysiologicAILab/iBVP-Dataset**

Organized into 4 sessions:

- **T1 — Rest** (session `_a`)  
- **T2 — Stress** (session `_b`)  
- **T3 — Motion** (session `_c`)  
- **T4 — Talking** (session `_d`)  

data/
└── iBVP_Dataset/
    ├── T1/               
    │   ├── p02/
    │   │   ├── video.avi
    │   │   ├── gt_bvp.txt
    │   │   └── timestamps.txt
    │   └── pNN/
    ├── T2/               
    │   └── p02/
    ├── T3/                
    │   └── p02/
    └── T4/                
        └── p02/
---

## COHFACE  
Dataset link:  
**https://www.idiap.ch/en/scientific-research/data/cohface**

data/
└── cohface/
    ├── 1/
    │   ├── data.avi
    │   └── data.txt
    ├── 2/
    │   ├── data.avi
    │   └── data.txt
    ├── 3/
    │   ├── data.avi
    │   └── data.txt
    └── 40/
        ├── data.avi
        └── data.txt
    └── protocols/
        ├── default.yml
        ├── lighting.yml
        └── motion.yml
---
