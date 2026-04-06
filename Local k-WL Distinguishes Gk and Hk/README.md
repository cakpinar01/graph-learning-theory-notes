# Local k-WL Distinguishes CFI Graphs

This note shows that **local k-WL can distinguish the CFI graphs \(G_k\) and \(H_k\)**.

## Contents

- `notes.pdf` → proof explanation  
- `demo.ipynb` → small illustration  

## Main Idea

Local k-WL operates on **k-tuples with neighborhood-restricted updates**, which allows it to capture richer structural information than standard WL in this setting.

In particular, local k-WL can detect a **distance-two clique of size \(k+1\)** in \(G_k\),  
while such a structure cannot exist in \(H_k\) due to the parity modification at a distinguished vertex.

This difference is reflected in the **unrolling trees**, leading to different stable colorings.

## Notes

This is a personal explanatory note written in my own words.

## Acknowledgment

Based on the course *Machine Learning on Graphs*  
(Prof. Christopher Morris, RWTH Aachen, WS 2025).
