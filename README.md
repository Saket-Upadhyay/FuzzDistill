# FuzzDistill: Intelligent Fuzzing Target Selection using Compile-Time Analysis and Machine Learning

## Abstract
Fuzz testing is a fundamental technique employed to identify vulnerabilities within software systems. However, the process can be protracted and resource-intensive, especially when confronted with extensive codebases. In this work, I present FuzzDistill, an approach that harnesses compile-time data and machine learning to refine fuzzing targets. By analyzing compile-time information, such as function call graphs' features, loop information, and memory operations, FuzzDistill identifies high-priority areas of the codebase that are more probable to contain vulnerabilities. I demonstrate the efficacy of my approach through experiments conducted on real-world software, demonstrating substantial reductions in testing time while maintaining a high level of vulnerability detection.


## Modules
| Module       | Description                                                        |
|----------------------|--------------------------------------------------------------------|
| [FuzzDistillCC](https://github.com/Saket-Upadhyay/FuzzDistillCC)  | Compiler back-end for feature extraction                                |
| FuzzDistillML    | Model training component                                  |
| FuzzDistillWeb    | Prediction front-end                                 |

## Paper
More like a report (not peer-reviewed).

|What|Where|
|----|---|
|PDF| TBD |
|arXiv| TBD |
|Presentation| TBD|

---

### Acknowledgement
This project was facilitated by the opportunities provided in the graduate class ``CS 6501: Software Security Testing'', led by Dr. Jack Davidson, Dr. Jason Hiser, and Dr. Anh Nguyen-Tuong at the University of Virginia.
I would like to express my sincere gratitude to all the instructors for creating an environment that fostered exploration and innovation, enabling me to delve into the intersection of fuzz testing and machine learning. The guidance and support received throughout the course were instrumental in shaping this project.
