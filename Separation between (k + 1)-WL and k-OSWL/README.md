# Separation between (k + 1)-WL and k-OSWL

This note shows that k-OSWL is strictly more expressive than (k+1)-WL on certain graph constructions (CFI graphs).

## Contents
- notes.pdf → detailed proof and explanation
- demo.ipynb → small illustration

## Main Idea
(k+1)-WL cannot distinguish the graphs G_{k+1} and H_{k+1}, but k-OSWL can.

The reason is:
- WL captures limited structural information
- k-OSWL can encode additional distance-based structure

In particular, k-OSWL detects a distance-two clique of size k+2, which exists in G_{k+1} but not in H_{k+1}.

## Notes
This is a personal explanatory note written in my own words.

## Acknowledgment
Based on the course Machine Learning on Graphs  
(Prof. Christopher Morris, RWTH Aachen, WS 2025).
