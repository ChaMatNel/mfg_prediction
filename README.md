# Project Description
This project uses machine learning models to predict manufacturing outputs based on real manufacturing data. The data comes from a multi-stage continuous flow manufacturing process. In the first stage, Machines 1, 2, and 3 operate in parallel, and feed their outputs into a step that combines the flows. Output from the combiner is measured in 15 locations surrounding the outer surface of the material exiting the combiner. Next, the output flows into a second stage, where Machines 4 and 5 process in series. After Machine 5, measurements are made again in the same 15 locations surrounding the outer surface of the material exiting Machine 5.

```
   Stage 1                                                    Stage 2                          
[Machine 1]  ─┐
              │
[Machine 2]  ─┼─> [Combiner] ─> [15 Measurement Points] ─> [Machine 4] ─> [Machine 5] ─> [15 Measurement Points]
              │
[Machine 3]  ─
```

The goal is to predict the output measurements from the first and second stages.

# Results


I was able to achieve a 68% accuracy on first stage measurements with a 


The goal is to predict the 15 measurement points based on machine input data

# Source
https://www.kaggle.com/datasets/supergus/multistage-continuousflow-manufacturing-process
