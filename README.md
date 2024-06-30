# APP MOVIL
Mobile application for the management of physical training routines in gyms.

## Introduction
TinyDecisionTreeClassifier is a simple but elegant standalone library for training decision trees directly on the edge. Decision trees were chosen since they are very fast and easily interpretable. 

Main features are:
- Based around classic C4.5 decision tree algorithm for continious variables.
- This is a standalone library. Since the library depends only on <stdint.h>, <stddef.h>,<stdlib.h>, "math.h" and "float.h" it can easily be ported to other frameworks like Mbed/ESP-IDF. 
- Fast and small. Checkout the benchmarking examples for Arduino Uno, Esp32 and NRF52840 provided in examples folder and the benchmarking graph.
- Simple to use. I tried to make the methods similar to the DecisionTreeClassifier from scikit-learn. If you ever used it, you will quickly recognize the familiar names like fit(), predict() and score().
- The average comlexity is O(Nlog(N)) (because of the quicksort).
- Template usage allows to train 8-bit models, which boosts performance on 8-bit MCUs and significantly reduces RAM requirements.
- Trained tree visualisation is supported via plot() method.

## Installation


## Benchmarking


## Examples
