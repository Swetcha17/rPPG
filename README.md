# rPPG

Data should be organized in the following format:

---

# Data/

## UBFC-rPPG  
Dataset link:  
**https://sites.google.com/view/ybenezeth/ubfcrppg**

UBFC-rPPG/
subject1/
vid.avi
ground_truth.txt
subject2/
vid.avi
ground_truth.txt
...

---

## UBFC-Phys  
Dataset link:  
**https://sites.google.com/view/ybenezeth/ubfc-phys**

UBFC-Phys/
T1/
s1/
video.avi
bvp.csv
s2/
video.avi
bvp.csv
...
T2/
s1/
video.avi
bvp.csv
T3/
s1/
video.avi
bvp.csv

---

## iBVP-Dataset  
Dataset link:  
**https://github.com/PhysiologicAILab/iBVP-Dataset**

Organized into 4 sessions:

- **T1 — Rest** (session `_a`)  
- **T2 — Stress** (session `_b`)  
- **T3 — Motion** (session `_c`)  
- **T4 — Talking** (session `_d`)  

iBVP_Dataset/
T1/ <- rest (session _a)
p02/
video.avi
gt_bvp.txt
timestamps.txt
p03/
...
T2/ <- stress (session _b)
p02/
...
T3/ <- motion (session _c)
p02/
...
T4/ <- talking (session _d)
p02/
...

---

## COHFACE  
Dataset link:  
**https://www.idiap.ch/en/scientific-research/data/cohface**

cohface/
1/
data.avi
data.txt
2/
data.avi
data.txt
3/
data.avi
data.txt
...
40/
data.avi
data.txt
protocols/
default.yml
...

---
